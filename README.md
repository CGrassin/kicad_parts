# KiCad Parts Library

This repository contains Kicad symbols and footprints for various parts that do not exist in KiCad's default libraries. They were all tested and validated in http://charleslabs.fr projects.

To install the library, download this repository and extract it, open KiCad, "Preferences" > "Manage Symbols Library..." and add the path of **.lib** file in global libraries. Do the same thing with "Preferences" > "Manage Footprints Library...", selecting the **.Pretty** folder.

This is the full list of parts contained in this repository:
* **Arduino Pro Mini** board (chinese version)
* **MPU6050** gyroscope module
* **Micro SD Card** reader module
* **ADS1115** 16bits ADC module (regular and SDA/SCL swapped)
* **Mini360** DC-DC buck module
* **SX1308** DC-DC boost module
* **BMP280** atmospheric pressure sensor module
* **MQ-1/MQ-2/...** gas sensor
* **FM62429/M62429** electronic volume controller IC
* **Logic Level Shifter** module
* **RV097NS** potentiometer/switch combo
* **HM-11** bluetooth module (16 pins version)

**Warning:** there are often several non-pin-compatible versions of those modules. Please make sure that both the pinout and the physical footprint match yours.
