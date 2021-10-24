# esphome-capacitive-touch-panel
<p float="left">

<img src="/docs/images/capacitive-touch-panel_3d.png" alt="3d render" width="48%">
<img src="/docs/images/touch-panel.gif" alt="3d render" width="48%">
</p>

A DIY capacitive touch panel based on the mpr121. Consisting of two PCBs, the main PCB where all the logic is located such as the mpr121, an esp8266, a buzzer, and one PCB where the buttons are located. Both are connected using 12 pin headers.

# construction
<img src="/docs/images/construction.png" alt="construction" width="48%">#

### Front panel PCB
<img src="/pcb/front panel/front panel_2021-10-22.svg" alt="construction" width="48%">
The front panel has 12 copper areas/pad on it for the individual buttons and can be customized for a different button layout. Each pad is connected through the pin headers with each one input to the mpr121 located on the logic PCB. 

### Logic module PCB
The logic module PCB houses the mpr121, a buzzer for optional auditory feedback and an esp8266 nodemcu.



# Build your own

**⚠️Disclaimer⚠️**

Firstly at the moment, the panel has a bit of a learning curve and isn't 100% intuitive if you use it the first time, but you can get the hang of it fairly quickly and after that, nearly all your inputs are registered. 

Secondly, this is the first "thing" that I created myself and published, also I am fairly new to all of this. I have nearly no experience in designing PCBs and do not really understand how capacitive touch recognition works. So I don't want to be responsible if you are going to build it yourself and can't guarantee that it works if you build it, but I am willing to help you to debug!

## BOM

- esp8266 NodeMCU Lolin 
- buzzer
- MPR121 Breakout
- Logic module & Front panel PCB
- Glass / Acrylic Glass 100 x 100 x 2 mm
- 12 Header pins

### PCBs
If you don't want to order the PCBs yourself (I ordered them from jlcpcb), I have a few spare ones that I could sell you for cheap.
If you are designing your own front panel PCB, I would be happy if you would share your design!

# images
<p float="left">

<img src="/docs/images/1.jpg" alt="3d render" width="48%">
<img src="/docs/images/2.jpg" alt="3d render" width="48%">
</p>
<p float="left">

<img src="/docs/images/3.jpg" alt="3d render" width="48%">
<img src="/docs/images/4.jpg" alt="3d render" width="48%">
</p>
