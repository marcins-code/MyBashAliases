## Bash aliases for daily use

```bash
#Main
alias c="clear"
alias h="history"
alias bslist="brew services list"
alias bsstop="brew services stop"
alias bsstart="brew services start"
alias bsrestart="brew services restart"
alias arestart="sudo apachectl -k restart"
alias astart="sudo apachectl -k start"
alias astop="sudo apachectl -k stop" 
alias sdown="sudo shutdown -h now" 

#Symfony
alias sc="php bin/console"
alias scaw=" php bin/console debug:autowiring"
alias scawa=" php bin/console debug:autowiring --all"
alias scdr=" php bin/console debug:route"
alias sst="symfony server:start"
alias scmke="php bin/console make:entity" 
alias scmkmg="php bin/console make:migration"
alias scdmm="php bin/console doctrine:migrations:migrate" 
alias scmkct="php bin/console make:controller" 
alias scmkcr="php bin/console make:crud" 
alias scmkfr="php bin/console make:form" 
alias sccc="php bin/console cache:clear" 


#GIT
alias gsts="git status"
alias gadd="git add"
alias gcmm="git commit -m"
alias gcm="git commit"
alias gckout="git checkout"
alias gbranch="git branch"
alias ggraph="git log --oneline --decorate --graph --all"
alias gmerge="git merge"
alias gps="git push"
alias gft="git fetch"
alias gpl="git pull"
alias grs="git reset" 
```
