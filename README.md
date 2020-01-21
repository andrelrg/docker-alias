# docker-alias
Docker command alias to improve productivity

alias dslogs="docker service logs"
alias dsls="docker service ls"
alias dslsg="docker service ls | grep"
alias dpsg="docker ps | grep"
alias dex="docker exec -it"
alias dsup="docker service update"
alias dsrm="docker service rm"
alias ddeploy="docker stack deploy -c"
alias dsps="docker service ps"

## How to use
Put it in your ~/.bash_rc or your ~/.zshrc and then use the following command to apply the aliases:
```
source ~/.bash_rc
```