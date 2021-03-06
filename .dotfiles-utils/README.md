## Prerequisites

[Homebrew](http://brew.sh/) and [`brew cask`](https://github.com/phinze/homebrew-cask) are required to install the default formulae and applications defined here.


## Installation

### Configure Mac

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

### Install Homebrew formulae

When setting up a new Mac, you may want to install some common [Homebrew](http://brew.sh/) formulae (after installing Homebrew, of course):

```bash
brew bundle ./Brewfile
```

### Install native apps with `brew cask`

You could also install native apps with [`brew cask`](https://github.com/phinze/homebrew-cask):

```bash
./.cask
```
