# ESP32-S3-LCD-2.8C 固件

[English](README.md)

| 固件 | 版本日期 | 烧录偏移 | 用途 |
| --- | --- | --- | --- |
| [ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin) | 2025-01-24 | `0x0` | 恢复 ESP32-S3-LCD-2.8C 的出厂固件 |

使用 esptool 烧录合并 BIN。

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin
```
