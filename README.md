# Docker minecraft server setup in github codespace

Docker minecraft server hosted in github codespace with automatic shutdown after server is empty for 5 minutes

## Requirements
- docker and docker compose
- cloudflared

## Environment variables
Set `$DISCORD_WEBHOOK_URL` to discord webhook to url

## Running server
Start server
```
./startserver
```
Show server logs
```
./mclogs
```
Show server console
```
./mccli
```
Stop server
```
./mcstop
```
