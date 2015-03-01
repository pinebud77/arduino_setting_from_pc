# An Application for Arduino setup using UART

This is a Visual C++ GUI application that set up Arduino board for my sensor node.

## What this application do?

- Communication with server to create an account
- Find UART port for Arduino
- Communicate with Arduino through UART for setup
- Specify SSID and password
- Scan through Arduino device if the functionality is supported


## Original source code

I got the CSerial and HTTP source code from somewhere I don't remember, and modified it. I don't know it is permitted.

## Thing to Do

- More general application framework (?)
- ~~Add sample UART output of my sensor node Arduino board~~

## Sample UART output from Arduino

```
Press 'c' key to update AP settings :
Press 'a' to set AP settings, Press 's' to scan APs :
Scan result :
SK\_WiFi4D19
-90
3
Press 'a' to set AP settings, Press 's' to scan APs :
SSID : Security : Password : Writing EEPROMj
reading EEPROM..
connecting to AP..
AP connected 1
mac: 18-fe-34-9d-15-5f
```
