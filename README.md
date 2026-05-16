# PVlowVoltage Firmware

Public ESPHome OTA firmware artifacts for PV low voltage controllers.

Firmware repository: https://github.com/cmariusz/PVlowVoltage_Firmware.git
Base URL: https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware

## Firmware

| Controller | Version | Chip | Manifest | Firmware | MD5 |
|---|---|---|---|---|---|
| Obniżanie napięcia PV - stałe fazy, Sofar | pv-low-voltage-a16 | ESP32 | [manifest](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-a16/manifest.json) | [firmware](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-a16/firmware.ota.bin) | `ea03bbc96dcf0474bb1625384714a013` |
| Obniżanie napięcia PV - stałe fazy | 2025.12.04_12h30 | ESP32 | [manifest](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-a6/manifest.json) | [firmware](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-a6/firmware.ota.bin) | `a470ff7c4a8ca79d3011347a04bda494` |
| Obniżanie napięcia PV - stałe fazy, Sofar | 2026.01.13_12h30 | ESP32-S3 | [manifest](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-b8m/manifest.json) | [firmware](https://raw.githubusercontent.com/cmariusz/PVlowVoltage_Firmware/main/firmware/pv-low-voltage-b8m/firmware.ota.bin) | `9a39ad1ee35a959ff4beab1f97ca6abe` |

## Release process

Run from the private ESPHome repository:

```powershell
.\scripts\prepare-firmware-update.ps1
.\scripts\prepare-firmware-update.ps1 -Compile -ReleaseNotes "Short change description"
```
