# ARM-Debugger
restore the Bootloader on bricked ARM MCUs ore flash a precompiled firmware

* small formfactor
* load firmware per sd- card
* easy usage
* based on DAP- library

## Version A usage
Load a precompiled .bin file to the sd card. This file must be named as "fw.bin".
Connect the SD card and Target with the unbricker. Plug the Unbricker in an USB port, the green led will light up.
Push the Button, the orange led will light up.
After verifying, the green led blinks. flashing the target is done.

If the red led lights up, check your sd- card wiring, the name of the firmware file and if the target controller is supported.

*Info: to burn the firmware on the debugger, a SWD- Programmer like an ATMEL ICE 3 is required*

### Project Log
* 1st Mockup done

## Supported ARM MCUs
**ATMEL / Microchip**
* SAM D09D14A
* SAM D09C13A
* SAM D10D14AM
* SAM D11D14A
* SAM D11D14AM
* SAM D11D14AS
* SAM D11C14A
* SAM D20E15A
* SAM D20E18A
* SAM D20J18A
* SAM D21J18A
* SAM D21E15A
* SAM D21E18A
* SAM D21G18A
* SAMD51P20A
* SAMD51P19A
* SAMD51N20A
* SAMD51N19A
* SAMD51J20A
* SAMD51J19A
* SAMD51J18A
* SAMD51G19A
* SAMD51G18A
* SAME51J19A

* SAM R21G18
* SAM R30G18A
* SAM R30E18A

* SAM C21J18A

* SAM L21E18B
* SAM L21J18A
* SAM L21J18B

**Texas Instruments**
* STM32F405xx
* STM32F407xx
* STM32F415xx
* STM32F417xx
* STM32F42xxx
* STM32F43xxx
* STM32F411xC
* STM32F411xE
* STM32F412

**Nordic Semiconductor**
* nRF51422
* nRF51822
* nRF52832  
* nRF52833
* nRF52840
