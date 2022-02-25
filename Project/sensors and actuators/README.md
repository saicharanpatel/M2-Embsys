## SENSORS Used:
###### Fingerprint sensor:
Biometric module used here is R305 series finger print module. It supports USART communication protocol. 
Here, USART protocol is used for communicating with the micro controller. USART is universal synchronous and asynchronous receiver and transmitter. This module has four pins out 1) Transmit, 2) Receive, 3) Vin, 4) GND. Transmit pin is connected to the receive pin of the microcontroller. Receive pin should be connected to the transmit pin of the microcontroller. Vin is applied with a voltage of 5V and GND is connected to ground. Data can be transmitted or received using serial communication.

Finger print processing involves two steps.1) finger enrollment and 2) finger matching. Initially, to enroll the finger user must give his finger print twice to the module. Module checks these two images and generates a template image and stores it. In the second step of finger matching, for 1:1 matching input finger print is matched with the template image generated and it generates an acknowledgement. For 1: N matching input is matched with the images in the library. It gives the matched image, a page id of the matched image is generated.

## ACTUATORS Used:
###### keypad:
Keypad used in this project is 4*3 keypad i.e. it has four rows and three columns. Columns of the keypad are connected to the PORT D pins of the microcontroller. PD5 to PD7 pins are connected to the three columns of the keypad. Rows are connected to the PORT C of the microcontroller. PC0 to PC3 pins are connected to the rows of the keypad. To give attendance, press 1 from the keypad and to enroll press 2 from the keypad, to clear all the data press 3 from the keypad.