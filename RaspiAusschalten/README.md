pi-shutdown
===========

Shutdown/reboot(/power on) Raspberry Pi with pushbutton

## Usage:
Connect pushbutton to GPIO pin 5 and ground then run:
```
sudo python pishutdown.py
`
When button is pressed for less than 3 seconds, Pi reboots. If pressed for more than 3 seconds it shuts down.
While shut down, if button is connected to GPIO pin 5, then pressing the button powers on Pi.

## Danke

Das Programm pi-shutdown wird von verschiedenen Seiten bereitgehalten. Ob es irgendeine Lizenz hat, weiß ich nicht.
Danke an: http://www.netzmafia.de/skripten/hardware/RasPi/Projekt-OnOff/index.html  und 
https://github.com/gilyes/pi-shutdown/blob/master/pishutdown.py 

