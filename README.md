# pira-smart-3.0-hardware

<img src="https://github.com/IRNAS/pira-smart-2.0-hardware/blob/development/4_DOC/irnas_logo.png" height="100">

PIRA Smart is a multifunctional device that can be used in any IoT project.

<img src="https://github.com/IRNAS/pira-smart-2.0-hardware/blob/development/4_DOC/PCB_top.png" height="250">

## Folder structure
 * folder 1_SCHEMATIC includes Altium schematic files and PDF schematic
 * folder 2_PCB includes Altium PCB file, PDF PCB print and PDF 3D PCB print
 * folder 3_OUTPUT_FILES includes Gerber and NC Drill files, PDF Assembly file and Bill of Material
 * folder 4_DOC includes 3D step model of PCB and photos of device
 * folder 5_ALTIUM_FILES incudes all Altium Designer files (Libraries, Output job, Project document, ...)
 * folder 6_RELEASE includes latest release version 2.1

## Specification

Device consists of:
 * Microcontroller module Murata Type ABZ - CMWX1ZZABZ:
   * Microcontroller STM (STM32L)
   * LoRa connectivity Semtech (SX1276)
 * BLE - RN4871
 * RTC - ISL1208IU8Z-T7A
 * EEPROM with EUI - 24AA02E48T-I/OT
 * LDO regulator - MCP1810T-30I/J8A
 * Boost converter - TPS630701RNMT
 * Battery charger - BQ24296RGET
 * RPi connector
 * GPIO header
 * Tag connect for programming TC2030

Dimensions:
 * Lenght: 65 mm
 * Height: 30 mm
 * PCB thickness: 1.6 mm

## Licensing

Pira Smart v3.0 hardware with documentation is licensed under [CERN OHL v.1.2. license](https://www.ohwr.org/licenses/cern-ohl/license_versions/v1.2).

What this means is that you can use this hardware and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

IRNAS is name and mark of Institute IRNAS Race. You may use these name and terms only to attribute the appropriate entity as required by the Open Licence referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.
 

