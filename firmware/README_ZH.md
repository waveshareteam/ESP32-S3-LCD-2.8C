# ESP32-S3-LCD-2.8C 固件

[English](README.md)

| 固件 | 版本日期 | 烧录偏移 | 用途 |
| --- | --- | --- | --- |
| [ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin](ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin) | 2025-02-24 | `0x0` | 恢复 ESP32-S3-Touch-LCD-2.8C（触摸版）的出厂固件 |
| [ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin) | 2025-01-24 | `0x0` | 恢复 ESP32-S3-LCD-2.8C（无触摸版）的出厂固件 |

请根据板卡型号选择对应的合并 BIN，并仅执行对应的一条烧录命令。

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8C_FactoryOnly_20250224.bin
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8C_FactoryOnly_20250124.bin
```
