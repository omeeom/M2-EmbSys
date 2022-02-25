# Digital Thermometer

Thermometers are the device we use to measure the temperature in any desired scale and we all will be quite familiar with the analog thermometers. There are some disadvantages in analog thermometers and this can be overcome by using digital thermometer.
The digital thermometer basically consists of a sensor that measures the change in resistance due to heat and converts this change in resistance to temperature.

## Block Diagram:

![DT](https://user-images.githubusercontent.com/80105220/154845541-461e7bb9-b259-494d-904b-7dabd4cc8a1a.jpg)


## High Level Requirement: 
------------|---------------------------------------------------
`Display`| It shall disply the measured temperature on display.
         |->Fahrenheit or Celsius display
         |->Max/min readings
`Accuracy`| Accuracy shall be high.
`Battery-powered`| Thermometer shall run on battery.
`Operating temperature`| It is the temperature range in which the device will be used.
## Low Level Requirement:
* buzzer: Switch or alarm signals are designed to alert the user when a reading 
  is finished, or when a temperature value has been reached.
* push switch: To start and stop the thermometer.
* led power light: To show that the thermometer is turned ON.
* Portability: It shall be pocket friendly.

## Digital Thermometer components:
* Battery: It is to provide the supply to the thermometer.

* Body: The body of the thermometer is made up of hard plastic.

* LCD (16x2): LCD (Liquid Crystal Display) is widely used electronic display  
  module and got a wide range of applications. 
  A 16×2 LCD consists of 16 columns and 2 rows thereby it is capable of displaying 16 characters in a single line. 
  It consists of two registers, Command register used to store the command instructions given to the LCD.

* LM35: LM35 is a Precision temperature sensor IC with its output proportional to 
  the temperature (in degree Celsius).
  It is capable of giving accurate temperature readings compared to thermistor. 
  The senor is sealed to avoid the effects of oxidation and other factors. 
  It operates at a temperature range of -55°c to 150°c.

* AVR Microcontroller:The full form of AVR is Alf-Egil Bogen Vegard Wollan RISC 
  microcontroller. It’s used on Computing,Hardware in Worldwide. 
  The AVR is a 8-bit RISC single chip microcontroller developed by Atmel. 

* Circuit: It consists of an ADC and a microcontroller along with some passive 
  components.


## Advantages of Digital Thermometers:
* Accuracy: The temperature reading doesn’t depend on scale reading and instead 
  shown directly on the display.Hence     
  temperature can be read exactly and accurately.

* Speed: Digital thermometers can reach a final temperature in 5 to 10 seconds 
  compared to conventional thermometers.

* Safety: Digital thermometers don’t use mercury, hence the hazards of the 
  mercury is eliminated in case the thermometer 
  breaks.

* Strong: The thermometer doesn’t need to be shaken for the proper mercury level, hence the risk of the tube getting 
  broken is eliminated.

## Applications of Digital Thermometer:
* Medical Applications: The digital thermometers are used to measure human body 
  temperature around 37⁰C. These 
  thermometers are mostly probe type or ear type. It measures oral and armpit body temperature.

* Marine Applications: Digital thermometers with a high-temperature exhaust gas 
  sensor as the temperature sensor can be   
  used in marine applications for measuring the local temperature.

* Industrial Applications: Digital thermometers are also used in power plants, 
  nuclear power plants, blast furnaces, 
  shipbuilding industries, etc. They can measure temperature from -220⁰C to +850⁰C.

* HVAC thermometers — rated for HVAC applications such as duct or flume 
  monitoring.

* Sanitary applications — Sanitary thermometers are rated for sanitary use such '
  as food or pharmaceutical applications.

* Home use — includes digital thermometers used for home health care, cooking, 
  and monitoring temperature on home 
  appliances such as the refrigerator or swimming pool.

* Laboratory — includes monitoring experiments and chemical reactions as well as 
  maintaining an optimal laboratory 
  environment.

* Food Service — uses thermometers in identifying completeness of cooking, and 
  sanitation of ingredients.

* Meteorological thermometers — give air, atmosphere and water temperature 
  readings.

## References:
  https://www.elprocus.com/digital-thermometers/
  
  https://atmega32-avr.com/digital-thermometer-using-avr-lm35-16x2-lcd/

  https://www.globalspec.com/learnmore/sensors_transducers_detectors/temperature_sensing/digital_thermometers
