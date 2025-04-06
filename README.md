# This repository contains a collection of set up guides for various tools and libraries in new machine.

# Set up with MacOS

## 1. Install brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 2. Install tool
### Git
git
```bash
brew install git
```
git-cola
```bash
brew install git-cola
```
gitk
```bash
brew install git-gui
```

### Ruby
```bash
brew install rbenv
```
**Some rbenv commands:**

Set up your shell to load rbenv automatically:
```bash
rbenv init
```
Installing Ruby versions
```bash
# list latest stable versions:
rbenv install -l

# list all local versions:
rbenv install -L

# install a Ruby version:
rbenv install 3.1.2
```
Set a Ruby version to finish installation and start using Ruby:
```bash
rbenv global 3.1.2   # set the default Ruby version for this machine
# or:
rbenv local 3.1.2    # set the Ruby version for this directory
```
**rbenv rehash**
Installs shims for all Ruby executables known to rbenv (~/.rbenv/versions/*/bin/*). Typically you do not need to run this command, as it will run automatically after installing gems.
```bash
rbenv rehash
```
**Note:** If you set `eval "$(rbenv init - zsh)"` in your `.zshrc`, you don't need to run `rbenv rehash` manually.

### BE tools
redis
```bash
brew install redis
```
redis-cli
```bash
brew install redis-cli
```
postgresql
```bash
brew install postgresql
```
awscli
```bash
brew install awscli
```

## Configuration
- [ZSH configuration](zsh/README.md): A guide to set up ZSH with Oh My Zsh and Dracula theme,
  plugins, and common libraries.
- [VSCode configuration](vscode/README.md): A guide to set up Visual Studio Code with recommended extensions, settings.
- [Docker configuration](docker/README.md): A guide to set up Docker with Docker Compose and a sample

