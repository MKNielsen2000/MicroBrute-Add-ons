#Microbrute addon boards / hacks
'''DISCLAIMER

These hacks/modifications are potentially dangerous for you and/or your synth. They are only for people with advanced electronics skills. I will not take any responsibility for any damage to your synth or yourself and understand that once you open your MicroBrute you lose your warranty.

'''
---

A bunch of boards for hacking / modifying the MicroBrute:
* White Noise Add-on
* Buffered output add-on

## White Noise Add-on
A tiny board that adds white noise to the Microbrute. 

![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/board%20rev1%20back.jpg?raw=true "Back of board rev 1")
![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/board%20rev1%20front.jpg?raw=true "Front of board rev 1")

Does what it says on the tin.

Based on a circuit from [Thomas Henry's noise generator cookbook](http://www.magsmoke.com/thomas_henry_books.asp).

Made possible thanks to [Yves Usson's publishing of all schematics related to the Microbrute.](http://hackabrute.yusynth.net/index_en.php)

#####STATUS
Boards done, need testing. 

####Connections

Power:
* Connect +12v to tp70 on the Microbrute
* Connect -12v to tp71 on the Microbrute
* Connect GND to tp72 on the Microbrute

![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/powerconnections.jpg?raw=true "power connections")

White noise:
* Connect OUT on white noise board to tp47 (external audio in) on the Microbrute

![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/tp47.jpg?raw=true "power connections")
 
 
## Buffered output Add-on
There are four waveform output hacks possible on the Microbrute but I've always thought it a damn shame that they get wired directly to output jacks with no protection and buffering which causes all sorts of issues. This boards fixes that problem. You mount this on one of the output jacks and wire three others to this board including the four waveforms. You can either pull the power from the above mentioned test points or daisy chain the power with the white noise generator. Pretty suave. 

![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/outputrev1.jpg?raw=true "Back of board rev 1")
![alt text](https://github.com/gilberte666/MicroBrute-White-Noise-Add-on/blob/master/outputrev1-2.jpg?raw=true "Front of board rev 1")

#####STATUS
Boards done, need testing. 