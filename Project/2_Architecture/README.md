## Block Diagram:

![DT](https://user-images.githubusercontent.com/80105220/154845541-461e7bb9-b259-494d-904b-7dabd4cc8a1a.jpg)

## Circuit Diagram:

![circuit diagram](https://user-images.githubusercontent.com/80105220/157038293-a15eed39-2ecf-4c6f-b70d-75a587f6f0f5.jpg)

## Digital Thermometer components:
* `Battery`: It is to provide the supply to the thermometer.

* `LCD (16x2)`: LCD (Liquid Crystal Display) is widely used electronic display  
  module and got a wide range of applications. 
  A 16×2 LCD consists of 16 columns and 2 rows thereby it is capable of displaying 16 characters in a single line. 
  It consists of two registers, Command register used to store the command instructions given to the LCD.

* `LM35`: The LM35 is an integrated circuit sensor that can be used to measure temperature. 
  It is a precision IC temperature sensor with its output proportional to the temperature (in oC). 
  The sensor circuitry is sealed and therefore it is not subjected to oxidation and other processes.
  With  LM35,  temperature  can be  measured  more  accurately  than  with  a thermistor. 
  It  also  possess  low  self-heating  and  does  not  cause  more  than  0.1 deg C temperature rise in still air. 
  The operating temperature range is from -55°C to 150°C. 
  The output voltage varies by 10mV in response to every oC rise/fall in ambient temperature, i.e., its scale factor is 0.01V/ oC. 

* `AVR Microcontroller(ATmega32)`:The full form of AVR is Alf-Egil Bogen Vegard Wollan RISC 
  microcontroller. It’s used on Computing,Hardware in Worldwide. 
  The AVR is a 8-bit RISC single chip microcontroller developed by Atmel. 

* `Circuit`: It consists of an ADC and a microcontroller along with some passive 
  components.
  
## ATmega32AVR
*  The full form of AVR is Alf-Egil Bogen Vegard Wollan RISC microcontroller.   
*  2 Kilo bytes of internal Static RAM
*  32 X 8 general working purpose registers
*  32 Kilo bytes of in system self programmable flash program memory.
*  1024 bytes EEPROM
*  Programmable serial USART
*  8 Channel, 10 bit ADC
*  One 16-bit timer/counter with separate prescaler, compare mode and capture mode.
*  Available in 40 pin DIP, 44-pad QFN/MLF and 44-lead QTFP
*  Two 8-bit timers/counters with separate prescalers and compare modes
*  32 programmable I/O lines
*  In system programming by on-chip boot program
*  Master/slave SPI serial interface
*  4 PWM channels
*  Programmable watch dog timer with separate on-chip oscillator
## ATmega32 Microcontroller Pin Diagram
![image](https://user-images.githubusercontent.com/80105220/157039786-10214da8-bf9c-4d08-bc99-c578f22a20ba.png)

## Pin Descriptions:
* Port A (PA7-PA0): Port A serves as analog inputs for A/D converter. It also acts as an 8-bit bidirectional I/O port if the A/D converter is not used internally.

* Port B (PB7-PB0) and Port D (PD7-PD0): These ports are 8-bit bidirectional I/O ports. Their output buffers have symmetrical drive characteristics with high source and sink  
  capability. As inputs, these are pulled low if the pull-up resistors are used. It also provides various special functional features of the ATmega32.

* Port C (PC7-PC0): Port C is an 8-bit bidirectional I/O port. If the Joint Test Action Group (JTAG) interface is enabled, the pull-up resistors on pins PC2 (TCK), PC3 (TMS),  
  and PC5 (TDI) will be activated.
* Vcc: Digital voltage supply

* GND: Ground

* RESET: It is a RESET pin which is utilized to set the microcontroller ATmega32 to its primary value. During the beginning of an application the RESET pin is to be set elevated 
  for two machine rotations.

* XTAL1: It is an input for the inverting oscillator amplifier and input to an internal clock operating circuit.

* XTAL2: It is an output from an inverting oscillator amplifier.

* AVcc: It is a supply voltage pin for A/D converter and Port A. It must be connected with Vcc.

* AREF: AREF is an analog signal reference pin for the analog to digital converter.
