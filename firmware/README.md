# ESP32-S3-LCD-2.8C Firmware

[简体中文](README_ZH.md)

| Firmware | Version | Flash offset | Purpose |
| --- | --- | --- | --- |
| [ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin) | 2025-01-24 | `0x0` | Restore the factory firmware on the ESP32-S3-LCD-2.8C |

Flash the merged BIN with esptool.

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin
```
