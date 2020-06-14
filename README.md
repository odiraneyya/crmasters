![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `# **Simple Relay Control Via Serial**`
Documentation by Orwa

## **Components**
1. Hardware
1. relay_sketch.ino
1. relay.py

## **Wiring Diagram**
![Wiring Diagram](Wiring Diagram.svg)

## **Prerequisites (installation)**
1. PySerial package. To install, type the following from the command prompt:
 “pip install pyserial”

## **Usage instructions (as a library)**
1. Launch “idle” on windows
1. Type: “import os;print(os.getcwd())”
 
1. Copy “relay.py” to subdirectory “Lib” within the folder above (displayed in idle in blue)
1. Now you can use the library using “import relay” then calling the following functions:  
a. relay.turn_on(): turns the relay on  
b. relay.turn_off(): turns the relay off
1. Note that if the hardware is not connected, then an exception will be thrown when importing the library
1. Note that if the hardware is connected but being used by another program, an exception will also be thrown when importing the library

## **Usage instructions (from the command line)**
1. To turn on the relay from the command line, go to the folder where “relay.py” is stored and type the following commands:  
a.	“python relay.py 1” turns the relay on  
b.	“python relay.py 0” turns the relay off
1. Note that if the hardware is not connected, an error message will be displayed.
1. Note that if the hardware is connected but being used by another program, an error message will be displayed
