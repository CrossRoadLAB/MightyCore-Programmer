# MIGHTYCORE-Programmer

![IMG_20210512_153515_Fotor](https://user-images.githubusercontent.com/83240004/125270656-2a130600-e30a-11eb-871e-02c9671d147f.png)

## GENERAL INFORMATION 

#### MIGHTYCORE Programmer is an open-source shield for Arduino Uno that facilitates the writing of the bootloader to the ATmega DIP-40 family ICs (MCU 8 bit). On the shield there is a socket for inserting the IC (40-pin Zif), a LED and a 16 MHz crystal oscillator. Despite its simplicity of construction, it greatly helps the production speed of microcontrollers. The supported ICs are:
- ATmega8535
- ATmega16
- ATmega32
- ATmega164
- ATmega324
- ATmega644
- ATmega1284

 ## HOW TO FLASH THE BOOTLOADER
 
 ![MightyCoreProgrammer_shield_installation](https://user-images.githubusercontent.com/83240004/125271219-cb01c100-e30a-11eb-8231-6478625f1577.png)

### PREREQUISITES

#### Install the MCUdude (MightyCore) libraries. For the detailed procedure click on the following link:
https://github.com/MCUdude/MightyCore#how-to-install

### PROCEDURE

- Upload sketch No. 11 in the examples section to the Arduino Uno;
- Select the desired card in Tools → Card → MightyCore;
- In Tools → Programmer, select “Arduino as ISP (MightyCore)”;
- Still in the Tools section, click on “Write the bootloader”;
- If the procedure is successful, the LED on the shield will start blinking.

![Blink](https://user-images.githubusercontent.com/83240004/125272058-b114ae00-e30b-11eb-875e-2cf8d6726aec.gif)

## SITE WHERE TO BUY PCB

If you are interested in buying the PCB you can consider supporting the project by purchasing it on:
https://www.pcbway.com/project/shareproject/MIGHTYCORE_Programmer.html
