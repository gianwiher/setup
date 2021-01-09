## Basic setup for OsX
scripts and files to setup a dev enwironment for macOS. Inspired by [Corey schafer](https://github.com/CoreyMSchafer/dotfiles)

### Install brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### Install iterm2
```bash
brew install --cask iterm2
```

### Setup ZSH
Install zsh
 ```bash
 brew install zsh
 ```
  ```bash
 chsh -s /usr/local/bin/zsh
 ```
Install oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Get [Powerlevel10k](https://github.com/romkatv/powerlevel10k) theme
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
### Install important programs using brew

