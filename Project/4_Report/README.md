# CONTENTS
1.Aims and Objective]
2.components used
3.SWOT Analysis
4.4W's and 1H's
5.About the Project


## The main aim of this circuit is to main a constant temperature in the specified area

Abstract - In this project, we will build a small circuit to interface Arduino with DHT11 Temperature and Humidity Sensor. One of the main applications of connecting DTH11 sensor with Arduino is weather monitoring.
Also we can connect this to a fan, A.c depends upon the user's usage.

###### I. AIMS AND OBJECTIVE
The aim of this system is to implement in C#.net set of reliable techniques for maintaining constant Temperature .

###### Problem statement

Nowadays Half-cooked food business is growing in a very large-scale. This industry will be run untill they achieve a constant temperature in their storage areas.
Here they need constant temperature. Fluctuation of temperature may cause a very big loss to these Industries.
For solving this problem we are here with the solution.

## COMPONENTS USED
|S.NO|  COMPONENTS   |
|:----| ------------:|
|1|Arduino UNO|
|2|DHT11 Temperature and Humidity Sensor|  
|3|Power supply|  
|4|16 x 2 LCD Display|
|5|10K Ohm Potentiometer|  
|6|5K Ohm Resistor (1/4 W)| 

###### About the temperature sensor
DHT11 is a part of DHTXX series of Humidity sensors. The other sensor in this series is DHT22. Both these sensors are Relative Humidity (RH) Sensor. As a result, they will measure both the humidity and temperature. Although DHT11 Humidity Sensors are cheap and slow, they are very popular among hobbyists and beginners.

The DHT11 Humidity and Temperature Sensor consists of 3 main components. A resistive type humidity sensor, an NTC (negative temperature coefficient) thermistor (to measure the temperature) and an 8-bit microcontroller, which converts the analog signals from both the sensors and sends out single digital signal.
This digital signal can be read by any microcontroller or microprocessor for further analysis.

# SWOT ANALYSIS
## STRENGTH
     Affordable and very easy to installation and use
## WEAKNESS
     The improvements can be done in connecting with all the other devices for easy operation
## OPPORTUNITIES
    In industries where we need to maintain a constant temperature
## THREATS
     Faced problems while simulation

# 4 W'S AND 1'H
## WHO
   For the industries and companies used for mainting a constant temperature 
## WHAT
   A sensor which helps the people for maintaining the temperature
## WHEN
   When we needs to use
## WHERE
   In industries,factories
## HOW
   By using the DHT11 Humidity and Temperature Sensor

## About the project

We will see the circuit design of DHT11 interfacing with Arduino. The DHT11 Humidity and Temperature sensor comes in two variants: just the sensor or a module.

The main difference is that the module consists of the pull – up resistor and may also include a power on LED. We have used a module in this project and if you wish to use the sensor itself, you need to connect a 5K Ω pull – up resistor additionally.

Coming to the design, the data pin of the DHT11 Sensor is connected to the Pin 11 of Arduino. A 16 x 2 LCD display is used to display the results. The control pins of LCD i.e. RS and E (Pins 4 and 6 on LCD) are connected to pins 4 and 5 of Arduino. The data pins of LCD i.e. D4 to D7 (pins 11 to 14 on LCD) are connected to pins 0 to 3 on LCD.