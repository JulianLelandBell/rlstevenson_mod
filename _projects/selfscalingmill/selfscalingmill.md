---
layout: project
title: Self-Scaling Milling Machine
permalink: /projects/selfscalingmill
subtitle: 
rollover-text:
project-type: engineering
cover-img: JL_w_Machine_w.jpg
images:
 - image_path: /projects/selfscalingmill/JL_w_Machine_w.jpg
   caption:

---

In the spring semester of 2012, I completed my senior design project (known at Swarthmore as my E90), which focused on the design and fabrication of a self-replicating milling machine. Recently, inexpensive digital fabrication tools like the RepRap and ShopBot have made complex fabrication tasks accessible to the hobbyist and maker communities, and have even begun to reach outside of those communities to broader public acceptance. However, there is a significant “manufacturing gap” that this genre of tool does not yet effectively fill – specifically, tools that are capable of high-precision machining of metal and other hard materials. My E90 focuses on designing a machine to fill this gap – a bench-scale, inexpensive milling machine which is cost- and performance-competitive with existing alternatives (Sherline, Taig, Harbor Freight), and is capable of “self-replication” in the same way a RepRap is – it can produce all parts involved in its construction which cannot be easily bought “off-the-shelf” from suppliers like McMaster-Carr, MSC, etc. The ultimate goal of the project is to design a machine which can be replicated by a moderately competent user with access to basic hand tools (including power drills, etc.), and access to an existing machine.

The frame design of this machine is descended from Lindsey’s Tetraform tetrahedral machine tool frame as well as the design of a number of hexapod machining centers: it relies on the innate stiffness of triangles to produce an extremely stiff frame design. The frame is constructed entirely out of commonly available HSS sections – 2.5″ x 2.5″ x .1875″ square tubing, .1875″ x 4″ flat plate, and 2.5″ L x .1875″ angle – and uses structural bolted connections with .5″ Grade 8 bolts. It uses slotted holes to create compliance in the frame: even if one part is not cut precisely to size (basically guaranteed when the user is assumed to be using a hacksaw!), the frame can still be adjusted to ensure that all sides are perpendicular to the top and bottom, all angles are 60 deg., etc.

The spindle that my machine used is a LittleMachineShop X2 Mini Mill R8 spindle. Although I would have strongly preferred to design my own spindle assembly, it is the most economical way I could find to procure a spindle unit AND motor – plus, it’s got a variable speed controller! I also elected to use the z-axis slide assembly from the X2 mini mill, which includes a rack and pinion gear system.

The linear motion system I designed uses 3 HIWIN AWG-15CB bearings, along with standard grade 3/8″-10 Acme threaded rods and nuts. The linear bearings are extremely high-capacity and precise. Unfortunately, they’re also highly intolerant of mounting misalignment, which led to a lot of shimming and fiddling. I designed a backlash-reducing nut housing to allow me to use standard-grade instead of precision-grade hardware (which is much more expensive). Although the thread fit tolerance differs between the two grades, the lead accuracy of the two thread profiles is the same. The backlash-reducing nut assembly, which uses a spring washer to press the nuts against opposite faces of the screw, eliminates the play caused by the looser fit. I’ve included images of the backlash-reducing nut assembly, as well as of the rest of the linear motion system, in the gallery below.

I modeled the entire assembly in SolidWorks. This allowed me not only to easily develop part drawings (which there were a lot of – 41 unique manufactured parts, and almost 100 manufactured parts total), but also to check for interference between parts, and ensure manufacturability. Especially because of the bolted connections into the hollow steel sections used in the frame, manufacturability was a major concern with this project: either the connections had to accessible through the open ends of the frame sections, or internal captive nuts had to be used. The complete Solidworks model (2011 edition) is attached below in a zip archive; if you need different file formats, contact me.

The machine made its first cuts on May 1st, 2012. It’s still very much in the prototype phase: although it was able to successfully drill stainless steel and mill osage orange (a fibrous hardwood), it began to exhibit serious chatter when I tried to do anything more than a skim cut in aluminum. This chatter eventually became so serious that some screws which I had failed to tighten fully began to back themselves out.


I’ve decided to release my project files to the community, so that others can see what I’ve done and build off of it. All files are released under a Creative Commons Attribution-­‐ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-­‐sa/3.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA. Like everything else on my site, the information here is presented as-is with no warranty/guarantee of any sort – use at your own risk.

* [Final Report](/projects/selfscalingmill/E90FinalReportSm.pdf): details design process, and includes part drawings.
* [Part Drawings](/projects/selfscalingmill/PartDrawings.pdf) (standalone PDF. Please note that these drawings are NOT drawn in accordance with standard drafting practices – they were drawn for my personal use, and include horrible abuses of multiple datum points, overly complicated notes, and so forth.)
* [SolidWorks Archive](/projects/selfscalingmill/SelfReplicatingMillingMachine.zip) (includes full assembly and drawings)
* [Milling Force and Power Spreadsheet](/projects/selfscalingmill/MillingForce&PowerSpreadsheet.xlsx)
* [Bearing Force and Moment Spreadsheet](/projects/selfscalingmill/Bearing Load Calculation.xls)
* [Final Presentation](/projects/selfscalingmill/E90FinalPresentation.pdf)
* [IEEE Student Application Paper](http://www.standardsuniversity.org/wp-content/uploads/design_construction_and_characterization_julian_leland.pdf)

This project was generously supported by grants from IEEE-USA and the Philadelphia Chapter of ASME.