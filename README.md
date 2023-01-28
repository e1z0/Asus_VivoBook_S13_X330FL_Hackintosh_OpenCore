# Asus VivoBook S13 X330FL Hackintosh OpenCore

<img src="https://raw.githubusercontent.com/e1z0/Asus_VivoBook_S13_X330FL_Hackintosh_OpenCore/master/pics/IMG_7469.jpeg" width="400" title="Proof of Concept MacOS on VivoBook S13" />

```
Manufacturer: ASUSTeK COMPUTER INC.
Product Name: VivoBook S13 X330FL_S330FL
Version: X330FL
CPU Version: Intel(R) Core(TM) i7-8565U CPU @ 1.8GHz quad-core with Turbo Boost (up to 4.6GHz) and 8MB cache
Memory: 16GB LPDDR3 2133 MHz
Storage: 512GB NVMe SSD
```
[More information about this machine](https://www.asus.com/laptops/for-home/vivobook/vivobook-s13-s330/overview/tech-specs08/)


A lot of effort have been pushed to this, it works but it's not very 100% fine. It needs optimizations in startup times and power management. The battery is not efficient with this 
build. Everything else works except some small minor problems like fingerprint sensor not working. But for general usibility even SD Card reader now works, sleep works very well and 
have been extensively tested. It's small portable machine but for it's full portability it needs full power management with CPU frequency scaling... To make battery last longer, last 
time I've got only 1,5 hour of work done using only battery. Thats not very good comparing to the Windows, where it lasts over 4 hours.. I need rework this and implement method with 
VoltageShift.kext. It's possible but it will take some time to do it. But for now it works great and stable.

# Status

| Device                                                | Status                                         |
|-------------------------------------------------------|------------------------------------------------|
| :white_check_mark: VGA                                | Working native with hardware acceleration      |
| :white_check_mark: Video brightness control           | Working with keyboard controls                 |
| :white_check_mark: Multimedia keyboard keys           | Working                                        |
| :heavy_exclamation_mark: Keyboard backlight           | Working, but keyboard hotkey does not*1        |
| :white_check_mark: Audio                              | Working native AppleALC, HDMI audio works      |
| :white_check_mark: Microphone                         | Working                                        |    
| :white_check_mark: Wifi                               | Working                                        |
| :white_check_mark: Bluetooth                          | Working as Apple3rdparty                       |
| :white_check_mark: NVMe                               | Working                                        |
| :white_check_mark: Type-A USB 3.1 Gen 1               | Working                                        |
| :white_check_mark: USB 2.0                            | Working                                        |
| :white_check_mark: Sleep                              | Working                                        |
| :white_check_mark: MicroSD card reader                | Working                                        |
| :heavy_exclamation_mark: Combo audio jack             | Detecting plugged switch but no audio output*2 |
| :heavy_exclamation_mark: HDMI                         | Working, does not turn on after sleep*3        |
| :heavy_exclamation_mark: CPU & Full Power Management  | Not yet                                        |
| :heavy_exclamation_mark: Type-C™ USB 3.1 Gen 1        | Not tested                                        |
| :x: Fingerprint sensor                                | Will never work                                |
| :x: Dedicated graphics NVIDIA® GeForce® MX250         | Will never work                                |


* 1. The keyboard backlight can be controlled via macOS Control Center, however the keyboard control of it does not work.
* 2. Audio output from 3,5 jack is not working but when connected it's detected by macOS, however only some clanckling sound appears. Maybe it needs some AppleALC parameters or patches.
* 3. HDMI Is working correctly (sound also), however the issue comes when the laptop goes back from the sleep, it does not automatically on the monitor, the monitor itself needs to be turned off/on or hdmi unplugged/plugged to make the external display work.

# Private beta testing

**_If you want to participate in private beta version testing, please write me email to e1z0@icloud.com you will be provided with further information.._**


