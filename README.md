# MKS SERVO57B
## Features
Based on the open project of nano_stepper by [Misfittech](https://github.com/Misfittech/nano_stepper)

To improve performance, Makerbase Team has made the following changes:
- Ported the project to STMicroelectronics' 32-bit MCU, STM32F103CBT6 ARM 32-bit Cortex™-M3 CPU Core,72 MHz maximum frequency,20k RAM. 128k Flash
- Changed the magnetic encoder to Allegro's A1333LLETR-T Contactless 0° to 360° angle sensor IC ,12bit
- Ported the compilation platform from arduino to PlatformIO —— Convenient  for STM32 MCU compilation
- Change the socket with motherboard, now it can work with much 3D printer motherboards using MKS SV_EXT V1.1 by Makerbase

## Firmware
  This project support build and upload by platformio, you can use Atom or Code editor (need install platformio) build it or upload  firmware. Please refer to the following method:
### How to Build
  Open platformio.ini file, set default_envs = mks_servo57b
  Other operations are the same as MKS SERVO42B(https://github.com/makerbase-mks/MKS-SERVO42B)  

## How to buy the MKS SERVO57B  
  https://www.aliexpress.com/item/4000165230349.html?spm=a2g0o.store_home.productList_8356959.pic_8
![MKS SERVO42B](https://github.com/makerbase-mks/MKS-SERVO57B/blob/master/Picture/SERVO57B.png "MKS SERVO57B")

## License
The hardware is under the Creative Commons Attribution Share-Alike 4.0 License as much of the work is based on Mechaduino project by J. Church.
 [https://github.com/jcchurch13/Mechaduino-Firmware](https://github.com/jcchurch13/Mechaduino-Firmware "https://github.com/jcchurch13/Mechaduino-Firmware"). 

The firmware is based on nano_stepper project by Misfittech：[https://github.com/Misfittech/nano_stepper](http:://github.com/Misfittech/nano_stepper "https://github.com/Misfittech/nano_stepper"), which is licensed as GPL V3 for non-commercial use. If you want to release a closed source version of this product, please contact MisfitTech.net for licensing details.
  

