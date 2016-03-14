# RGB-LED-control-using-Android-Smartphone
Change the colors of RGB LED connected to Intel Edison using values values from Android Smartphone

We use Android Smartphone sensors to change the color of RGB-LED connected to Intel Edison.
Sensor data is sent from Smartphone to Intel Edison via Bluetooth protocol.  

Smartphone code to get sensor data and transfer it to Intel Edison is written by Sarweshkumar CR.

Hardwares used:
Intel Edison
Android Smartphone ( which has accelerometer and magnetometer )
3 resistors each of 220 Ohm.
RGB LED 

Pin Configuration : 
Connect Red LED pin to pin 3 of Intel Edison via 220 Ohm resistor
Connect Green LED pin to pin 5 of Intel Edison via 220 Ohm resistor
Connect Blue LED pin to pin 6 of Intel Edison via 220 Ohm resistor
Connect Anode LED pin to 5 V supply of Intel Edison

For bluetooth configuration on the Intel Edison, run the file rgbled_setup.sh using the command ./rgbled_setup.sh

The link for buying LED online is -  http://www.ebay.in/itm/8mm-Diffused-Round-RGB-LED-Diode-Common-Anode-Super-Bright-4-Legs-10-Pcs-Per-Lot-/171983997852?_trksid=p2054897.l4275
The desciption of LED can be found here - https://arduino-info.wikispaces.com/RGB-LED
