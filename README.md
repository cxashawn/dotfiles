# ¯\\\_(ツ)_/¯

## zsh

1. install oh my zsh

2. `brew install coreutils`

3. install solarized dircolors
```
git clone --recursive git://github.com/joel-porquet/zsh-dircolors-solarized $ZSH_CUSTOM/plugins/zsh-dircolors-solarized

# add following in ~/.zshrc
# plugins=(zsh-dircolors-solarized)
```

4. use customized `zshrc`, `dircolors.ansi-dark`, `robbyrussell.zsh-theme`

## vim

- in Vim, run `:PluginInstall`

## vscode

- copy vscode config files to `~/Library/Application\ Support/Code/User`

## Extra
- user@host in prompt
  - add `PROMPT="%{$fg[cyan]%}%n@%{$fg[blue]%}%m%{$reset_color%} ${PROMPT}"` in `~/.zshrc`
