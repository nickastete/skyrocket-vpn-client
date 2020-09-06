# Skyrocket Staging VPN client

1. Ask for a Tailscale auth key.
2. Create an env file with the key, as follows:
```
  $ echo TAILSCALE_AUTH=YOUR_KEY_HERE > tailscale_auth.env
```
3. Run `docker-compose up`
4. Nagivate to http://localhost:8000