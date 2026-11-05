# LinkerLabs

We build open-source hardware adapters, protocol bridges, and local-first firmware to integrate proprietary appliances into modern smart home ecosystems without vendor clouds.

---

### Active Focus: OpenHVAC

Most modern mini-split and heat pump systems rely on unreliable vendor clouds, slow mobile apps, or expensive closed dongles. **OpenHVAC** provides an open-source, hardware-level interface that taps directly into native indoor unit serial ports (CN105, S21, UART) for direct, deterministic local control.

* **Hardware (`openhvac-hardware`):** Compact, opto-isolated/level-shifted adapter boards with integrated wide-input buck regulation designed to run reliably off internal board power.
* **Firmware (`openhvac-firmware`):** Native C/C++ ESP32 firmware supporting local Home Assistant integration, local REST/MQTT, and continuous telemetry feedback.
* **Home Assistant Component (`ha-openhvac`):** Turnkey HACS climate entity integration with full mode, fan, vane, and setpoint controls.

---

### Repositories

| Repository | Scope | Status |
| :--- | :--- | :--- |
| [openhvac-hardware](https://github.com/linkerlabs/openhvac-hardware) | KiCad schematics, PCB layout, gerbers, and 3D enclosure models | Active / REV1 |
| [openhvac-firmware](https://github.com/linkerlabs/openhvac-firmware) | ESP32 core firmware, protocol drivers, and configuration tools | Active |
| [ha-openhvac](https://github.com/linkerlabs/ha-openhvac) | Native Home Assistant integration component | In Development |
| [branding](https://github.com/linkerlabs/branding) | Vector marks, KiCad silkscreen footprints, and color palettes | Maintained |

---

### Principles

* **100% Local:** No external API keys, subscription models, or telemetry pings.
* **Hardware Robustness:** Designed to survive dirty 12V/5V rails, transient noise, and tight indoor unit cavities.
* **True Open Source:** Permissive licensing across schematics, gerbers, and source code.
