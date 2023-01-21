# zshconfig


**MOVED TO [shellconfig](https://github.com/MB3hel/shellconfig) repo!**



This repo holds my zsh configuration.

## Installation
- Install [Oh My Zsh](https://ohmyz.sh/)
- Clone this repo to `~/.zshconfig`
- Populate `~/.zshrc` with the following

```sh

# Load generic zsh configuration
. ~/.zshconfig/zshrc

# System specific Environment Variables & other settings below

```

- Populate `~/.zprofile` with the following

```sh
emulate sh
. ~/.profile
emulate zsh
```
