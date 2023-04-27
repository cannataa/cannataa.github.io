---
title: "SLA Microfludic Device"
excerpt: "Resin-printed pinched flow fractionation mold."
header:
  image: /assets/img/mfdinitial.jpeg
  teaser: /assets/img/mfdinitial.jpeg
gallery:
  - image_path: /assets/img/mfdfinal.jpeg
  - image_path: /assets/img/mfdinitial.jpeg
  - image_path: /assets/img/mold.jpg
  - image_path: /assets/img/setup.jpg
  - image_path: /assets/img/separated.jpg

---
# About
Pinched flow fractionation is a method of size-based separation. Two solutions, one containing particles and the other without, are introduced to a microchannel together such that the particles are all aligned to one sidewall of the microchannel. As the flow profile expands out of the microchannel, the trajectory of the particles is determined by their size. This separation can be observed under a microscope, and separated particles can be directed into different outlet channels. Several factors affect the degree of separation, including the ratio of flow rates between the particle-containig and non particle containing solutions (the degree of separation increased as the relative flow of the particle-containing solution decreased) and the width of the microchannel (the degree of separation increased as the microchannel width decreased). Pinched flow fragmentation could have several applications, but for our case, we considered the separation of blood cells.

Stereolithography (SLA) printing is an optimal method of producing the molds for these microfluidic devices because of the high resolution that is possible. The SLA printers in the DFL are able to print features as small as 25 microns. Unfortunately, SLA prints can sometimes warp when they are cured. To avoid this, and because the mold does not necessitate intense mechanical properties, we elected to forgo the curing stage of post-processing in order to maintain the precision of the part dimensions to the highest degree possible.

# Design
In order to match the design specifications and dimensions of a microscope slide, the mold interior is 25 mm by 75 mm, with walls of a 2.5 mm width on all sides. In the initial design (see below), the mold depth was 2 mm, but this was increased to 4 mm in future iterations. The posts for the microfluidic connections are of a 2 mm diameter, which is the width of the microfludic tubing, and extend 1 mm above the top of the mold. This ensures that the hole for the tubing permeates entirely through the molded part.

The design for the microchannel and other relevant features is based on data collected in the Yamada paper (see source 1, below). 
* This research determined that the optimal **boundary angle**; that is, the angle of the opening exiting the microchannel, to achieve maximum particle separation is 180 degrees. Smaller angles resulted in a lesser degree of separation. 
* The optimal **channel depth** throughout the entire geometry was determined to be approximately 50 microns. However, in order to better accomodate resolution limitations of 3D printing and to ensure that the microchannel molds properly, the microchannel depth was increased to 150 microns in later design iterations.
* The optimal **microchannel width** was determined to be approximately 50 microns.
* The optimal **microchannel length** was determined to be 100 microns.
* The paper discussed two potential **conformations for post-separation species collection**: (1) a uniform-width single outlet channel in which the separation of particles could easily be observed, and (2) multiple outlet channels, each ideally containing a single particle type or contaminent, which lead to separate tubing ports. In our final design, we elected for conformation (2), with three outlet channels. If our device were to be used to separate blood cells and related contaminants, tests would have to be run in order to determine the optimal angles between these outlet channels.
* The final design change between our inital and final designs was to increase the **depth of the inlet tubing ports**. This should help to prevent blockage or clogging entering the microchannel.

## Final Fusion360 Design
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e1db99992810ef92e?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Molding Process
A solution of PDMS, a silicone polymer, and a hardener is mixed and poured into to the SLA printed molds. A vacuum is applied to release any air bubbles trapped in the solution. The filled molds are then heated and cured. After the microfluidic devices are demolded, they are bonded to a glass slide. The demolded microfluidic device looks like this:
![Demolded Pinched Flow Fractionation Microfluidic Device](mold.jpg)

# Part Testing
In order to test our pinched flow fractionation device, two inlet flows were set up: one of pure water and the other with a contamination of small particles. Although the mold has three outlet holes, the width of the tubing adapters only allowed for the outer two outlet streams to be run through tubing. The setup can be seen in the image and video below:

![Pinched Flow Fractionation Setup](setup.jpg)
[Setup Video](https://youtube.com/shorts/iuPDcyEqd0U?feature=share)

The two outlet streams were collected and observed. In the picture below the rightmost tubes are cloudier than than the column second to the right, indicating a successfull separation after mixing.
![Separated Outlet Streams](separated.jpg)

# Sources
1. Anal. Chem. 2004, 76, 18, 5465–5471
Publication Date:August 12, 2004
https://doi.org/10.1021/ac049863r
{% include gallery caption="MMicrofludic Devices Gallery" %}
