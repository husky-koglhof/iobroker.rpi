![Logo](admin/rpi-monitor.png)
ioBroker RPI-Monitor Adapter
==============

RPI-Monitor implementation for integration into ioBroker

## Important Information
Works only with node >= 0.12

## Installation
After installation you have to configure all required modules via administration page.

After start of iobroker.rpi, all selected modules generates
an object tree in ioBroker within rpi.<instance>.<modulename>
e.g. rpi.0.cpu

Following Objects are available after selection:

#### **CPU**

- cpu_frequency
- load1
- load5
- load15

#### **Raspberry (vcgencmd is required)**

- cpu_voltage
- mem_arm
- mem_gpu

#### **Memory**

- memory_available
- memory_free
- memory_total

#### **Network (eth0)**
- net_received
- net_send

#### **SDCard**
- sdcard_boot_total
- sdcard_boot_used
- sdcard_root_total
- sdcard_root_used

#### **Swap**
- swap_total
- swap_used

#### **Temperature**
- soc_temp

#### **Uptime**
- uptime

#### **WLAN**
- wifi_received
- wifi_send

## Configuration
On configuration page you can select following modules:

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
 - Odroid C1
 - Raspberry Pi 1

## Changelog

### 0.0.3 (2015-12-28)
 - (husky-koglhof) Fixed value calc.
   Set Value to 2 digits
   
### 0.0.2 (2015-12-26)
 - (husky-koglhof) Workaround for node 0.10.x
 - (bluefox) Some Fixes
 
### 0.0.1 (2015-12-23)
 - Initial commit. Alpha Version.

## License

Copyright (c) 2015 husky-koglhof <husky.koglhof@icloud.com>

MIT License
