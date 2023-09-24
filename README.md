# @dennishoyer | Docker Stacks

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
