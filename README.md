# Modpacks

This repo contains modpacks, distributed using [packwiz](https://packwiz.infra.link/).

Each modpack is in its own directory, and contains:
- `README.md`: description of the modpack
- `package/`: packwiz contents of the modpack

packwiz commands should be run inside the relevant modpack's `package/` directory.

There is a pre-commit hook that auto-updates modpacks' packwiz metadata files when changes are made, in case manual edits were made.
