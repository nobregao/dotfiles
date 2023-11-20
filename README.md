# dotfiles

my dotfiles

## Tools

* install [homebrew](http://brew.sh)
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

* install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh):
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)
```

* basic tools:

```shell
brew install fzf
brew install starship
```

* install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md):

```shell
brew install zsh-autosuggestions
#activate
source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh

```

1. install the languages and package managers:

```shell
brew install asdf

asdf plugin-add java
asdf install java latest
asdf global java latest

asdf plugin-add maven
asdf install maven latest
asdf global maven latest

asdf plugin-add python
asdf install python latest
asdf global python latest
```