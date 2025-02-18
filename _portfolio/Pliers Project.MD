---
title: "Multi-Material 3D Printed Pliers"
excerpt: "A multi-material plier designed with a flexible TPU spring component and rigid body. These pliers are capable of handling 3 mm diameter plastic pellets."
header:
  image: /assets/img/Pliers1.jpg
  teaser: /assets/img/Pliers6.png
gallery:
  - url: /assets/img/Pliers3.png
    image_path: assets/img/Pliers3.png
    alt: "placeholder image 1"
  - url: /assets/img/Pliers4.png
    image_path: assets/img/Pliers4.png
    alt: "placeholder image 2"
  - url: /assets/img/Pliers7.png
    image_path: assets/img/Pliers7.png
    alt: "placeholder image 3"
  - url: /assets/img/Pliers5.png
    image_path: assets/img/Pliers5.png
    alt: "placeholder image 4"
---

# Description
Snap-fit models are functional designs that are printed in separate components and assembled without the use of glue or tools. This method of additive manufacturing allows fast print times and variability in materials, colors, and attachments. For instance, the pliers in this project were printed on two separate printers that ran simultaneously, decreasing overall print time and introducing several materials such as PLA, ABS, and TPU filaments. An alternative method to obtaining an operative device is print-in-place parts. No post-processing or assembly is required, which means the model works immediately after removal from the print bed.

# Features
* **Materials** Three materials were used in the design of the pliers to ensure optimal functionality. The red component is made of ABS. This piece was printed in a Voron2 with a 0.4 mm extrusion nozzle and a closed chamber. ABS has high tensile strength and is resistant to physical impacts and chemical corrosion. It enabled a very sturdy and durable part for the pliers. The grey and blue components were printed as one structure. The grey material is PLA, and the blue is 95A TPU. This piece was fabricated on a dual extruder MakerGear printer with 0.35 mm nozzles. Because the MakerGear had a moveable bed and did not have an insulated chamber, the rigid handle, rotation section, and tip of the right side of the pliers were printed with PLA. The flexible TPU material creates a spring-loaded action that returns the plier tips to the open position, whenever not in use. The TPU/ PLA component was printed with dual extruders so both materials could be incorporated and secured in the print. An “L” shaped TPU structure was designed inside the PLA piece to ensure the two different materials stayed intact. 

* **Design** To assemble the device, align the two sides of the pliers so that the two rotational indents on the pieces are facing each other and the flexible TPU attachment rests gently in the pocket on the opposite component. Then, carefully but firmly press down on the circular rotational piece of the pliers. There should be a small snap when the pliers are completely together, and the face of the pliers is flat. These pliers are capable of gripping and picking up a plastic pellet with a 3 mm diameter, moving it to another location, and releasing it. When there is no pressure applied to the pliers, the tips rest in the open position. When they are squeeze, the flexible TPU piece attached to one side of the pliers is guided into a small pocket on the other side and the 4 small 2 mm by 2 mm square openings in the spring are compressed until the object that is being gripped is secured or until the plier tips meet. Once the pressure is released, the TPU retracts and forces the pliers back open. 

* **Dimensions** When completely open, the plier tips are 11.65 mm apart. They can compress until the jaws are touching, which is 16.6 degrees from the open position. The pliers are 98.787 mm high, 5 mm thick, and the outer edges of the base of the plier handles are 50.623 mm apart. The length of the plier tips/jaws are 29.777 mm. 

* **Print Settings** The ABS component used the Digital Fabrication Lab (DFL) configuration files for the Voron2 printers. Some characteristics of this material included a higher bed temperature (100℃) and extrusion nozzle temperature (240℃). The PLA and 95A TPU filaments were printed using the MakerGear configuration files provided by the Digital Fabrication Lab and the program SuperSlicier. The TPU material was printed slower than the PLA filament (25mm/s maximum speed) and had a faster retraction speed (15mm/s). Additionally, the extrusion nozzle was warmer for TPU (240℃). Support material was included under the flexible piece, and it was made of PLA. Also, there was a wipe tower to prime the extrusion nozzles and wipe excess filament before printing each layer. 

# CAD Model
<iframe src="https://a360.co/3IISzZr" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="This is a sample gallery to go along with this project." %}
