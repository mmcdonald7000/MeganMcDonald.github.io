---
title: "Large Format 3D Printed Podium"
excerpt: "Generative design was leveraged to create an optimized podium for large format 3D printing."
header:
  image: /assets/img/podiuma.jpg
  teaser: /assets/img/podiumh.jpg
gallery:
  - url: /assets/img/podiumc.jpg
    image_path: assets/img/podiumc.jpg
    alt: "placeholder image 1"
  - url: /assets/img/podiumd.jpg
    image_path: assets/img/podiumd.jpg
    alt: "placeholder image 2"
  - url: /assets/img/podiume.jpg
    image_path: assets/img/podiume.jpg
    alt: "placeholder image 3"
  - url: /assets/img/podiumf.jpg
    image_path: assets/img/podiumf.jpg
    alt: "placeholder image 4"
  - url: /assets/img/podiumg.jpg
    image_path: assets/img/podiumg.jpg
    alt: "placeholder image 5"
---

# Design Description & Discussion
A general structure of the podium was created in the “Design” tab on Fusion 360. The height of the podium was 1219 mm and the width was 523 mm. At the top of the structure, a flat small shelf was extruded 107.8 mm towards the speaker to conceal the speaker’s notes or give additional space to place items. A slanted presentation platform was directly underneath the small shelf at a 15° angle to hold a book, speech, or laptop at the proper height for a reader or speaker (1045.651 mm to 1143.30 mm). A lip sat at the edge of the slanted surface closest to the speaker to prevent objects from sliding off. A middle shelf was placed perpendicular to the podium wall 322.478 mm below the bottom of the slanted ledge to provide ample storage for accessories and supplies. The bottom shelf was 651.6 mm underneath the middle shelf to hold larger items. The middle and bottom shelves had a depth of 581 mm and the presentation platform had a depth of 377.765 mm. On the front of the podium wall, facing away from the speaker was a design symbolizing the Digital Fabrication Lab at Vanderbilt University. The minimum feature size of the podium was 30 mm so that the model was compatible with the LF3DP printer. Additionally, no supports, extreme overhangs (< 45°), or excessive bridging (> 100 mm) were made. Once the basic structure of the podium was created, separate bodies were formed between the shelves, on the open face of the podium closest to the speaker, and on the top surface of the slanted platform.  These bodies enabled Obstacle Geometries to be selected in the “Generative Design” tab on Fusion 360. The other bodies such as the podium wall, the slanted platform, and the shelves were chosen as Preserved Geometries. Structural constraints and load cases were implemented so that the podium would remain standing if the speaker were to lean up against it using 400 N of force or if objects were placed on the shelves. Study materials such as aluminum, stainless steel, and nylon were chosen to give an accurate representation of the model. Then, a pre-check was initiated to ensure that the model was printable. Once there were no warnings in the pre-check section, a preview of the design was created to give a rough estimate of the generative design. The structure was then generated, and the optimal generative design outcome was selected. Adjustments were made according to printability limitations. And before a life-size version of the podium could be created on the LF3DP, a smaller model was printed on a Voron 3D printer. 

# LF3DP Printer Specifications
- Build volume 4’x4’x4’
- Output ~ 1 kg hour
- Overhang angle > 45°
- Bridge distance < 100 mm
- No Support material
- Minimum feature size: 30 mm

# Research & Discussion
Large Format 3D printing (LF3DP) is an industrial-scale 3D printing application that creates objects layer by layer instead of traditional molding or machining techniques. Not only is this innovative technology cost-effective because it reduces the amount of waste material and the production time, but it is also capable of producing complex geometries. The limitations of this technology, however, are its support structures and overhang tolerances. Because the extruded material from the large nozzle stays warm and has a higher viscosity when it is initially deposited, the fibers cannot withstand overhang angles less than 45 degrees. While heat from the material results in strong mechanical properties due to high quality adhesion between layers, it is not desirable for the removal of support structures. Therefore, support material in large format printing is not used. 

Prior to 3D printing on such a large scale, Generative Design is usually used to optimize the printing operation. Generative Design (GD) is an iterative exploration process in which engineers and architects input design goals into software, along with parameters such as performance or geometry requirements, materials, and constraints. It generates a range of design solutions that meet the set information. With every set of solutions, the computer software undergoes machine learning to ensure higher quality for future iterations. This design process is much faster than the standard system and it allows designers to explore many decisions. Generative Design can also lower the risks associated with a project. For example, if it is given the correct parameters and algorithms, the system can understand complex data and predict dangers. Though it is largely automated, a disadvantage of generative design is that it encourages the designer to leverage machine learning. Without choosing and changing an output, the resulting designs may not stand up to the high expectations of the designer. 

LF3DP and GD have gained interest and support throughout society, especially because of their potential in the residential construction industry. For example, large scale 3D printers could use concrete as material to fabricate shelters for the homeless. With about 18% of the nation’s population living on the streets, homelessness is one of the biggest socioeconomic issues in the U.S. today. Using 3D printing to build homes is a fast, affordable, sustainable, and an efficient solution to this global issue. Several companies and nonprofit organizations are teaming up to address homelessness in low-income communities with Generative Design and LF3DP. The process involves creating a blueprint and printing the materials layer by layer. By leveraging a Generative Design workflow to create a podium for the Digital Fabrication Lab, I was able to see how modeling through a software program can help optimize a project and produce a life-like structure. 

Generative Design is used in the construction industry to quickly explore and make decisions on complex design problems. It allows for a more effective workflow between humans and computers. The first stage of GD is using the algorithm and parameters specified by the designer to produce multiple design outcomes. Once the options are generated, an analysis is performed to test how well the system achieved the goals defined by the designer. The optimal designs are ordered and ranked according to the results of the analysis. The process uses the rankings for machine learning to determine which direction the design should be developed next. Once the designer compares the generated outcomes and chooses their favorite design option, the project can be edited and integrated by the designer. 

When the blueprints of the structure are developed and approved, home builders can send the design to the LF3DP. This preparation step allows the printer to process the digital file that was generatively altered. It will automatically map out the structural reinforcement, placing the electrical and plumbing outlets during the print. Before printing begins, rails are installed around the building site to direct the nozzle on where to lay the build material. Once the home has been printed, post processing such as removing rails can be complete. Then, other installments on the house can be made including putting in windows, doors, plumbing, and electrical wiring. 

Traditional homes require tons of material and transportation. However, 3D-printing technology requires limited equipment and less transportation, which can lead to a reduced carbon footprint during building. Houses are built within a month or two compared to the normal 6 months to 9 months construction period. This can be extremely beneficial in case of an emergency where shelters need to be built immediately. Additionally, this process can be sustainable not only because less waste is produced, but also because old construction materials can be recycled into concrete that can be used again to build these houses. And due to the larger percentage of carbon emissions, experts are looking for more eco-friendly alternatives including natural materials like hemp or clay, or recycled glass and plastic to use as building material. While these products aren’t widely available yet, they have potential to contribute to the future processing of 3D-printed homes. 

Because of the cheap costs, scalability, and fewer required laborers, 3D printed homes could play an important role in helping the US address a housing crisis fueled by worker shortages and material costs. While the machines that build 3D printed houses are large and capable of complex structures, they still have some limitation on the size of parts that can be printed and the types of materials that can be used. But the biggest challenges that the 3D printed housing industry faces are lack of additive manufacturing resources and lack of expertise. Therefore, the goal of 3D printing in construction should be to bring together companies to collaborate and invest in the industry. There is a huge learning curve for traditional construction companies and workers when it comes to using Generative Design and operating industrial sized 3D printers. And, as with any innovative technology, it will take some time for the public to familiarize themselves with this new method. But with continued research and development, Generative Design and Large Format 3D Printing will transform the future of housing and can provide a solution to the housing issue around the world.


# CAD Model
<iframe src="https://a360.co/40j7HDM" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="This is a sample gallery to go along with this project." %}
