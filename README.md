# AirDefense-Sensor-Config-Script
An Expect script that simplifies configuration of Motorola (Extreme) AP7131 and AP621 AirDefense sensors

This assumes you are on a linux/mac system that has bash, expect and working USB to Serial adapter.
Place both 5-new and 5-boilerplate in the same directory and enter
'bash 5-new'

You will see...

What are the last two octets of the IP for this sensor? (192.168.x.y)
12.34
Where will this sensor be installed? (ex. DEN-02-123)
DEN-02-123        

The Expect script handles the rest...
