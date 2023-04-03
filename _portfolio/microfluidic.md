---
title: "SLA Microfludic Device"
excerpt: "Resin-printed pinched flow fractionation mold."
header:
  image: /assets/img/mfdinitial.jpeg
  teaser: /assets/img/mfdinitial.jpeg
gallery:
  - image_path: /assets/img/mfdfinal.jpeg
  - image_path: /assets/img/mfdinitial.jpeg

---
# About



# Design
In order to match the design specifications and dimensions of a microscope slide, the mold interior is 25 mm by 75 mm, with walls of a 2.5 mm width on all sides. In the initial design (see below), the mold depth was 2 mm, but this was increased to 4 mm in future iterations. The posts for the microfluidic connections are of a 2 mm diameter, which is the width of the microfludic tubing, and extend 1 mm above the top of the mold. This ensures that the hole for the tubing permeates entirely through the molded part.

The design for the microchannel and other relevant features is based on data collected in the Yamada paper (see source 1, below). 
* This research determined that the optimal boundary angle; that is, the angle of the opening exiting the microchannel, to achieve maximum particle separation is 180 degrees. Smaller angles resulted in a lesser degree of separation. 
* The optimal channel depth throughout the entire geometry was determined to be approximately 50 microns. However, in order to better accomodate resolution limitations of 3D printing and to ensure that the microchannel molds properly, the microchannel depth was increased to 150 microns in later design iterations.

## Initial Design
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e1db99992810ef92e?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Final Design
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e1db99992810ef92e?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Printing Parameters
Both the PLA and TPU filament are printed on a bed heated to 60 C. The majority of the print settings remain the same. Here are the differences in printing parameters between PLA and TPU:
* **Extruder Temperature:** PLA is extruded at 210 C, and TPU is extruded at 240 C.
* **Print Speed:** Because it is flexible, TPU must be printed slower. The maximum print speed for PLA is 60 mm/s, and the maximum print speed for TPU is 25 mm/s.
* **Retraction Speed:** TPU must be retracted slower than PLA. The TPU retraction speed is set to 15 mm/s.

# Sources
1. Anal. Chem. 2004, 76, 18, 5465–5471
Publication Date:August 12, 2004
https://doi.org/10.1021/ac049863r
{% include gallery caption="Multimaterial Pliers Gallery" %}
