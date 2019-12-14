This repository has codes for interfacing GSM SIM900A with ESP32 microcontroller.

The file "all functions" has the following features
1. Sending SMS
2. Receiving SMS
3. Calling
4. Receive a call
        
The file receiving messages has 2 types of codes - static and dynamic. In static, a reply message is sent to a specific number, irrespective of where it came from. But in dynamic, a reply message is sent to a number from which the message came from.

```
Some points to consider:
1. For Arduino or ESP8266, just change the HardwareSerial library to SoftwareSerial library and 
accordingly map the GPIO pins.
2. If your SIM900A is not working, try 12V/2A supply, mine worked with this only.
3. The N/W led will blink every 3 seconds once a connection has been established.
4. In India, SIM900A works well with 4G SIM Cards - Airtel, Idea and Vodafone but not with JIO.
```
