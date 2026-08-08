---
title: "Acbotics"
layout: fullwidth
sitemap: false
permalink: /acbotics/
---

## AcSample Production

{% include figure.html src="acbotics/AcSample_CADFull.JPG" alt=" " caption="The full, assembled version of the first production AcSample models. Each unit consists of three separate pumps, each with their own flow sensors, that are fed into external filters chosen by the customer. The entire assembly is mounted to a red baseplate to make it easier to deploy at the desired depth. During the winter of 2025/2026 and the summer of 2026, I helped to refine the pre-production design into scalable, easy-to-assemble product and created lots of internal documentation (assembly instructions, engineering drawings, etc.)." position="full" width="450px" %}

## AcSample Prototype

{% include figure.html src="acbotics/Large_AcSample_Prototype_Full.png" alt=" " caption="The CAD model for an early prototype of the AcSample eDNA sampler. Each unit consisted of a triplicate pump system (housed in the T-joint PVC fixture), the electronics housing (the other PVC tube shown in the back), and the outer metal framing. During the summer of 2025, I was responsible for designing and manufacturing the outer housings for several different sampler prototypes. Feedback received on these helped to shape the production version of these samplers." position="full" width="450px" %}

*May 2025 - August 2025*

One of my major projects as a Mechanical Engineering intern at Acbotics my first summer working there was early prototyping for their in vitro eDNA sampling systems, later named the AcSample. When I first arrived, they had some of the higher-level design choices planned out (ie they had selected particular peristaltic pumps to try out, had chosen the type of flow sensor and tubing that they wanted to use, had some PVC pipes and fixtures on hand), but still had yet to fit everything into housings and make it something that could easily be deployed into the water off the back of a boat or dock. They were also deciding if they wanted to make two different prototype sizes (with different pumping capabilities) to see which size was preferred by customers (or if both had their niches).

{% include figure.html src="acbotics/MakeraCAM.JPG" alt=" " caption="The mounting plate I made for the large eDNA prototype, using MakeraCam." position="left" width="300px" %}

Since the pump system itself and the electronics were going to be housed separately, my first task was to design some sort of outer framing that would connect these PVC housings without being too cumbersome and avoid any tangling of cables. Since each housing was quite heavy, it would be difficult to use 3D-printed parts (especially out of PLA/PETG, which was the main filament we had on hand) that could reliably hold everything together without chipping or snapping. However, I had access to a desktop CNC machine (a Carvera Air) which I had previously used for the PLUTOS Source Box. Although I had only cut acrylic with it before, it was designed to cut into soft metals quite easily, so I decided to make my mounting design an aluminum plate. I made my design in Fusion, then ported it over to the supplied software that came with the CNC machine, MakeraCAM. The software was quite simple (primarily made for 2D contours and basic toolpaths), but was quick and easy to use. The main constraint was space, since the bed size was only 300mm x 200mm.

{% include figure.html src="acbotics/eDNA_Plate.JPG" alt=" " caption="The cut aluminum mounting plate, with a few tabs to file off." position="right" width="300px" %}

The plate was easy to cut, and the rest of the assembly came together quickly. I left one hole in the center that I mounted a thin steel pipe to, which became the carrying handle for the whole assembly. Small L-pieces were mounted next to each hole for the PVC pipes and provided a tab for metal pipe clamps to be secured around each pump housing. Two metal discs were then installed higher-up on the main shaft of the handle, which had slots cut in them so the electronics housing could be attached. Although the full assembly was large (when placed on the ground, the handle was around waist-high), it was balanced enough to be easy to dip into the water.

{% include figure.html src="acbotics/Early_AcSample_Prototype.png" alt=" " caption="The first full prototype, which was the larger of the two designs. The carrying handle made it much easier for customers to deploy. Any metal pipe clamps that were used are not shown." position="right" width="300px" %}

After making the larger prototype, I also made a mounting bracket for the smaller design. The manufacturing process was nearly identical, except that I used Fusion CAM instead of the software provided with the machine. It took some time to get all of the settings configured in Fusion, but Fusion provides a lot more options for toolpaths and was a much more practical option long-term for Acbotics. Since there was no longer a flat, level surface for the assembly to sit on, I added a couple of threaded rods to the side with the electronics housing. This is the assembly at the top of this section.

{% include figure.html src="acbotics/AcSample_Metal_Plate.JPG" alt=" " caption="The plate for the smaller prototype, designed in Fusion CAM." position="left" width="300px" %}

Finally, after designing these two prototypes, I was tasked with making a fixture for the desktop CNC machine that would allow us to more easily machine holes into the PVC caps. Prior to making this fixture, we had been measuring and drilling holes by hand (and using the drill press), which was time-consuming and inconsistent. I made a simple design consisting of a bottom plate and two clamps, and created a generic CAM file with the fixture modeled in (so toolpaths would automatically avoid the fixture or throw errors). After the first few caps were successful, I made two more fixtures for different plug sizes. The holes drilled in these plugs were inlet/outlet ports for each pump or bulkheads for other cables.

{% include figure.html src="acbotics/Machined_transducerCap.JPG" alt=" " caption="A machined PVC cap clamped down using a custom fixture." position="right" width="300px" %}

## PLUTOS Source Box

{% include figure.html src="acbotics/PLUTOS_Source_Box_Assembly.png" alt=" " caption="The full assembly CAD model of the PLUTOS Source Box which I designed as one of my first projects at Acbotics during the summer of 2025. An underwater speaker plugs into the box on the side, and four buttons on the top allow the user to choose what sound to play. The box is IP-67 andhouses a Li-Ion battery, an amplifier, and other electronics. I built four of these units, and they were used for underwater acoustic experiments involving seal calls." position="full" width="450px" %}

