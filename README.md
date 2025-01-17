# Two Trees BlueR - 3D Printer

Documentation, firmware and set of utilities for my own use and personal needs.

<p align="left"><img src="Assets/Printer%20Preview.jpg" width="50%" height="50%"></p>

## Machine Specs
| Parameter | Value |
|--|--|
Number of nozzles|1|
Construction volume|235mm * 235mm * 280mm|
Printing method|SD-Card / online printing (by Serial UART communication through printer USB connector and some internet interface)|
IHM|3.5 inch color touch screen|
Machine speed|10~300mm/s|
Print speed|20~200mm/s|
Extrusion head temperature (highest)|260 °C|
Maximum hot bed temperature (highest)|100 °C|
Printing platform|Warm bed|
XY axis positioning accuracy|0.01mm|
Z axis positioning accuracy|0.004mm|
Recommended printed material|PLA, ABS and PETG|
Consumable filament diameter|1.75mm|
Print file format|G-Code|
Machine size|L=410mm * W=400mm * H=520mm|
Machine weight|7.5kg|
Power supply|127V~220V/240W|
Microcontroller|[STM32F103VET6 datasheet](Hardware/Motherboard/2.%20Datasheets/MCU/STM32F103VET6.pdf)|
Motor Driver|[TMC2209 datasheet](Hardware/Motherboard/2.%20Datasheets/Stepper%20Motor%20Driver/TMC2209.pdf)|
Stepper Motor|[US-17HS4401S datasheet](Hardware/Stepper%20Motors/US-17HS4401S.pdf)|
Motherboard|[MKS Robin Nano v1.2 schematic](Hardware/Motherboard/1.%20Schematic/MKS%20Robin%20Nano%20v1.2.pdf) ([source HW + FW](https://github.com/import-tiago-mks/MKS-Robin-Nano-V1.X))|
Display|[MKS TFT35](https://github.com/import-tiago-mks/MKS-TFT) - Parallel line communication interface (FSMC) (schematic not available)|

More information on the manufacturer's official website: https://twotrees3d.com/

## Firmware
Version|[Marlin 3D Printer Firmware](https://github.com/MarlinFirmware/Marlin/releases/tag/2.1.3-b1) (from release 2.1.3-b1) + [BlueR v3 Marlin Configurations](https://github.com/MarlinFirmware/Configurations/tree/release-2.1.3-b1/config/examples/Two%20Trees/BlueR/BlueR%20V3) (from release 2.1.3-b1) + Personal Customization|
--- | ---
<p align="center"><img src="Assets/firmware-compile.png" width="70%" height="70%"></p> 


## Frequently Asked Questions

### What is my micro-stepping configuration?

<p align="center"><img src="Assets/MicrosteppingDetails.png" width="100%" height="100%"></p>
<p align="center"><img src="Assets/MicrosteppingJumpers.png" width="70%" height="70%"></p>
   

### What VREF value I seted at motor-drivers (aka motors current definition)?

- X-axis VREF = 0.75V ∴ IRMS = 0.53A </br>
- Y-axis VREF = 0.85V ∴ IRMS = 0.60A </br>
- Z-axis VREF = 0.85V ∴ IRMS = 0.60A </br>
- E-axis VREF = 0.75V ∴ IRMS = 0.53A </br>

<p align="center"><img src="Assets/IRMS_formula.png"</p>    
<p align="center"><img src="Assets/TMCVref.jpg" width="50%" height="50%"></p>
  
| ![](Assets/VREF_X.png) | ![](Assets/VREF_Y.png) | ![](Assets/VREF_Z.png) | ![](Assets/VREF_E.png) |
|--|--|--|--|


## Print Samples

### Decoration Models
#### Among Us ([STL](https://www.thingiverse.com/thing:4626168))


![](Assets/Among%20Us%200.png) | ![](Assets/Among%20Us%201.png)
--- | ---

#### Bulbasaur Planter ([STL](https://www.thingiverse.com/thing:633081))
<p align="center"><img src="Assets/IMG_20201103_212945.jpg" width="80%" height="80%"></p>


### Tools & Utensils
#### SD & Micro SD Card Box ([STL](https://www.thingiverse.com/thing:3611322))
<p align="center"><img src="Assets/IMG_20201107_093354.jpg" width="80%" height="80%"></p>

#### 18650 Battery Box (x8) ([STL](https://www.thingiverse.com/thing:3191180))
<p align="center"><img src="Assets/IMG_20201108_102735.jpg" width="80%" height="80%"></p>

#### Dust Filament Filter ([STL](https://www.thingiverse.com/thing:1692395))
<p align="center"><img src="Assets/IMG_20201114_103905.jpg" width="80%" height="80%"></p>

#### Universal Filament Clip ([STL](https://www.thingiverse.com/thing:3757356))
<p align="center"><img src="Assets/IMG_20201114_103758.jpg" width="80%" height="80%"></p>


### Calibration & Tests
#### XYZ Cube ([STL](https://www.thingiverse.com/thing:1278865))
<p align="center"><img src="Assets/IMG_20201114_103646.jpg" width="100%" height="100%"></p>


### BlueR Self-Upgrades Parts
#### BLTtouch Support (front mounting) ([STL](https://moltech3d.com/blog/2020/10/05/suporte-para-fixacao-do-bltouch-na-impressora-twotrees-bluer/))
<p align="center"><img src="Assets/IMG_20201114_123223.jpg" width="80%" height="80%"></p>

## Improved Components and Upgrades
- [x] Stepper motor driver - [TMC2209](https://pt.aliexpress.com/item/1005004894012542.html?spm=a2g0o.productlist.main.1.8b1a3094f3ilw9&algo_pvid=60c85c97-1763-409c-a219-69ed684f337f&algo_exp_id=60c85c97-1763-409c-a219-69ed684f337f-0&pdp_npi=3%40dis%21BRL%2162.49%2155.61%21%21%21%21%21%40210217c716815801065208639d0750%2112000030924511198%21sea%21BR%212057087985&curPageLogUid=Iu7Dh05cteNe) at X, Y, Z and E - **ultra-silent controllers**
- [x] Auto leveling sensor - [3D Touch](https://pt.aliexpress.com/item/1005004256711867.html?spm=a2g0o.productlist.main.1.49e469f4PgU8Lp&algo_pvid=3bd698ac-774d-458f-9fc5-778463a89a93&algo_exp_id=3bd698ac-774d-458f-9fc5-778463a89a93-0&pdp_npi=3%40dis%21BRL%2196.58%2158.92%21%21%21%21%21%4021227e5116815802204888198d070b%2112000028559162278%21sea%21BR%212057087985&curPageLogUid=k1XbKoGe0mXJ) - **Automatic and improved bed leveling**
- [x] PEI spring steel sheet with magnetic base [235mm x 235mm](https://www.aliexpress.com/item/1005004111663711.html?spm=a2g0o.productlist.main.11.23e26290BBybOu&algo_pvid=d9085f1c-9384-4d4b-a717-6a7b56e6481d&algo_exp_id=d9085f1c-9384-4d4b-a717-6a7b56e6481d-5&pdp_ext_f=%7B%22sku_id%22%3A%2212000029713002839%22%7D&pdp_npi=3%40dis%21BRL%21333.87%21166.91%21%21%21%21%21%40212248ba16768089154476925d071a%2112000029713002839%21sea%21BR%212057087985&curPageLogUid=6puS8CKqDljH) - **better adhesion and increase surface hardness**
- [x] Anti-backlash spring loaded nut - [T8](https://pt.aliexpress.com/item/32820989850.html?spm=a2g0o.cart.0.0.4d623c00aKJcGs&mp=1) - **Smooths lines on the z axis**

## Printer Details
| ![](Assets/1.jpg) | ![](Assets/2.jpg) | ![](Assets/3.jpg) |
|--|--|--|
| ![](Assets/4.jpg) | ![](Assets/5.jpg) | ![](Assets/6.jpg) |
| ![](Assets/7.jpg) | ![](Assets/8.jpg) | ![](Assets/10.jpg) |
