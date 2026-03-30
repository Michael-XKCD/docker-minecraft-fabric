# homelab-docker-minecraft-fabric

Reusable Docker Compose stack repo for the Minecraft Fabric server and its backup sidecars.

## Purpose

This repository contains the reusable runtime compose stack for the Minecraft Fabric
server, including hourly and daily backup containers. The homelab monorepo should
consume tagged releases from this repo and apply environment-specific networking,
Pangolin labels, and secrets.

The Packwiz content used by the server lives in this repo under `packwiz/` so the
stack source remains self-contained.

## Included

- `compose.yaml`
- `.env.example`
- validation workflow
- basic consumption notes

## Not Included

- real secrets
- host-specific Pangolin labels
- host-specific backup/data paths
