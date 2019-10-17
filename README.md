A docker-compose configuration for [certbot](https://certbot.eff.org).

## Quick Start

Edit the `.env` file to contain your domain name and email address.

```
DOMAIN=example.com
EMAIL=me@example.com
```

Run the service.

```
docker-compose up
```

SSL credentials will be in `etc/live/DOMAIN`.
