# BLACK_F407VE_MBEDOS
 Target to BLACK-F407VE custom board in MbedOs
 
 This board is based in STM32F407VETx microcontroller
 
 <img src="https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/black_f407ve.jpg" />
 
 Documentation:
   - [Schematic](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/STM32F407VET6_schematics.pdf)
   - [Datasheet](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/STM32F407VET6_datasheet.pdf)
   - [Left PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_left02.png)
   - [Right PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_right01.png)
   - [ST-Link/FSMC/NRF24/Serial1 PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_st-link02_FSMC_NRF24_USART1.png)

Why to Use? This custom board already have:
 - LSE oscillator enabled
 - CAN enabled
 - Pin mapping to keys and leds
 - Pin mapping to Display's backlight and touch PEN (INT)
 - Pin mapping to SPI's touch in display bus
 - Pin mapping to SPI's NRF24/Flash
 - Use console Serial1 default out
 - 
How to use?
 - Drop the mbed-os folder to your program path.
 - Insert [mbed-os/targets/TARGET_BLACK_F407VE.json](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/mbed-os/targets/TARGET_BLACK_F407VE.json) in your target.json
 - OR Rename [mbed-os/targets/target.json.MRE](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/mbed-os/targets/targets.json.MRE) to target.json and replace it with your
   - Caution, this will exclude other custom boards that you have add from selection in Mbed Studio
