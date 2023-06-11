# Hackintosh EFI for Lenovo IdeaPad 320-15IKB (81BG)
Goal of this repo is to run Mac os (and Windows dual) on Lenovo Ideapad 320-15IKB Laptop

<img src="/Screen Shot 2023-06-02 at 21.31.35.png">

## About this Laptop

### Hardware Status

Type | Spec | Status | Solution
---------|:---------:|----------:|----------
Computer		| Lenovo Ideapad 320-15IBK 81GB   | :white_check_mark: |
BIOS Version	| LENOVO 6JCN33WW | :white_check_mark: |
CPU				| Intel Core i5-8250U @ 1.60GHz | :white_check_mark: | 
Graphics		| Intel® UHD Graphics 620 | :white_check_mark: |
Audio			| Realtek ALC230 (audio layout 13) | :white_check_mark: |
Ethernet		| RTL8111/8168/8411 | :white_check_mark: |
WiFi			| Realtek RTL8821CE | :x: |
Bluetooth		| Realtek | :x: |
Touchpad		| ELAN | :x: |
Keyboard		| HID | Working |
Battery		|   ? | Working |

:white_check_mark:

## Software Status

Type | Spec | Status
---------|:---------:|:----------:
Battery Status		| - | Working
Brightness		| - | Working
Sleep/Hibernate		| - | ~~Weird issue~~ [Working](https://www.tonymacx86.com/threads/hackintosh-lags-after-wake-from-sleep.276096/)!
Trackpad		| - | Weird issue

## Modifications

Type | Spec | Status
---------|:---------:|----------
ADATA SU800 512GB		| - | Working
Xiaomi Mi Wireless Mouse		| - | Working
Logitech K540 Wireless Keyboard		| - | Working


## Kext Used

Kext | Link | Status
---------|:---------:|----------
AppleALC.kext | - | Working
HoRNDIS | [Install](https://github.com/jwise/horndis) | Working
Lilu.kext | - | Working
RealtekRTL8111.kext | - | Working
SMCBatteryManager.kext | - | Working
SMCProcessor.kext | - | Working
SMCSuperIO.kext | - | Working
VirtualSMC.kext | - | Working
VoodooI2C.kext  | - | Working
VoodooI2CHID.kext  | - | Working
VoodooPS2Controller.kext  | - | Working
VoodooTSCSync.kext  | - | Working
WhateverGreen.kext | - | Working



