# **Simple Relay Control Via Serial**
Documentation by Orwa

## **Components**
<ol>
<li> Hardware <li> 
<li> relay_sketch.ino <li> 
<li> relay.py<li>  
<ol>

## **Wiring Diagram**

## **Prerequisites (installation)**
<ol>
<li>	PySerial package. To install, type the following from the command prompt:
 “pip install pyserial” <li>  
 <ol>

## **Usage instructions (as a library)**
<ol>
<li> Launch “idle” on windows <li>
<li> Type: “import os;print(os.getcwd())” <li>
 
<li> Copy “relay.py” to subdirectory “Lib” within the folder above (displayed in idle in blue) <li>
<li> Now you can use the library using “import relay” then calling the following functions: <li>
>>>a.	relay.turn_on(): turns the relay on
>>>b.	relay.turn_off(): turns the relay off
<li>	Note that if the hardware is not connected, then an exception will be thrown when importing the library <li>
<li>	Note that if the hardware is connected but being used by another program, an exception will also be thrown when importing the library <li>  
 <ol>

## **Usage instructions (from the command line)**
<ol>
<li> To turn on the relay from the command line, go to the folder where “relay.py” is stored and type the following commands: <li>
>>>a.	“python relay.py 1” turns the relay on
>>>b.	“python relay.py 0” turns the relay off
<li> Note that if the hardware is not connected, an error message will be displayed. <li>
<li> Note that if the hardware is connected but being used by another program, an error message will be displayed <li>  
 <ol>

