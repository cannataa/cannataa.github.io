---
title: "LF3DP Generative Design"
excerpt: "A tiered podium created with generative design methods for large format 3D printing."
header:
  image: /gdp5.png
  teaser: /assets/img/gdp5.png
  
gallery:
  - image_path: /assets/img/gdp1.png
  - image_path: /assets/img/gdp2.png
  - image_path: /assets/img/gdp2.5.png
  - image_path: /assets/img/gdp3.png
  - image_path: /assets/img/gdp4.png
  - image_path: /assets/img/gdp5.png
  - image_path: /assets/img/gdp6.png
  - image_path: /assets/img/gdp7.png
  - image_path: /assets/img/gdp8.png

---
## Design
The base platform of the podium was first set to dimensions of 450 mm by 600 mm. This ensured that the area of the slanted surface was more than large enough to comfortably hold a laptop at 435 mm by 600 mm (approximately 17” by 24”). The base was set to 40 mm thick, and the Pattern tool was used to create two additional 40 mm shelves above the base. Finally, the top podium platform, also 40 mm thick, was created at a 15° angle and 1150 mm (about 45”) above the ground, which is a height that should be appropriate for those of average height. However, the highest part of the podium is at approximately 57”, so the podium would need to be scaled down in order to fit on the 4’x4’ build platform on the LF3DP.

Between each of the shelves, a void space designated as an obstacle geometry was created flush against the back of the podium and with a parametrized border, initially set to 75 mm, along the front and sides of the podium. This obstacle geometry ensured that no support structures would infringe upon the shelves, keeping them open and available for use as storage. In the preliminary design, a 75 mm panel on the entirety of the front of the podium was created as a preserved geometry. This had the multifunctional purpose of acting as a support structure and concealing the contents of the podium shelves from the audience.

In the generative design workspace, a 25 lb (about 805 lb force) load was added to each of the three shelves, and a 150 lb (about 1410 lb force) load was applied to the top of the podium at a 45 degree angle. These represent the potential loads the shelves can be expected to withstand and a person leaning their body weight onto the top of the podium, respectively. Gravitational force was also included as a load on the entire podium design. ABS plastic was set as the study material, and additive manufacturing was selected as the manufacturing method. The maximum overhang angle was set to 45 degrees, and the minimum feature size was set to 30 mm, as both are design constraints of the LF3DP. The print was oriented to print in the (-) y direction, such that the front of the podium acted as its base. The objective was set to minimize mass, and the minimum safety factor was set to 2.

The first podium design produced in the generative design space was projected to weigh about 115 kg of ABS filament. Because PLA is denser than ABS, the actual print would have weighed even more. In order to reduce the amount of filament used and increase the design flexibility, the front panel was removed as a preserved geometry from the bottom two thirds of the podium. The panel thickness for the top third was also reduced from 75 mm to 40 mm. Additionally, the void area obstacle geometry was removed from the bottom shelf, as it is unlikely this space would be used for storage in actuality, so that this space could now allow support structures. The generative design following these changes had a significantly reduced weight of 64 kg of ABS filament, while maintaining necessary support to withstand the prescribed loads. Plus, these changes allowed for a more visually intriguing design along the front of the panel, with a V-shaped support structure evoking the Vanderbilt logo.

Despite setting the maximum overhang angle to 45 degrees, the form created by the generative design workspace failed to meet this criteria in several places, most notably in bridging support structures across the entire bottom third of the design. These support structures were manipulated using several tools in the Modify Form workspace, including Move, Freeze/Unfreeze, Thicken, Pull, and Extrude, until the overhang angles were in compliance and bridging was minimized. At the time of writing, there remains a small section in the middle third of the podium in which the support structures exceed the 45 degree angle at a bridging distance slightly over 100 mm, but the design was able to successfully print on the MakerGear M3 FFF printer despite this. If this design were to be actually printed utilizing LF3DP, further manipulation would need to be performed to reduce the bridging distance to a greater extent.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e8ce9c0807e5103eb?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## FFF Scaled Down Model
The podium model was scaled down to 7% of its proportions and printed from PLA on the MakerGear M3 FFF printer. At this scale, there was negligible stringing or other print issues involving overhangs. Images of the scaled-down print can be seen in the gallery below.


{% include gallery caption="Large Format 3DP Gallery" %}
