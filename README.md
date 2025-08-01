# metakermit's dotfiles ~/.*

After looking at the many [interesting dotfile solutions](http://dotfiles.github.io/), I decided to go the build-your-own-lightsaber road after all. So here goes…

## Installation
On a clean Ubuntu machine, do:

    wget -O - https://raw.githubusercontent.com/metakermit/dotfiles/master/meta/install-linux.sh | bash

On macOS do:

    bash <(curl -s https://raw.githubusercontent.com/metakermit/dotfiles/master/meta/install-mac.sh)

Alternatively, if you already have `git` and you cloned this repository,
in Ubuntu just do:

    ./meta/install-linux.sh

or on a Mac:

    ./meta/install-mac.sh

## TODO

- [ ] Store kermit-location inside the scripts folder
- [ ] Add k script prefix with tab-completed subcommands (argparse+genzshcomp, OptionParser or trollop)
- [ ] Move additional customizations to separate file (too custom to my preferences)
- [ ] Install essential programs platform-independently

## Changelog

- Add emacs config [metakermit/kermit-emacs](https://github.com/metakermit/kermit-emacs)
- Install script inspired by [this tutorial](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)

## Credits

- meta/install.sh inspired by [holman/dotfiles bootstrap script](https://github.com/holman/dotfiles/blob/master/script/bootstrap)
