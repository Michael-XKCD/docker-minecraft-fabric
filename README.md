# docker-minecraft-fabric

Docker Compose stack for a Minecraft Fabric server with built-in hourly and daily backups.

## Includes

- Fabric server runtime
- hourly backup sidecar
- daily backup sidecar
- Packwiz modpack source under `packwiz/`

## Notes

- this repo is intentionally public so the Packwiz manifest can be fetched directly
- secrets and host-specific paths should live in downstream env/secrets, not here
