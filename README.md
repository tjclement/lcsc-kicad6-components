# LCSC component library for KiCad 6 (5.99 nightly)

- Kicad symbols and footprints for parts from lcsc.com
- Converted from LCSC's EasyEDA library, so you have a good chance that they match the part you buy from LCSC
- Symbols include datasheet links for later traceability
- Symbols point to LCSC footprint over a generic one (e.g. it will use LCSC's own QFP-144 footprint rather than KiCad's built-in)

Note: 3D models are also downloaded, but they need to be converted to .stp files at some point in the future before KiCad can use them.

## FAQ
* Why only support KiCad 6, when it's not a stable release yet?
  * The [easyeda2kicad](https://github.com/wokwi/easyeda2kicad) library that's used currently only supports v6, and since v6 is really nice to use, I didn't port the lib to v5.

## License
Choose from: MIT, Unlicense, or CC0. All are effectively public domain, so you can use this work however you like.

## Current component list
* STMicroelectronics STM32F750Z8T6 ([datasheet](https://datasheet.lcsc.com/szlcsc/2001071810_STMicroelectronics-STM32F750Z8T6_C411817.pdf))
* STMicroelectronics STM32F103CBT6 ([datasheet](https://datasheet.lcsc.com/szlcsc/1809301224_STMicroelectronics-STM32F103CBT6_C8304.pdf))
* Microchip Tech ATSAMD20E18A-MUT ([datasheet](https://datasheet.lcsc.com/szlcsc/2101221836_Microchip-Tech-ATSAMD20E18A-MUT_C614295.pdf))
* Texas Instruments MSP430FR6972IPMR ([datasheet](https://datasheet.lcsc.com/szlcsc/2001081132_Texas-Instruments-MSP430FR6972IPMR_C472489.pdf))
* Cirrus Logic WM8782SEDS/RV ([datasheet](https://datasheet.lcsc.com/szlcsc/1811081623_Cirrus-Logic-WM8782SEDS-RV_C323842.pdf))
