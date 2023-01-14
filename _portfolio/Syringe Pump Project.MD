---
title: "Syringe Pump Project"
excerpt: "A low budget automatated syringe pump system designed with 3D printed parts."
header:
  image: /assets/img/Syringe Pump Design.jpg
  teaser: /assets/img/Syringe Pump Design.jpg
gallery:
  - image_path: assets/img/Syringe Pump Design.jpg
  - image_path: assets/img/Syringe Pump pic 2.jpg 
  - image_path: assets/img/Syringe Pump pic 3.jpg
   
---


# Purpose

Syringe Pumps are vital pieces of equipment in the medical industry and are used widely
from laboratories to hospitals. Syringe pumps deliver small amounts (0.012–300 mL/min) of fluid
accurately and they are commonly used for drug dosing and injections. Syringe pumps are preferred
to other methods of fluid delivery as they are very sterile and can be sealed. Furthermore, they are
intuitive to use and provide stable flow for liquids of varying viscosity. While using a syringe pump
is very straightforward, it is quite hard to provide a consistent flow rate using a syringe pump
manually by pressing on the plunger. As a solution to this problem, it is becoming more common to
see automated syringe pumps that press liquid out at a constant flow rate. These devices can be
quite expensive, however they require only simple electronics and easily manufactured parts.
Therefore, the purpose of this project was to create a lower
budget automated syringe pump.

# Features

Mechanically, this syringe pump system is designed so that when the button is pressed, the LED
changes from red to green and the stepper motor is turned on and begins to run. As one end of the
flexible coupler is attached to the motor shaft, the coupler rotates in time with the motor shaft. The
lead screw is attached to the other end of the flexible coupler which is how the rotation of the motor
shaft is translated to the lead screw. This lead screw is what allows the copper nut, which is screwed
into the middle support structure, to traverse along the length of the lead screw while unobstructed.
As a consequence of this fixed connection, the middle support structure will also traverse along the
length of the lead screw. This connection is how the pump translates the rotation of the stepper
motor into the linear motion of the syringe plunger. Both the nut and lead screw traverse the lead
screw, moving 8 mm for every rotation of the motor shaft. The middle support structure is hovering
over the top of the electrical enclosure, allowing it to glide along the linear rod and move with the
copper nut along the lead screw. When the middle support structure, which pushes the plunger and
compresses the syringe, hits the switch that is attached to the support structure holding the body of
the syringe, the motion of the system will stop. The motor shaft will no longer rotate. The coupler
and lead screw will cease rotating and the middle support structure will remain in place.

# Parts Required 
  **Off-the-Shelf Parts**
  
---

| Off-the-Shelf Parts  | Quantity |
| ------------- | ------------- |
| 250 mm lead screw with 2mm pitch and 8 mm lead  | 1  |
| 1/4" x 8 mm Flexible Coupler  | 1  |
| 200 mm linear rod with 8 mm diameter  | 1  |
| LM8UU Linear bearing for 8 mm diameter rod  | 1 |
| LM8UU Linear bearing Clips | 2  |
| Nema 17 Stepper Motor  | 1  |
| MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp  | 1  |
| Arduino Uno  | 1  |
| A4988 Stepper Driver  | 1  |
| Small Breadboard  | 1  |
| Panel Mount Latching Push Button  | 1  |
| Limit Switch  | 1  |
| RGB Common Cathode LED  | 1  |
| M3 x 6 mm Screws  | 8  |
| M3 x 12 mm Screws  | 8  |
| 24 AWG Wire Roll  |  4  |
| Insulated Electrical Wire Connectors  | 4  |
| 20 Pair 18-24 AWG Gauge Pins  | 1  |
| 3 mm Heat Insets  | 8  |

---

  **3D-Printed Parts**
  
---
  
| 3D-Printed Parts  | Quantity |
| ------------- | ------------- |
| Bottom component of box   | 1  |
| Top component of box  | 1  |  
| Motor mount support  | 1  |
| Middle support structure  | 1  | 
| Syringe pump body support   | 1  |

---

# Operation

* Make sure the small, middle floating support piece is set directly in front of the coupler at the “starting position”.
* Place the desired, liquid filled syringe (20mL or 5mL) into the corresponding “mold” that supports the body of the pump. The nose of the
syringe should be resting on the smaller semicircle depression with the wings of the pump secured
in the 3.5 mm thick slit. 
* Ensure that the circular back end of the plunger is firmly fixed in the slits of the middle support structure that will be operating along the lead screw.
* Specify the desired flow rate in the Arduino IDE program.
* The LED on the left side of the syringe pump system should be red. Press the red button on the far left, next to the LED. The LED should turn from red to green. Simultaneously, the stepper motor will begin to turn the flexible coupler, which in turn will rotate the lead screw at a calculated rate of steps per millimeter, pushing the middle support structure and the back end of the plunger forward along the linear rod and compressing the syringe. 
* If the red button is pressed at any time after the green light and before the syringe is completely compressed, the LED will turn yellow and the system will pause. If the button is pressed once more, the LED will turn green again and the motion of the system will continue. 
* When the syringe is completely decompressed, the switch will be triggered and the LED should turn red. At the same time, the
stepper motor will stop turning the flexible coupler, which will stop the rotations of the lead screw.
The back support of the plunger will also stop moving along the linear rod.

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e4321ab69ef979d9715?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Arduino Code 

Click [here](https://create.arduino.cc/editor/mmcdonald7000/3189c821-d817-4559-a097-ff17348fe9fe/preview) to access the Arduino code used to run this syringe pump system.

{% include gallery caption="Syringe Pump Photo Gallery" %}
