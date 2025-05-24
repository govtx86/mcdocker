## Install packages
```
sudo pacman -S git zsh docker docker-compose cloudflared htop curl wget
```
## Script permission
```
sudo chmod +x ~/bin/*
```
## Start docker service
```
sudo systemctl enable docker.socket
```
```
sudo systemctl start docker.socket
```

## Add user to docker group
```
sudo groupadd docker
```
```
sudo usermod -aG docker $USER
```

# Post-Setup

## Start script
```
wsl --shell-type login source ~/.zshrc; startServer
```
## Stop script
```
wsl --shell-type login source ~/.zshrc; stopServer
```
## Add discord chat permission
```
lp group default permission set essentials.discord.receive.chat
```
