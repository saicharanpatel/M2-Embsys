## Working and output
simple project is built using Arduino UNO and DHT11 Humidity and Temperature Sensor, where the Humidity and Temperature of the surroundings are displayed on an LCD display.

After making the connections, we need not do anything as the program will take care of everything. Although there is a special library for the DHT11 module called “DHT”, we didn’t use it. If you want to use this library, you need to download this library separately and add it to the existing libraries of Arduino.

The program written is based on the data timing diagrams provided in the datasheet. The program will make the Arduino to automatically read the data from the sensor and display it as Humidity and Temperature on the LCD Display. 