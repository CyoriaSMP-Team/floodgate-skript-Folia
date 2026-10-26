# floodgate-skript-Folia — CyoriaSMP Folia release provenance

- Original/source project: https://github.com/kejonaMC/floodgate-skript
- Original license: MIT. Upstream authorship and licensing are preserved.
- Tested target: Minecraft/Folia 1.21.11.
- Stage: **Folia compatibility-descriptor build**. Pre-release only, not certified region/thread safe.
- Binary: `floodgate-skript-2.3-CyoriaFolia.jar` (GitHub Releases asset; no worlds/config/secrets).

## What is actually modified
Binary diff against original only changed plugin.yml folia-supported marker/version. No scheduler implementation patch was found.

## Verification scope
Server startup verified; bedrock Skript syntax end-to-end interaction not established.

## Limitations
A Folia-supported descriptor by itself does NOT guarantee thread safety. Back up your data and test on a disposable world before deployment.

Source fork retains original project history. This document does not assert that a successful startup means fully Folia-compatible gameplay.
