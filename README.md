# Fastboot Images For Realme Devices

| Device | Region | Firmware Version | Link |
| :-: | :-: | :-: | :-: | 
| Realme 5 Pro | IN | A11 | [AFH](https://androidfilehost.com/?fid=4349826312261604056) |
| Realme Q | CN | A06 | [AFH](https://androidfilehost.com/?fid=1899786940962607920) |
| Realme XT | IN | A10 | [AFH](https://androidfilehost.com/?fid=1899786940962606272) |
| Realme X2 Pro | CN | A11 | [AFH](https://androidfilehost.com/?fid=4349826312261628809) |
| Realme X2 Pro | EU | A06 | [AFH](https://androidfilehost.com/?fid=4349826312261642076) |
| Realme X2 Pro | IN | A07 | [AFH](https://androidfilehost.com/?fid=4349826312261679551) |

If your device is not listed, please open a issue having your device name & region in label!

# Steps To Flash 
Download Latest Fastboot Files From Google

Open cmd in the fastboot folder

Boot device in fastboot mode

Use following commands to flash the images :

fastboot flash boot boot.img

fastboot flash system system.img

fastboot flash vbmeta vbmeta.img

fastboot flash vendor vendor.img


# Boot Partition Damaged Error After Root
Use the following command while in fastboot mode :

fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img

