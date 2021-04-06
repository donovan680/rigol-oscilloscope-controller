# rigol-oscilloscope-controller
Controlling a Rigol oscilloscope using Linux and Python.

After many frustrated nights trying to debug electronics projects blindly (the analog scope is wayyyy too much work to pull off the shelf and use), I decided it was time to spring for a digital storage oscilloscope. Since I had read many good things about them, I chose the Rigol DS1052E, which is a two channel 50 MHz scope that can be easily modded to work at 100 MHz. The scope is way smaller and lighter than I expected, and has a nice set of buttons that give it the feel of a quality instrument. It works perfectly well as a standalone device, however since it has a USB slave port that implements the usbtmc interface, it turned out to be pretty easy to control using Linux. After a night of coding (most of which involved re-learning Python), 
I was able to grab data from the device and plot it:

