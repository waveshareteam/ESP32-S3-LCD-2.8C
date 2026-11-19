# ESP32-S3-LCD-2.8C Firmware

[简体中文](README_ZH.md)

| Firmware | Version | Flash offset | Purpose |
| --- | --- | --- | --- |
| [ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin](ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin) | 2025-02-24 | `0x0` | Restore the factory firmware on the ESP32-S3-Touch-LCD-2.8C (touch model) |
| [ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin) | 2025-01-24 | `0x0` | Restore the factory firmware on the ESP32-S3-LCD-2.8C (non-touch model) |

Choose the merged BIN for your board model and run only the corresponding command.

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin
```
