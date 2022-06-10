# ¯\\\_(ツ)_/¯

- [Shell](#shell)
- [Editor](#editor)

# Shell

## zsh

1. install oh my zsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. `brew install coreutils`

3. install solarized dircolors
```
git clone --recursive git://github.com/joel-porquet/zsh-dircolors-solarized $ZSH_CUSTOM/plugins/zsh-dircolors-solarized

# add following in ~/.zshrc
# plugins=(zsh-dircolors-solarized)
```

4. replace with customized `zshrc`, `dircolors.ansi-dark`, `robbyrussell.zsh-theme` from `zsh/` folder

## Command

[modern unix command line](https://jvns.ca/blog/2022/04/12/a-list-of-new-ish--command-line-tools/)

- [`fd`](https://github.com/sharkdp/fd)
- [`rg`](https://github.com/BurntSushi/ripgrep/#installation)

# Editor

## vim

- install vim from homebrew `brew install vim`

- in Vim, run `:PluginInstall`

## vscode

- copy vscode config files to `~/Library/Application\ Support/Code/User`

## Extra
- user@host in prompt
  - add `PROMPT="%{$fg[cyan]%}%n@%{$fg[blue]%}%m%{$reset_color%} ${PROMPT}"` in `~/.zshrc`
