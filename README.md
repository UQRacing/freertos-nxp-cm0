# FreeRTOS for NXP Cortex-M0+ systems

Current FreeRTOS version used: 10.4.6

Last updated: 3 Feb 2022

Maintainer: Matt Young (m.young2@uqconnect.edu.au)

## Contents
- Base FreeRTOS image
    - Flattened headers and C files into one directory
- Cortex-M0 port
    - Source: FreeRTOS/Source/portable/GCC/ARM_CM0
- Config file suitable for Cortex-M0+ systems
- NXP specific stuff for thread-aware debug, [as detailed here](https://www.nxp.com/docs/en/quick-reference-guide/MCUXpresso_IDE_FreeRTOS_Debug_Guide.pdf)

## Licence
This is just a bundle of FreeRTOS, so it is released under the same licence as FreeRTOS itself, which is currently the MIT licence. See
LICENSE.txt for more details.
