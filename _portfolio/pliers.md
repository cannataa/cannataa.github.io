---
title: "Multi Material Pliers"
excerpt: "Print-in-place, functional pliers, constructed from PLA and TPU."
header:
  image: /assets/img/Screenshot (175).png/assets/img/pliers render.jpg
  teaser: /assets/img/IMG_5819.jpg
gallery:
  - image_path: /assets/img/Screenshot (174).png
  - image_path: /assets/img/Screenshot (175).png
  - image_path: /assets/img/IMG_5819.jpg
  - image_path: /assets/img/pliers render.jpg

---
# About

Print-in-place parts are an exciting application of 3D printing. Instead of printing multiple parts that must be assembled in order to be functional, print-in-place parts are fully functional as soon as they are removed from the bed; no post-processing or assembly is required. More complex print-in-place parts are possible with dual extrusion printing. Portions of the printed part can have different properties, depending on the filament used. For example, flexible filaments such as TPU can be used for the joints of a part, while other filaments such as PLA or ABS can be used to form rigid components. Because of the layer-by-layer construction of 3D printed parts, different filaments can be printed such that each part component is attached to the other once the print is complete.

These principles were applied to design a set of needle-nose pliers that are capable of picking up, moving, and releasing items of >3 mm diameter. The handles and jaws were printed from PLA, and the flexible hinge was printed from TPU, with TPU joints embedded into the PLA portions to attach the components of the print. Instead of the traditional pliers mechanism, I chose to design pliers that were closed in the relaxed position (there is a 1.5 mm gap between the relaxed jaws in the final design). Applying pressure to the handles causes the jaws to open, and relieving pressure allows the jaws to close down on the object of interest. Further pressure can be applied to the object of interest by pulling the handles outward if desired. 

The TPU hinge is circular in design, with the segment between the handles cut out, in order to provide room for the handles to close under pressure. In the initial design, the TPU hinge was too narrow and therefore did not provide enough resistance to applied force such that the jaws would adequately open. The relative difference between the outer and inner radii of the hinge was therefore increased in later designs (see image gallery below). Also in the initial design, the PLA portions were attached to the hinge by T-shaped TPU inserts protruding from the hinge. While this successfully conjoined the TPU and PLA portions of the part, the narrow strip (the "stem" of the T) allowed for extraneous rotation of the handles and did not offer enough support, such that when the handles were compressed, they just pulled away from the hinge without exerting the desired force. This was corrected in later designs by changing the attachments to U-shaped inserts. The final major design change was increasing the angle between the handles at the relaxed position, from 38 degrees to 80 degrees. This allowed for the potential of a greater force to be applied to the hinge.

# Design
The jaws are 1.5 mm apart at resting, can open to a maximum of _ mm, and can close such that the jaws are touching. The jaws are 25 mm in length.

## Initial Design
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e439dab8299d2a1310f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Final Design
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e43b07d1aae18632c20?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Printing Parameters
Both the PLA and TPU filament are printed on a bed heated to 60 C. The majority of the print settings remain the same. Here are the differences in printing parameters between PLA and TPU:
* **Extruder Temperature:** PLA is extruded at 210 C, and TPU is extruded at 240 C.
* **Print Speed:** Because it is flexible, TPU must be printed slower. The maximum print speed for PLA is 60 mm/s, and the maximum print speed for TPU is 25 mm/s.
* **Retraction Speed:** TPU must be retracted slower than PLA. The TPU retraction speed is set to 15 mm/s.


{% include gallery caption="Multimaterial Pliers Gallery" %}
