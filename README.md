# Sodium Leaf Culling — Unofficial 1.20.1 Fabric Backport

An unofficial Minecraft 1.20.1 Fabric backport of [Sodium Leaf Culling](https://github.com/txnimc/SodiumLeafCulling), originally created by Toni. This port adapts the leaf-rendering hook to Sodium 0.5.11 while preserving the upstream quality setting and surrounding-leaf checks.

This project is independent and is not affiliated with or endorsed by the upstream author.

## Requirements

- Minecraft 1.20.1
- Fabric Loader
- Fabric API
- Sodium 0.5.11 for Minecraft 1.20.1
- Indium 1.0.34 for Minecraft 1.20.1

## Build

Run `gradlew :1.20.1-fabric:build`. The backport source is in `src/main/java`; the `1.20.1-fabric` Stonecutter target selects the older Sodium API.

## Credits and license

The upstream project and its original author are credited above. This backport is distributed under the MIT License; see [`LICENSE.md`](LICENSE.md). The upstream repository remains unchanged.

AI disclosure: AI assistance was used to adapt the compatibility code for Sodium 0.5.11 and to prepare and validate this backport. The original project and author are credited above.
