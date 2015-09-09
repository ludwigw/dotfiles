# dotfiles

1. Clone to path (`$HOME/.bin/bash/bash_entrypoint`)
2. Load up in `.bash_profile`

```sh

## LOAD DEFAULT DOTFILES

[[ -r $HOME/.bin/bash/bash_entrypoint ]] && source $HOME/.bin/bash/bash_entrypoint

## CUSTOM TO MACHINE HERE

# Add psql
export PATH=$PATH:/Applications/Postgres.app/Contents/Versions/9.4/bin


```
