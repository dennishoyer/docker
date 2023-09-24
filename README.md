# @dennishoyer | Docker Stacks

# Usage

    git clone https://github.com/codingPear/home-assistant-docker-compose.git
    cd home-assistant-docker-compose
    nano -l .env #or whatever editor you prefer
    (change default settings & save)
    docker-compose up -d
    
    
## Stacks

### System stack

**Environment variables**

```
TUNNEL_TOKEN=CLOUDFLARE-TUNNEL-TOKEN
```

**Images used in stack**
- cloudflare
- portainer

### Home stack

**Environment variables**

```
TUNNEL_TOKEN=CLOUDFLARE-TUNNEL-TOKEN
```

**Images used in stack**
- cloudflare
- homeassistant

### Data stack

**Environment variables**

```
TUNNEL_TOKEN=CLOUDFLARE-TUNNEL-TOKEN
```

**Images used in stack**
- postgres
- influxdb
- grafana
