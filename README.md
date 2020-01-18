Copyright (C) 2017 - The LineageOS Project

# Device Tree for Xiaomi Redmi 5 (rosy)

## Working
- [x] Bluetooth
- [x] Camera
- [x] Flashlight
- [x] FM Radio
- [x] GPS (All Modes)
- [x] Hotspot
- [x] Offline Charging
- [x] RIL
- [x] Sensors
- [x] Sound
- [x] VoLTE
- [x] Wifi

## Bugs:
None

## Device specifications

| Feature                 | Specification                           |
| :---------------------- | :---------------------------------------|
| CPU                     | Octa-core 1.8 GHz Cortex-A53            |
| Chipset                 | Qualcomm MSM8953 Snapdragon 625         |
| GPU                     | Adreno 506                              |
| Memory                  | 2/3/4 GB                                |
| Shipped Android Version | 7.1.1                                   |
| Storage                 | 16/32 GB                                |
| MicroSD                 | Up to 128 GB                            |
| Battery                 | 3300 mAh (non-removable)                |
| Dimensions              | 151.8 x 72.8 x 7.7 mm                   |
| Display                 | 1440x720 pixels, 5.7 (~282 PPI)         |
| Rear Camera             | 12 MP, LED flash                        |
| Front Camera            | 5 MP                                    |
| Fingerprint             | Rear-mounted                            |
| Sensors                 | Accelerometer, Gyro, Proximity, Compass |
| Release Date            | December 2017                           |

## Device Picture

![Redmi 5](https://i.imgur.com/Dx9SAeS.jpg "Redmi 5")

## Cloning
##### Shallow Clone
If you're just cloning it just for building, then use the following command to save bandwidth & space.

`git clone --single-branch --depth=1 https://github.com/LinuxPanda/android_device_xiaomi_rosy.git -b 9`

##### Full Clone
If you need the entire commit history, then the usual single branch clone command.

`git clone --single-branch https://github.com/LinuxPanda/android_device_xiaomi_rosy.git -b 9`
