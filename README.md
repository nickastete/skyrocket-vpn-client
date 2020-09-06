# Skyrocket Staging VPN client

1. Check out this repository.
2. Ask for a Tailscale auth key.
3. Inside this repository's directory, create an env file with the Tailscale key, as follows:
```
  $ echo TAILSCALE_AUTH=YOUR_KEY_HERE > tailscale_auth.env
```
4. Run `docker-compose up`
5. Nagivate to http://localhost:8000