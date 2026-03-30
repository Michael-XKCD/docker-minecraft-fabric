# Consumption Notes

This stack repo contains the reusable runtime compose wrapper for the Minecraft Fabric server.

Expected downstream overlays should supply:

- external/shared network attachments for public access
- Pangolin raw TCP labels
- any host-specific hardening or policy labels

Expected downstream env or overlays may override:

- image tags
- bind-mounted world and backup paths
- server tuning values
- Packwiz URL
