# docker / Docker-compose Abbreviation

```
dk='docker'
dkc='docker-compose'

dki='docker image'
dkps='docker ps'
dkps='docker ps'
dkb='docker build'
dkcu='docker-compose up $1'
dkcub'docker-compose up $1 --build'

dke='docker exec'
dkeit='docker exec -it '
dkr='docker run'
dkrit='docker run -it '

dkspa='docker system prune -a '
dkrma='docker rm $(docker ps -a -q)'
dkrmia='docker rmi $(docker images -q)'
```

## Install:

### Install docker and docker-compose

### Clone from github
```
    cd ~/.oh-my-zsh/custom/plugins
    git clone https://github.com/tamnil/docker-abbreviation
```
### Load the plugin ins .zshrc

~/.zshrc  : 

    plugins=( [...] docker-abbreviation )


    Start a new ZSH session or reload the configuration:


```
    source ~/.zshrc

```
