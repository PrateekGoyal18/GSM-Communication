This repository has codes for interfacing GSM SIM900A with ESP32 microcontroller.
The file "all functions" has the following features
Markup : 1. Sending SMS
        2. Receiving SMS
        3. Calling
        4. Receive a call
        
The file 

**Some points to consider:**
 Markup : 1. For Arduino or ESP8266, just change the HardwareSerial library to SoftwareSerial library and accordingly map the GPIO pins.
          2. If your SIM900A is not working, try 12V/2A supply, mine worked with this only.
