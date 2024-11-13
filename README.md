# Blind-Roller

**V2------Blind Roller Remote Control Using Step Motor //In Progress**

-I used NEMA17 Step motor to have more certain control over the angles.
-I used TMC2209 to drive the step motor sliently and smoothly.
-I used NODEMCU ESP8266 - In the future i will use my own self-produced item.
-I will update box to cover step motor and mount it to the blind roller system ---Designs are made on Fusion 360 and printed by 3D printer by me.
-I used PLA for cover and used ABS for gear system.
-I will be sharing STL files and NODEMCU codes on this page.

Structure changed:
- I used TB6600 instead of TMC2209,2208,DRV8825,A4898,TMC2130  because of the torq needs of the load.

Power usage reducing and electricty outage caution.
-Added Selenoid Coil to stop motor gear physically to reduce

Next Plans:
- I will add current controller to the ESP8266
-I will add temperature control device one for Selenoid Coil one for ESP8266 to stop overheating risk.
-




**v1-Blind Roller Remote Controller Using Servo Motor ---> Updated  -->> Completed**

7:30 am blind openning  --NodeMCU D5 digital pin
19:30 pm blind closin automatically--- D4

Open button in the Blynk app will open the Blind  V5,V4
Close Button in the Blynk app will close the Blind V5 ,V4
Stop button in the Blynk app will stop every thing( this is an escape if something unexpected occurs)--V6 on Blynk

I use virtual pins to connect NODEMCU to BYLNK app 

V11: Button twice click feature 




