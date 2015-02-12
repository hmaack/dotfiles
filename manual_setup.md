# Rails development Environment on OS X Yosemite

## Command Line Tools

```bash
$ xcode-select --install
```

## Homebrew

```bash
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew doctor
```

Install Ruby and set it as the default version

```bash
$ \curl -sSL https://get.rvm.io | bash -s stable --ruby

$ ruby -v
# ruby 2.2.*
```

## Zsh

```bash
$ brew install zsh
$ chsh -s /usr/local/bin/zsh
$ curl -L http://install.ohmyz.sh | sh
```

## Requirements for SublimeLinter-*

```bash
$ gem install scss-lint
$ gem install rubocop
$ gem install haml

$ brew install node
$ npm install -g jshint
$ npm install -g coffeelint
```
