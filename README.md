# Asus VivoBook S13 X330FL Hackintosh OpenCore

<img src="https://raw.githubusercontent.com/e1z0/Asus_VivoBook_S13_X330FL_Hackintosh_OpenCore/master/pics/IMG_7469.jpeg" width="400" title="Proof of Concept MacOS on VivoBook S13" />

```
Manufacturer: ASUSTeK COMPUTER INC.
Product Name: VivoBook S13 X330FL_S330FL
Version: X330FL
CPU Version: Intel(R) Core(TM) i7-8565U CPU @ 1.8Ghz
```

A lot of effort have been pushed to this, it works but it's not very 100% fine. It needs optimizations in startup times and power management. The battery is not efficient with this 
build. Everything else works except some small minor problems like fingerprint sensor not working. But for general usibility even SD Card reader now works, sleep works very well and 
have been extensively tested. It's small portable machine but for it's full portability it needs full power management with CPU frequency scaling... To make battery last longer, last 
time I've got only 1,5 hour of work done using only battery. Thats not very good comparing to the Windows, where it lasts over 4 hours.. I need rework this and implement method with 
VoltageShift.kext. It's possible but it will take some time to do it. But for now it works great and stable.

# Status

| Device                   | Status                                  |
|--------------------------|-----------------------------------------|
| VGA :white_check_mark:   | Working native with hardware acceleration      |
| Video brightness control :white_check_mark: | Working with keyboard controls |
| Multimedia keyboard keys |  Working |
| Keyboard backlight :heavy_exclamation_mark: | Working, but keyboard hotkey does not |
| Audio :white_check_mark: | Working native AppleALC, HDMI not tested yet            |
| Wifi :white_check_mark:  | Working                                 |
| Bluetooth :white_check_mark:  | Working as Apple3rdparty |
| NVMe :white_check_mark:  | Working   |
| USB :white_check_mark:  | Working   |
| Sleep :white_check_mark:  | Working   |
| SD Card :white_check_mark:  | Working   |
| HDMI :heavy_exclamation_mark: | Not yet |
| CPU & Full Power Management :heavy_exclamation_mark: | Not yet |
| Fingerprint sensor :x:   |  will never work             |



# Private beta testing

**_If you want to participate in private beta version testing, please write me email to e1z0@icloud.com you will be provided with further information.._**


