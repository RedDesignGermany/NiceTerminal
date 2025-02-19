#  a Nicer Terminal
Make your mac terminal prompt (.zshrc) a bit nicer.

Open your .zshrc file, which is usually saved under your user name: 

/users/.zshrc

or

~/.zshrc

### Changes of prompt
```zsh
PROMPT='%F{89}path: %~%f'   # “path: ” followed by the current path in the first line
PROMPT+='
'   # Creates a new line after the path
PROMPT+='%F{75}%n@%m%f %# '  # Username and hostname in the second line
```

### Alias for ls with colors
```zsh
alias ls='ls -l -a -G -p'
```
or
```zsh
alias ls='ls -a -G -p'
```

### LS_COLORS for the color configuration
```zsh
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```
