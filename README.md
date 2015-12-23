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

Following Objects are available after selection:
### CPU
- cpu_frequency
- load1
- load5
- load15
### Raspberry (vcgencmd is needed)
- cpu_voltage
- mem_arm
- mem_gpu
### Memory
- memory_available
- memory_free
- memory_total
### Network (eth0)
- net_received
- net_send
### SDCard
- sdcard_boot_total
- sdcard_boot_used
- sdcard_root_total
- sdcard_root_used
### Swap
- swap_total
- swap_used
### Temperature
- soc_temp
### Uptime
- uptime
### WLAN
- wifi_received
- wifi_send

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
