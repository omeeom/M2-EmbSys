## Block Diagram (Structural Diagram):

![DT](https://user-images.githubusercontent.com/80105220/154845541-461e7bb9-b259-494d-904b-7dabd4cc8a1a.jpg)


![image](https://user-images.githubusercontent.com/80105220/157075957-46db3600-c105-44d4-9cfe-a16236788b5c.png)

## Circuit Diagram (Behavioural Diagram):

![circuit diagram](https://user-images.githubusercontent.com/80105220/157038293-a15eed39-2ecf-4c6f-b70d-75a587f6f0f5.jpg)

## Digital Thermometer components:
## LCD (16x2)-Actuator
 * This display offers a way to interface your microcontroller to the outside world. It’s one of the main output devices  
   in your kit. In fact, it could be considered an `actuator`. This display is compatible with the ubiquitous HD44780 LCD controller. To be able to use it on the breadboard, you’ll need to solder the included 16 pins header strip to the display. It also needs a series resistor for the backlight, as well as a variable resistor to control its contrast.
*  LCD (Liquid Crystal Display) is widely used electronic display module and got a wide range of applications. 
*  A 16×2 LCD consists of 16 columns and 2 rows thereby it is capable of displaying 16 characters in a single line. 
*  It consists of two registers, Command register used to store the command instructions given to the LCD.
*  The operating voltage of this LCD is 4.7V-5.3V
*  It includes two rows where each row can produce 16-characters.
*  The utilization of current is 1mA with no backlight
*  Every character can be built with a 5×8 pixel box
*  The alphanumeric LCDs alphabets & numbers
*  Is display can work on two modes like 4-bit & 8-bit
*  These are obtainable in Blue & Green Backlight
*  It displays a few custom generated characters
## LM35-Sensor
* The LM35 is an integrated circuit sensor that can be used to measure temperature. 
*  It is a precision IC temperature sensor with its output proportional to the temperature (in oC). 
*  The sensor circuitry is sealed and therefore it is not subjected to oxidation and other processes.
*  With  LM35,  temperature  can be  measured  more  accurately  than  with  a thermistor. 
*  It  also  possess  low  self-heating  and  does  not  cause  more  than  0.1 deg C temperature rise in still air. 
*  The operating temperature range is from -55°C to 150°C. 
*  The output voltage varies by 10mV in response to every oC rise/fall in ambient temperature, i.e., its scale factor  
   is 0.01V/ oC. 

## AVR Microcontroller(ATmega32)
*  The full form of AVR is Alf-Egil Bogen Vegard Wollan RISC microcontroller. 
*  It’s used on Computing,Hardware in Worldwide. 
*  The AVR is a 8-bit RISC single chip microcontroller developed by Atmel. 
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
  capability.
  As inputs, these are pulled low if the pull-up resistors are used. It also provides various special functional features of the ATmega32.

* Port C (PC7-PC0): Port C is an 8-bit bidirectional I/O port. If the Joint Test Action Group (JTAG) interface is enabled, 
  the pull-up resistors on pins PC2 (TCK), PC3 (TMS),and PC5 (TDI) will be activated.
* Vcc: Digital voltage supply

* GND: Ground

* RESET: It is a RESET pin which is utilized to set the microcontroller ATmega32 to its primary value. During the beginning of an application the RESET pin is to be set elevated 
  for two machine rotations.

* XTAL1: It is an input for the inverting oscillator amplifier and input to an internal clock operating circuit.

* XTAL2: It is an output from an inverting oscillator amplifier.

* AVcc: It is a supply voltage pin for A/D converter and Port A. It must be connected with Vcc.

* AREF: AREF is an analog signal reference pin for the analog to digital converter.

## Interrupt Pins
Interrupt pins are the requirements of most of the circuits and it is increasing in number due to the rules of physics. The basic purpose of the interrupt pins is to get the attention of the CPU when every external device required. The controller requires an external pulse on specific pins and then the CPU will perform the programmed instructions by putting all other instructions at hold. In ATMega32 the number of interrupt pins is three. All these pins are useable without affecting each other. All interrupt pins within ATMega32 are: 
* INT0 
* INT1 
* INT2 
## Asynchronous Serial
ATMega32 supports multiple kinds of serial communication protocol and asynchronous serial communication is one of them. UART Communication is quite popular in most of the peripherals due to its simplicity and dependent on the programming. It communicates with two-pin, one for sending data and second for receiving it. In this microcontroller, there is a module for asynchronous serial communication which is given below: 
* RXD  
* TXD
## Synchronous serial
Asynchronous and Synchronous serial communication systems are mostly the same but in asynchronous the devices use the internal program for clock and in the synchronous and external clock input/output pins are required to keep the data sync between two devices. In ATMega32 there is a pin for external clock input/output during serial communication.
* XCK
## SPI
SPI protocol is also a popular serial communication due to its managing ability of different devices at a single time. It uses four wires, two for data and one for clock but the forth wire can be used in case of multiple devices. Whenever multiple devices need to operate with ATMega32 then only forth pin (SS) will be increased and the number of data and clock pin will be the same. ATMega support only four pins for single SPI communication device but in case of multiple devices Select Slave pin can be made through programming.
* SS’ 
* MOSI 
* MISO
* SCK 
## I2C
It is also a kind of serial communication but it is mostly used in those devices which requires only one-way communication most of the time. It is quite popular in most of the sensors, LCD, and motors too. I2C pins use one wire for data and second for the clock pulse, both these pins are given below:
* SCL 
* SDA 
## Analog to Digital Channel
There is a total of 8 analogs to digital channels that can be used as ADC. These all channels use a single 10-bit ADC which can be used by multiple channels at the same time. The channels are only in port A and all are listed below:
* ADC0
* ADC1 
* ADC2
* ADC3 
* ADC4 
* ADC5
* ADC6 
* ADC7 
## Timer Module Pins
In ATMega32 there is a total of three timers. The first two timers are 8-bits and the third timer is 16-bit. Timer0 and Timer1 can only operate with the external pulse, timer1 only operate within the microcontroller. All these timers can use internal and external oscillator, but they also can use the sperate oscillator. The sperate oscillator will be given through the specific pins. All these oscillator and timer pins are given below:
* T0 
* T1 
* TOSC1 
* TOSC2
## Capture/Compare/PWM
Some pins within the microcontroller can be used to generate the desired output signal. These pins capture the input signal and then compared it with the instructed signal and then it generates an event on the match. These pins are mostly used for PWM generation. All these pins in ATMega32 are:
* OC0 
* OC1B
* OC1A 
* OC2
