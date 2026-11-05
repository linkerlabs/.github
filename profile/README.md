<div align="center">
  <img src="https://github.com/linkerlabs/.github/blob/main/profile/bannerAsset-2.png" alt="LinkerLabs Banner" width="100%">

  **Deterministic Hardware. Native Protocols. Zero Cloud.**

  *Open-source hardware adapters and local-first embedded firmware for appliance sovereignty.*

</div>

---

### Products

| Product | Focus | Target Platforms | Status |
| :--- | :--- | :--- | :---: |
| **OpenHVAC** | Local serial interface hardware & deterministic firmware for HVAC units | Mitsubishi (`CN105`), Daikin (`S21`), Panasonic, Hisense | `REV1.0 Active` |

---

### OpenHVAC Ecosystem

| Layer | Repository | Description | Stack |
| :--- | :--- | :--- | :--- |
| **Hardware** | [`openhvac-hardware`](https://github.com/linkerlabs/openhvac-hardware) | KiCad schematics, PCB layout, JLCPCB manufacturing files (Gerbers, BOM, CPL), and 3D enclosure models. Features wide-input buck regulation and level-shifted UART. | `KiCad` `FreeCAD` `SMT` |
| **Firmware** | [`openhvac-firmware`](https://github.com/linkerlabs/openhvac-firmware) | Native C/C++ ESP32 firmware running HVAC serial frame decoders, checksum routines, local MQTT telemetry, and NVRAM configuration. | `ESP-IDF` `C/C++` `MQTT` |
| **Integration** | [`ha-openhvac`](https://github.com/linkerlabs/ha-openhvac) | Native Home Assistant integration component exposing responsive `climate`, `sensor`, and diagnostic entities with instantaneous feedback. | `Python` `HACS` |

---

### Infrastructure & Assets

| Repository | Description | Scope |
| :--- | :--- | :--- |
| [`.github`](https://github.com/linkerlabs/.github) | Organization profile, community health files, and global workflow configurations. | Profile / Governance |
| [`branding`](https://github.com/linkerlabs/branding) | Master vector marks, color tokens, and 1-bit monochrome footprint modules for KiCad silkscreen and copper layers. | Assets / CAD Footprints |

---

<div align="center">
  <sub>LinkerLabs is an independent open-source hardware initiative. All brand names and trademarks belong to their respective owners and are referenced solely for technical interoperability.</sub>
</div>
