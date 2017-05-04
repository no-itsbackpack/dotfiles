Bits and pieces taken from all over GitHub.

### Install
#### `script/install`

    bash -c "$(curl -fsSL raw.github.com/paddingtonsbear/dotfiles/master/script/install)"

Always read a script before you curl: [https://github.com/paddingtonsbear/dotfiles/blob/master/script/install](https://github.com/paddingtonsbear/dotfiles/blob/master/script/install)

This will install:

- [zsh](https://github.com/robbyrussell/oh-my-zsh)
- [rbenv](https://github.com/sstephenson/rbenv)
- [ruby-build](https://github.com/sstephenson/ruby-build)
- various config files

If the installer finds an existing file when symlinking, it will skip it.

### Uninstall
#### `script/uninstall`

This will remove all of the symlinks and the vim plugins.
