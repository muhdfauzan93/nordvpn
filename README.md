# Nordvpn Meshnet

### Run Docker Container
```
docker run -ti --cap-add=NET_ADMIN --cap-add=NET_RAW ghcr.io/muhdfauzan93/nordvpn/app:latest
```

### Run Docker Compose
```
docker-compose up -d
```

1. Login to Nordvpn

```
nordvpn login
```

1. Copy the url and paste it in the browser. Copied link address and paste it in the terminal.

```
nordvpn login --callback <URL>
```

2. Enable Nordvpn Meshnet
```
nordvpn set meshnet on
```

3. Show peer list
```
nordvpn meshnet peer list
```

4. Allow peer routing
```
nordvpn meshnet peer routing allow <PEER_ID>
```