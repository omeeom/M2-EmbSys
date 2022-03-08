#### Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements : High Level Requirement and Low Level Requirement.
`2_Architecture`   | Documents specifying design details including structural,Behavioural,Circuit and Pin Diagram also  
                     detailed component discription  .
`3_Implementation` | All codes including source code,make file and simulide file.
`4_Testplan`       | Documents with test plans and details.
`5_Output`         | Simulated output.
`6_Application`    | Application of Digital Thermometer.
`7_ImagesAndVideos`| Images and videos related to project.
`8_Report`         | All the details covered.
`9_References`     | Sites from where reference has been taken.

# Digital Thermometer

Thermometers are the device we use to measure the temperature in any desired scale and we all will be quite familiar with the analog thermometers. There are some disadvantages in analog thermometers and this can be overcome by using digital thermometer.
The digital thermometer basically consists of a sensor that measures the change in resistance due to heat and converts this change in resistance to temperature.

## Block Diagram:

![DT](https://user-images.githubusercontent.com/80105220/154845541-461e7bb9-b259-494d-904b-7dabd4cc8a1a.jpg)


## High Level Requirement: 
   ID     |  DESCRIPTION
----------|----------------------------------------------------------------
 `HLR_1.0`|`Display`: It shall disply the measured temperature on display.
 `HLR_1.1`|          ->Fahrenheit or Celsius display
 `HLR_1.2`|          ->Max/min readings
 `HLR_2.0`|`Accuracy`: Accuracy shall be high.
 `HLR_3.0`|`Battery-powered`: Thermometer shall run on battery.
 `HLR_4.0`|`Operating temperature`:It is the temperature range in which the device will be used.
## Low Level Requirement:
   ID     |  DESCRIPTION
 ---------|----------------------------------------------------------------------------------------------------------------------------
 `LLR_1.0`|`buzzer`: Switch or alarm signals are designed to alert the user when a reading is finished, or when a temperature value has been reached.
 `LLR_2.0`|`push switch`: To start and stop the thermometer.
 `LLR_3.0`|`led power light`: To show that the thermometer is turned ON.
 `LLR_4.0`|`Portability`: It shall be pocket friendly.

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

* `AVR Microcontroller`:The full form of AVR is Alf-Egil Bogen Vegard Wollan RISC 
  microcontroller. It’s used on Computing,Hardware in Worldwide. 
  The AVR is a 8-bit RISC single chip microcontroller developed by Atmel. 

* `Circuit`: It consists of an ADC and a microcontroller along with some passive 
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
  
  https://microcontrollerslab.com/atmega32-microcontroller-pinout-programming-tutorials-features/
