Start script
```
wsl --shell-type login source ~/.zshrc; startServer
```
Stop script
```
wsl --shell-type login source ~/.zshrc; stopServer
```
Add discord chat permission
```
lp group default permission set essentials.discord.receive.chat
```
