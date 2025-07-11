## Infinix NOTE 40 5G (_X6852_)
## TWRP / OrangeFox device tree

## Device specifications

Device                  | Infinix NOTE 40 5G
-----------------------:|:-----------------------------------------
SoC                     | Mediatek Dimensity 7020 (6 nm)
CPU                     | Octa-core (2x2.2 GHz Cortex-A78 & 6x2.0 GHz Cortex-A55)
GPU                     | IMG BXM-8-256
Memory                  | 8/12 GB RAM
Storage                 | 256/512 GB (UFS 2.2)
MicroSD                 | microSDXC (dedicated slot)
Shipped Android Version | 14.0
Battery                 | Non-removable 5000 mAh
Display                 | 1080 x 2436 pixels (~393 ppi density), 6.78 inches
Camera                  | 108 MP (wide), 2 MP (Depth), 2 MP (Macro); 32 MP (front, wide)

## Device picture

![ Infinix NOTE 40 5G ](https://fdn2.gsmarena.com/vv/pics/infinix/infinix-note40-5g-2.jpg "Infinix NOTE 40 5G")

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [ ] USB OTG
- [ ] Vibrator

## Building

_Lunch_ command :

```
lunch twrp_X6852-eng && mka adbd vendorbootimage
```
