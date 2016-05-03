![Byotics](https://github.com/connieleung/byotics/blob/gh-pages/assets/bg/biotic-gaming.jpg?raw=true)
# Byotics
### A Paramecia Pong Game Interface
Control paramecias with an electric field and motion gesture


<br>
---
###Inspiration 

#####Abstract

[Design, engineering and utility of biotic games](http://pubs.rsc.org/en/content/articlehtml/2011/lc/c0lc00399a), 18th November 2010 (open access article)


<br>
####Core
* [Biotic Gaming White Paper](http://pubs.rsc.org/en/content/articlepdf/2011/lc/c0lc00399a)  *PDF*

* [Paramecium/Arduino interface](http://making.do/paramecium/), 25 APR 2013
* [Variable-focus liquid lens](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-15-10-5931&id=134423)
* [Lab on Chip](http://pubs.rsc.org/en/journals/articlecollectionlanding?sercode=lc&themeid=6d7cd3f3-3674-4118-88ba-93af80017515)
* [Low Tech Microfluidics](http://www.cytofluidix.com/low-tech-microfluidics/)
* [Low Tech Microfluidics Video](https://vimeo.com/117917126)



<br>
<br>
### About Parameicas
---
* [paramecias 101](http://101science.com/paramecium.htm)
* [photography through a microscope](http://sci-toys.com/scitoys/scitoys/biology/micro.html)
* [paramecium wiki](https://en.wikipedia.org/wiki/Paramecium)
* [human relationship](http://www.fcps.edu/islandcreekes/ecology/paramecium.htm)



<br>
<br>
### Hardware
---
* Logitec Webcam
* laser pen lens
* ~~[Belkin WeMo Netcam](http://cache-www.belkin.com/support/dl/QIG_F7D7602_8820-01324_RevA00_NetCamHD.pdf) *PDF*~~
* Arduino Uno
* ZX Gesture Sensor
* Small tupperware
* dielectric fabric, thread
* Z-axis dielectric tape
* wires
* hydrocarbon (CnH2n+2) wax
* double-sided tape
* ravine water
* non-dielectric insultar tape
* aluminium/copper tape
* Olfa knife
* clear nail polish
* [multimeter](http://www.sciencebuddies.org/science-fair-projects/multimeters-tutorial.shtml#usingamultimeter)

![hardware](https://github.com/connieleung/byotics/blob/gh-pages/arduino/sketch/assets/IMG_20160129_231453.jpg?raw=true&w=60)


<br>
<br>
### Setup
---
###### Arduino Hookup Guide
---
![Arduino Hookup Guide](https://cdn.sparkfun.com/assets/learn_tutorials/3/4/5/zx_sensor_fritzing_bb.png)
Fritzing Schematic
![Arduino Hookup Guide 2](https://cdn.sparkfun.com/assets/learn_tutorials/3/4/5/ZX_Sensor_Hook_Up_Guide-05.jpg)
Real-life setup
<br>
###### Arduino Library Setup for ZX Sensor & Play
---
1. Sketch > Include Library > Manage Libraries... > Search "SparkFun ZX Distance and Gesture Sensor v1.0.1" (or populate keyword "gesture") > Install
2. File > Examples > SparkFun ZX Distance and Gesture Sensor > Select "I2C_Gesture_Demo" to get you started
3. Run your demo ![Demo Run](https://cdn.sparkfun.com/assets/learn_tutorials/3/4/5/Gesture_init.png = 100x320)
3. Move your hand around above the sensor, and you should see Z (height above the sensor) and X (position side to side) appear in the serial terminal ![Gesture Motion](https://cdn.sparkfun.com/assets/learn_tutorials/3/4/5/ZX_Sensor_Hook_Up_Guide-05.jpg = 320x)
4. Live Z- and X- data should appear given as an unsigned integer between 0 and 240 (inclusive) ![Gesture Arduino Run]<img width="320" https://cdn.sparkfun.com/assets/learn_tutorials/3/4/5/ZX_Demo_run.png />
5. More information for this sensor model and hookup can be found on [SparkFun](https://learn.sparkfun.com/tutorials/zx-distance-and-gesture-sensor-hookup-guide#arduino-gesture-example) :feelsgood:


