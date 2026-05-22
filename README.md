# Cheetahs-Creations-Cold-Chain-Monitor

# Universal Smart Cold-Chain Monitor (by Cheetahs Creations - Emily)

## Description
A universal, low-latency, "local-first" temperature monitoring solution designed for freezers, refrigerators, and high-stakes thermal environments. Unlike cloud-dependent sensors, this device integrates directly into local Home Assistant environments using open protocols, featuring "Rate-of-Change" intelligence to detect "door-ajar" events before total temperature failure.

## Key Features
* **Local-Only:** No cloud dependencies; communicates via Zigbee/Thread.
* **Smart Detection:** Firmware-level "delta" logic detects rapid temperature rises, not just fixed thresholds.
* **Hardware Ruggedized:** IP68-rated probe with ultra-thin cabling designed for freezer seals.
* **Open Source:** Hardware design and software configuration fully transparent.

## Roadmap
- [ ] Phase 1: Prototype assembly & sensor calibration.
- [ ] Phase 2: Firmware implementation (ESPHome/Zigbee).
- [ ] Phase 3: Field testing & "Rate-of-Change" logic tuning.
- [ ] Phase 4: Final documentation & Bill of Materials (BOM).

## Getting Involved
We welcome contributions, especially regarding firmware optimization or 3D-printable housing improvements. Please check the `CONTRIBUTING.md` file (to be added) or open an issue for feature requests.

## License
CERN Open Hardware Licence (CERN OHL) v1.2
