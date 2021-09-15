# BLACK_F407VE_MBEDOS
 Target to BLACK-F407VE custom board in MbedOs
 
 This board is based in STM32F407VETx microcontroller
 
 <img src="https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/black_f407ve.jpg" width="340" height="460" />
 
 - Other documentation can be found in doc
   - [Schematic](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/STM32F407VET6_schematics.pdf)
   - [Datasheet](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/STM32F407VET6_datasheet.pdf)
   - [Left PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_left02.png)
   - [Right PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_right01.png)
   - [ST-Link/FSMC/NRF24/Serial1 PinOUT](https://github.com/marceloh220/BLACK_F407VE_MBEDOS/blob/main/doc/stm32f407vet6_st-link02_FSMC_NRF24_USART1.png)

How to use?
 - Drop the mbed-os folder to your program path.
 - Insert TARGET_BLACK_F407VE.json in your target.json or
 - Rename target.json.MRE to target.json and replace it with your (Caution, this will exclude other custom boards that you have add from selection in Mbed Studio)
