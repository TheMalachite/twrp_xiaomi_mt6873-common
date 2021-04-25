Device Tree for Redmi 10X (atom)
==========================================

The Redmi 10X (codenamed _"atom"_) is a high-end, mid-range smartphone from Xiaomi.
It was released in June 2020.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Dimensity 820 5G                                                                                                      |
| GPU                     | Mali-G57 MC5                                                                                                                   |
| Memory                  | 6/8 GB RAM                                                                                                                     |
| Shipped Android Version | 10.0                                                                                                                           |
| Storage                 | 64/128/256 GB                                                                                                                  |
| Battery                 | Non-removable Li-Po 4520 mAh battery                                                                                           |
| Display                 | 1080 x 2400 pixels, 20:9 ratio (~401 ppi density)                                                                              |
| Camera (Back)(Main)     | 48 MP, f/1.8, 26mm (wide), 1/2.0", 0.8µm, PDAF                                                                                 |
| Camera (Front)          | 16 MP, f/2.3, (wide), 1/3.06", 1.0µm                                                                                           |

## Device picture
![atom](https://cdn-files.kimovil.com/default/0004/71/thumb_370771_default_big.jpeg)

## Build instructions

```
# Compiling
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_atom-eng
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```
## Kernel source

You can find the kernel source used in this tree at [MiCode/Xiaomi_Kernel_OpenSource](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/bomb-q-oss)

**Copyright 2021 The TWRP Open Source Project**
