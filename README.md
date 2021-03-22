# Two Trees BlueR - 3D Printer

Documentation, firmware and set of utilities for my own use and personal needs.

<p align="left"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Printer%20Preview.jpg" width="50%" height="50%"></p>

## Specs
| Parameter | Value |
|--|--|
Number of nozzles|1|
Nozzle diameter|0.4mm|
Construction volume|235mm * 235mm * 280mm|
Printing accuracy|± 0.1~0.2mm|
Layer thickness|0.1~0.4mm|
printing method|SD card / online printing|
IHM|3.5 inch color touch screen|
Machine speed|10~300mm/s|
print speed|20~200mm/s|
Extrusion head temperature (highest)|260 °C|
Maximum hot bed temperature (highest)|100 °C|
Printing platform|Warm bed|
XY axis positioning accuracy|0.01mm|
Z axis positioning accuracy|0.004mm|
Recommended printed material|PLA, ABS and PETG|
Consumable diameter|1.75mm|
Print file format|Gcode|
Machine size|L=410mm * W=400mm * H=520mm|
Machine weight|7.5kg|
Power supply|127V~220V/240W|
Microcontroller|[STM32F103VET6 datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/2.%20Datasheets/MCU/STM32F103VET6.pdf)|
Motor Driver|[TMC2209 datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/2.%20Datasheets/Stepper%20Motor%20Driver/TMC2209.pdf)|
Stepper Motor|[US-17HS4401S datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Stepper%20Motors/US-17HS4401S.pdf)|
Motherboard|[MKS Robin Nano v1.2 schematic](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/1.%20Schematic/MKS%20Robin%20Nano%20v1.2.pdf) ([source HW + FW](https://github.com/makerbase-mks/MKS-Robin-Nano-V1.X))|
Display|MKS Robin TFT35(FSMC) (schematic not available)|
Firmware|[Marlin 3D Printer Firmware 2.0.x](https://github.com/MarlinFirmware/Marlin) (from bugfix-2.0.X in 3/21/2021) + [BlueR v3 Marlin Configurations](https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Two%20Trees/BlueR/BlueR%20V3) (from import-2.0.X in 3/21/2021) + Personal Customization|

More information on the manufacturer's website: https://www.twotrees3dprinter.com

## Print Samples

### Decoration Models
#### Among Us ([STL](https://www.thingiverse.com/thing:4626168))


![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Among%20Us%200.png) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Among%20Us%201.png)
--- | ---

#### Bulbasaur Planter ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Decoration/Bulbasaur%20Planter))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201103_212945.jpg" width="80%" height="80%"></p>


### Tools & Utensils
#### SD & Micro SD Card Box ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Tools%20%26%20Utensils/SD%20%26%20Micro%20SD%20Card%20Box))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201107_093354.jpg" width="80%" height="80%"></p>

#### 18650 Battery Box (x8) ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Tools%20%26%20Utensils/18650%20Battery%20Box%20(x8)))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201108_102735.jpg" width="80%" height="80%"></p>

#### Dust Filament Filter ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Tools%20%26%20Utensils/Dust%20Filament%20Filter))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103905.jpg" width="80%" height="80%"></p>

#### Universal Filament Clip ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Tools%20%26%20Utensils/Universal%20Filament%20Clip))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103758.jpg" width="80%" height="80%"></p>


### Calibration & Tests
#### XYZ Cube ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Calibration%20%26%20Tests/XYZ%20Cube))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103646.jpg" width="80%" height="80%"></p>

#### Temperature Tower ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Calibration%20%26%20Tests/Temperature%20Tower))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103409.jpg" width="80%" height="80%"></p>

#### Bed Level ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/Calibration%20%26%20Tests/Bed%20Level))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201112_212333.jpg" width="80%" height="80%"></p>


### BlueR Self-Upgrades Parts
#### BLTtouch Support (front mounting) ([STL](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/tree/master/3D%20Models/BlueR%20Self-Upgrades/BLTtouch%20Support%20(front%20mounting)/STL))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_123223.jpg" width="80%" height="80%"></p>

## Improved Components and Updates
- [x] Stepper Motor Driver - [TMC2209](https://br.banggood.com/5pcs-TMC2209-Stepper-Motor-Driver-Super-Silent-Stepsticks-Mute-Driver-Board-256-Microsteps-For-Sidewinder-3D-Printer-p-1585178.html?rmmds=myorder&cur_warehouse=CN) at X, Y, Z and E - **ultra-silent controllers**
- [x] Auto Leveling Sensor - [3D Touch](https://br.banggood.com/TWO-TREES-Touch-Auto-Leveling-Sensor-Auto-Bed-Leveling-Sensor-BLTouch-For-3D-Printers-p-1625266.html?rmmds=myorder&cur_warehouse=CN) - **Automatic and improved bed leveling**
- [x] Glass and mirror on the heated bed plate (Custom 235mm x 235mm x 3mm) - **better adhesion and flatness surface**
- [ ] Wireless Printer Monitor and Controller - [Raspberry](https://www.raspberrypi.org/) + [OctoPi](https://github.com/guysoft/OctoPi) + [OctoPrint](https://octoprint.org/) + [Sonoff](https://sonoff.tech/)
- [ ] Premium Ultra-Quiet Fan Cooler - [Noctua NF-A4x10 FLX](https://noctua.at/en/nf-a4x10-flx) + [DC-DC Buck Converter with LM2596](https://br.banggood.com/LM2596-DC-DC-Verstellbar-Step-Down-Schaltregler-Power-Supply-Module-p-88252.html?rmmds=search&cur_warehouse=CN)
- [ ] Z Axis Lead Screw Stabilizer - [Custom](https://www.thingiverse.com/thing:4656082) by [@jorgelousada](https://www.thingiverse.com/jorgelousada)
- [ ] Silicone cover for heated block - [MK8 Cover](https://www.aliexpress.com/item/33050074990.html?spm=a2g0o.detail.0.0.4574ac8c3xkbkY&gps-id=pcDetailBottomMoreThisSeller&scm=1007.13339.169870.0&scm_id=1007.13339.169870.0&scm-url=1007.13339.169870.0&pvid=c34b10de-e1c6-47de-9053-f818f89dd91a&_t=gps-id:pcDetailBottomMoreThisSeller,scm-url:1007.13339.169870.0,pvid:c34b10de-e1c6-47de-9053-f818f89dd91a,tpp_buckets:668%230%23131923%2330_668%23808%234094%23253_668%23888%233325%2312_668%234328%2319926%23211_668%232846%238116%23942_668%232717%237558%23186_668%231000022185%231000066058%230_668%233468%2315616%23763)


## Filament Brands Rated
### [Cliever](https://www.cliever.com/)   :star::star::star::star::star: 
- packaging without moisture protection
- excellent color diversity and good print quality

## Printer Details
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/1.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/2.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/3.jpg) |
|--|--|--|
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/4.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/5.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/6.jpg) |
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/7.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/8.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/10.jpg) |
