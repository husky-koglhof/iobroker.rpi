![Logo](admin/rpi-monitor.png)
ioBroker RPI-Monitor Adapter
==============

## Global Description
RPI-Monitor Implementation for Integration into ioBroker

## Important Information
Works only with node >= 0.12

## Installation
After Installation you have to setup all needed Modules within
Administration Site.

After start of iobroker.rpi, all selected modules generates
an object Tree within ioBroker within rpi.<instance>.<modulename>
e.g. rpi.0.cpu

Following Objects are available after selection:<br>
<br><b>CPU</b><br>
- cpu_frequency<br>
- load1<br>
- load5<br>
- load15<br>
<br><b>Raspberry (vcgencmd is needed)</b><br>
- cpu_voltage<br>
- mem_arm<br>
- mem_gpu<br>
<br><b>Memory</b><br>
- memory_available<br>
- memory_free<br>
- memory_total<br>
<br><b>Network (eth0)</b><br>
- net_received<br>
- net_send<br>
<br><b>SDCard</b><br>
- sdcard_boot_total<br>
- sdcard_boot_used<br>
- sdcard_root_total<br>
- sdcard_root_used<br>
<br><b>Swap</b><br>
- swap_total<br>
- swap_used<br>
<br><b>Temperature</b><br>
- soc_temp<br>
<br><b>Uptime</b><br>
- uptime<br>
<br><b>WLAN</b><br>
- wifi_received<br>
- wifi_send<br>

## Configuration
### Within Administration you can select following Modules
- CPU
- Raspberry
- Memory
- Network
- SDCard
- Swap
- Temperature
- Uptime
- WLAN

## Logfiles / Configuration Settings

## Features

## Todo

## Tested Hardware

## Changelog

### 0.0.1 (2015-12-23)
 - Initial commit. Alpha Version.

## License

Copyright (c) 2015 husky-koglhof <husky.koglhof@icloud.com>
