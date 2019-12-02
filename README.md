# bash-config
Notes from the dotfiles

```bash
## PAPERTRAIL
alias "pt"="papertrail"
alias "metrics"="papertrail -s <app> --min-time 'yesterday at 01:00' <string> | cut -f 7 -d ' ' | sort | uniq -c"

## VIRTUAL BOX CONFIG //08082012 -BB
export PATH=/opt/local/bin:/opt/local/sbin:$PATH
export MANPATH=/opt/local/share/man:$MANPATH

## Path to local OSX Apache HTML Docs
alias "local"='cd /Library/WebServer/Documents/'

