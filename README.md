# 立创实战派 ESP32-S3 例程合集

本仓库收录了 14 个基于 **ESP-IDF (v5.x)** 的实战例程，适用于立创实战派 ESP32-S3 开发板。  
每个例程均可独立编译运行，用于快速掌握 ESP-IDF 的开发流程。

---

## 📂 例程目录

| 序号 | 例程名 | 功能简介 |
|------|--------|----------|
| 01 | boot_key | 按键启动与输入检测 |
| 02 | attitude | 姿态传感器（IMU）示例 |
| 03 | micro_sd | SD 卡读写与文件系统 |
| 04 | wifi_scan | 扫描 Wi-Fi 网络并输出列表 |
| 05 | wifi_connect | Wi-Fi STA 模式连接热点 |
| 06 | http_client | HTTP 客户端请求示例 |
| 07 | uart_debug | 串口通信与调试输出 |
| 08 | i2s_playback | 播放音频（I2S DAC 输出） |
| 09 | i2s_record | 麦克风音频采集 |
| 10 | lvgl_display | LVGL 图形界面显示 |
| 11 | touch_sensor | 电容触摸按键示例 |
| 12 | ble_server | 蓝牙 BLE 服务端示例 |
| 13 | audio_pipeline | 音频流处理框架 |
| 14 | ota_update | OTA 固件在线升级 |

---

## ⚙️ 使用方法

进入任意例程目录后执行：

```bash
idf.py set-target esp32s3
idf.py build flash monitor
