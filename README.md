# docker-alias
Docker command alias to improve productivity

alias dslogs="docker service logs"<br>
alias dsls="docker service ls"<br>
alias dslsg="docker service ls | grep"<br>
alias dpsg="docker ps | grep"<br>
alias dex="docker exec -it"<br>
alias dsup="docker service update"<br>
alias dsrm="docker service rm"<br>
alias ddeploy="docker stack deploy -c"<br>
alias dsps="docker service ps"<br>

## How to use
Put it in your ~/.bash_rc or your ~/.zshrc and then use the following command to apply the aliases:
```
source ~/.bash_rc
```