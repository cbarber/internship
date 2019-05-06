---
title: Introduction
root: '/docs'
parents: ['Get Started']
---

<h1 align="center">
  Introduction
</h1>

# Mojotech Internship documentation

Wifi: mojotech
Slack

## Brew

Brew is package manager for mac osx. https://brew.sh/
```sh
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## iTerm2

Terminal replacement for mac os x. https://www.iterm2.com
```sh
brew cask install iterm2
```

## Shell

Bash is a little lackluster and switching to fish/zsh can greatly improve functionality. fish is a pretty easy shell to start with.  https://fishshell.com/
```sh
brew install fish
echo "/usr/local/bin/fish" | sudo tee -a /etc/shells
chsh - s /usr/local/bin/fish
```

### oh-my-fsh
```sh
curl -L https://get.oh-my.fish | fish
```

### bob-the-fish
```sh
omf install bobthefish
```

## fzf

fzf is a fuzzy file finder with shell integration (CTRL-T, CTRL-R, and ALT-C)
```sh
brew install fzf
/usr/local/opt/fzf/install
```

## git
```sh
brew install git
```

## docker

## nvm

## rvm
