---
title: "CU AUV"
layout: fullwidth
sitemap: false
permalink: /cuauv/
---

## UHPV (Orion's Pressure Vessel)

*Designed Fall 2024, Fabricated/Assembled Spring 2025*

{% include figure.html src="cuauv/Orion_Full.png" alt=" " caption="The full CAD assembly of Orion's UHPV, the main pressure vessel of the AUV. It housed all of the electronics of the AUV (including a Jetson Nano and a ZED stereo camera) and has two panels on the port and starboard sides with bulkheads to connect to all the external devices on the AUV. I designed the UHPV in the fall of 2024 and assembled/leak tested it in the following spring (2025)." position="full" width="450px" %}

The Upper Hull Pressure Vessel, or UHPV, is one of the most critical components of our team's AUV. While other external components of the sub are modular and can easily be removed or attached while testing, the UHPV houses all of the electrical boards and it thus needs to be on a strict testing timeline and perform reliably.

{% include figure.html src="cuauv/Sirius_Internals.png" alt=" " caption="The UHPV of Sirius, the previous AUV, which I spent hours leak testing at our local pool prior to Robosub 2024." position="left" width="300px" %}

Sophomores on CU AUV usually are assigned to less mission-critical components of the sub, but during the previous spring, I had spent a lot of time helping to leak test the UHPV of the previously designed sub, Sirius. I was able to discover the source of the leaks (microfractures in the welds of the aluminum plates), but more importantly, became very familiar with its other sealing surfaces and what made it inconvenient to work with. I also found out from designing my previous enclosure (for the downcam) that the team did not have a consistent guide for designing and machining o-ring grooves, and everyone interpreted the Parker O-Ring Handbook differently. Thus, I was entrusted with designing the next UHPV, and made it my goal to improve our understanding of o-ring seals.

{% include figure.html src="cuauv/Orion_FOS.png" alt=" " caption="A pressure simulation for the Orion UHPV, done in Solidworks. At a depth of 10 meters, the factor-of-safety is still over 2.2." position="right" width="300px" %}

When designing the new UHPV for Orion, our next AUV, I prioritized making a quick design cycle, so I avoided any major aesthetic changes and focused instead on optimizing what already worked well. I was able to significantly reduce the weight of the pressure vessel by condensing the UHPV to a smaller footprint and changing the acrylic supports on the lid. I carefully computed all of the o-ring math, and had others check my work during design reviews. Since we wanted to accelerate our overall team timeline, I also opted to use subtractive manufacturing for the entire UHPV, and made many drawings to outsource most of its production. I was careful to specify tolerances and surface finishes, and outside of one accidental through-hole (which epoxy was able to fix!), we had the UHPV machined and ready for integration over a month ahead of the previous model.

{% include figure.html src="cuauv/Orion_LeakTest.JPG" alt=" " caption="The new Orion UHPV being prepared for its first leak test. Each sealing surface is surrounded with blue shop towel to make leaks easier to identify and locate." position="left" width="300px" %}

After all parts of the UHPV were sent out to be anodized, it was time to be integrated and leak tested. Learning from testing the previous year, I taped shop towel around every bulkhead and sealing surface before deploying the pressure vessel into the pool. This way, it would become more easily apparent which seal had failed, and avoid "guessing" at where the problem is. In the end, the careful design choices made a big impact, as the UHPV had passed an overnight pool test on its first try, rather than the 2+ weeks it took before.

{% include figure.html src="cuauv/Orion_Askew.JPG" alt=" " caption="Orion at its first leak test, desperately needing to be balanced." position="right" width="300px" %}

In the meantime, I also created an entirely new sealing guide for the whole mechanical subteam on our internal wiki website. The previous guide was created in 2008 and had largely been forgotten about, so a set standard was desperately needed. I spent hours scraping through the Parker O-Ring Handbook, learning more of the "why" behind certain dimensions so that I could make modifications that made sense for our particular application. For example, a lot of our machining is still done on manual machines, where it can be hard to obtain tolerances tighter than 2-3 thou. However, our seals are not under much pressure, and we do not need to worry about o-rings being pulled through larger clearance gaps. So, I created entirely new charts for face and bore seals that opened these tolerances (in the correct ways) to make machining faster and have less rejected parts.

{% include figure.html src="cuauv/Orion_From_Ground.jpg" alt=" " caption="A picture of me working on Orion, adjusting the floats I had cut to fit into pockets of the aluminum frame." position="left" width="300px" %}

The mechanical subteam worked quickly to integrate the frame, thrusters, and other key components of the sub so that it could begin its first live tests. Although we can model all of the materials in Solidworks and obtain the center of mass/buoyancy for our sub, it is difficult to model all of the SEACON cables that are connected, and thus often our initial calculations are off. When we first put Orion in the water, it heavily favored its backside. However, we regularly need to add floats and counterweights to our subs to balance them, which we added at the following pool tests until the sub was level without needing help from the thrusters.

I thoroughly enjoyed working on this project, as it was a nice challenge for me. I got to run simulations, make proper drawings to outsource a complicated part, and successfully made improvements to a design that had some tricky flaws. My o-ring guide has also already been adopted by new members of the team, so it is nice to know that a side project I spent a lot of time on will be a valuable resource for years to come.

## Summer Lead, RoboSub 2024 (3rd Place Overall)

*May 2024 - August 2024, Competition Week August 5-11*

{% include figure.html src="cuauv/Competition_TeamPic.PNG" alt=" " caption="A picture of the CUAUV summer team at the RoboSub 2024 competition. Only a handful of members, mostly freshman, stayed in Ithaca during the summer to conduct the final assembly of our AUVs and travel with them to competition. I was responsible for coordinating our in-person teams with other members who were remote, and made many time-sensitive decisions at Robosub which earned us 3rd place overall." position="full" width="450px" %}

Following my first year on the CU AUV team, I stayed in Ithaca over the summer to help prepare our AUVs (Sirius and Polaris) for our main competition, Robosub, in August. Most of our members (especially the leadership team) had internships and other jobs elsewhere in the summer, so it was primarily the responsibility of our team's freshman to get the last leg of work done on the AUVs with remote help. Because no older members were able to be in Ithaca for the full summer, I was selected to be the summer lead/team coordinator, responsible for reporting the current status of our AUVs throughout the summer, connecting remote leadership members with the team as problems arose, and executing "game-time" decisions at the competition itself to help our team perform the best.

{% include figure.html src="cuauv/Overnight_Pool.png" alt=" " caption="A picture of me struggling with Sirius at an overnight pool test during Robosub 2024." position="left" width="300px" %}

Due to an onslaught of technical difficulties in upgrading our latest sub (Sirius) to a new computer (Jetson Orin Nano), our team was significantly behind our expected timeline developed in the fall. Sirius had yet to be fully mechanically assembled, and had not run on its own power in the water yet. At the same time, our in-person team found it difficult to keep up with our extensive pool-testing schedule, and felt that their workload at the beginning of the summer would not be sustainable. I had many small group and one-on-one calls with our remote leadership team to express our concerns and find a balance between catching Sirius back up to speed and letting our in-person team have time to rest and enjoy some time off during their summer. Through unexpected electrical shorts, stuck camshafts, and even a rogue tornado during a pool test, we were able to make it to August with both subs in mostly-working condition.

{% include figure.html src="cuauv/Sirius_OnBed.png" alt=" " caption="Our team working on reassembling Sirius on a hotel bed at competition." position="right" width="300px" %}

Robosub 2024 did not start out smoothly for out team, to say the least. Due to some issues when shipping our AUVs and all of our equipment, everything we needed to compete arrived over 24 hours late. In addition, certain key electrical components (such as the IMU for Polaris and SEACON cables needed to connect enclosures to the UHPV) had been marked off as packed when they never left Ithaca. Having to make some quick decisions, we decided to only focusing on getting Sirius reassembled and up-to-speed for our main competition runs, as we had limited time and manpower to prepare for a deep run in the competition.

Rallying the team's morale took some effort, but we were able to qualify Sirius for the semi-final round leg of Robosub and performed well at our presentation and vehicle assessment. We still had some lingering issues (mainly that communication with Sirius was inconsistent through our tether and our vision modules were struggling with the glare off the surface of the water), but were able to score on the majority of obstacles and tasks under the water. Our team split into two groups, one waking up early to book our practice slots at 6am sharp, while the other worked late into the night with Sirius in the hotel pool during our allotted 10pm-2am hours. I helped to coordinate efforts between our two teams, even as I battled an ear infection which appeared just as our equipment had finally shipped. 

{% include figure.html src="cuauv/Sirius_CompRun.jpeg" alt=" " caption="A picture of me and a teammate ready to deploy Sirius for its first semi-final run." position="left" width="300px" %}

Our technical difficulties continued through the semi-finals. It was becoming more apparent that our tether cables were degrading, and reprogramming Sirius during our final runs was nearly impossible. If we wanted to update anything on our Jetson, we would have to quickly open the lid of the UHPV, plug directly into the Jetson's USB-C port, and carefully seal the lid back up. Our first semi-final run was a bit of a catastrophic failure (we scored less than half the points we had in most of our practice runs), which gave us a little less than 24 hours to gear up for one last try. Our vision models were simply unable to see most of the game elements and timed-out on too many tasks. By relying more on dead reckoning, and precisely mapping out the layout of the game elements prior to our last run, we were able to qualify for the finals alongside 6 other teams.

{% include figure.html src="cuauv/Competition_AwardPic.JPG" alt=" " caption="Our third-place award received at the end of our competition. Given our onslaught of challenges, we were extremely proud of our performance!" position="right" width="300px" %}

Our last-day finals run was nothing short of magical. We knew that if we wanted to make podium, everything that Sirius had shown it could do would have to go right, and even then we still would need some luck on top of that. Well, as our sub was attempting to surface in a particular area of the pool, a game element had gotten stuck inside the frame of the sub and fell into a bin, scoring a huge amount of points for the manipulator task that we had given up at the start of the week. After our last run, our sub refused to even boot normally, but it didn't matter. We had secured 3rd place, and earned our team a cash prize of $2,500.

This summer had been one of my biggest challenges as a leader. Since there were so many problems that had cropped up prior to and during competition, and it was difficult to catch our remote leadership members up to speed on every obstacle as they arrived, plenty of confusion and tension was understandably generated between team members. The role really challenged my skills as a communicator and negotiator, helping everyone to feel respected and heard even when it would be tempting to assign blame to others when things didn't go right. Though we had really big aspirations for our new sub when we first designed it, we were able to rise to the occasion and perform the best we could given the circumstances, which felt rewarding in its own right. I helped everyone to recognize how much effort each individual on our team had put in, and the critical role each person played in making our success story. 

## Downcam Enclosure

*Designed Fall 2023, Fabricated/Assembled Spring 2024*

{% include figure.html src="cuauv/Downcam_Full.png" alt=" " caption="A rendering of Sirius's downcam enclosure, designed to enclose a IDS UI camera up to a depth of 10 meters. It has two outgoing cables (for data and power), and fit snugly beneath the main pressure vessel of Sirius. The camera enabled the AUV to see tasks beneath it, dropping and picking up game pieces in specific locations." position="full" width="450px" %}
