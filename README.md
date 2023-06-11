# Hackintosh EFI for Lenovo IdeaPad 320-15IKB (81BG)
Goal of this repo is to run Mac os (and Windows dual) on Lenovo Ideapad 320-15IKB Laptop

<img src="/Screen Shot 2023-06-02 at 21.31.35.png">

## About this Laptop

### Hardware Status

Type | Spec | Status | Solution
---------|:---------|:----------:|----------
Computer		| Lenovo Ideapad 320-15IBK 81GB   | :white_check_mark: |
BIOS Version	| LENOVO 6JCN33WW | :white_check_mark: |
CPU				| Intel Core i5-8250U (Kaby Lake R) | :white_check_mark: | 
Graphics		| Intel® UHD Graphics 620 | :white_check_mark: |
Audio			| Realtek ALC230 (audio layout 13) | :white_check_mark: |
Ethernet		| RTL8111/8168/8411 | :white_check_mark: |
WiFi			| Realtek RTL8821CE | :x: | Replace with Intel card (NGFF)
Bluetooth		| Realtek | :x: | Intel card also fix (NGFF)
Touchpad		| ELAN | :x: | Use USB Mouse
Keyboard		| HID | Working |
Battery		|   ? | Working |

### :white_check_mark: Working
- [x] CPU power management.
- [x] Graphics acceleration and Brightness.
- [x] Battery status.
- [x] Keyboard.
- [x] Wi-Fi.
- [x] Bluetooth.
- [x] USB ports.
- [x] Ethernet.
- [x] Audio (Internal speakers, 3.5mm headphone jack).
- [x] Internal microphone.
- [x] VGA WebCam.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.
- [x] Sleep/Hibernate

### :x: No working
- [ ] Trackpad.
- [ ] HDMI video & audio output.
- [ ] AirDrop & Handoff.
- [ ] Battery drains.


## BIOS setup required

- Configuration / Sata Controlller Mode: AHCI
- Security / Intel Platform Trust Technology: Disabled
- Security / Intel SGX: Disabled
- Security / Secure Boot: Disabled
- Boot / Boot Mode: UEFI

## Compatible
- [x] MacOS 12 Monterey
- [x] MacOS 13 Ventura
- [x] OpenCore 0.9.2



