---
layout: project
title: Macadamia Nut Cracker
description: ENGRD 2020 Statics Project
technologies: n/a
image: assets/images/macadamia-nuts.png
---
# Macadamia Nut Cracker Project - ENGRD 2020 Statics
**Skills used: Equilibrium, Solving Mechanisms, Ergonomics and functional requirements, Research**
{% comment %}
<img src="assets/images/macadamia-nuts.png" width="50%" height="50%">
{% endcomment %}
## Find:
Design problem: Imagine you have a macadamia nut that you want to crack open by hand
using a simple lever nut cracker. Design a nut cracker with appropriate dimensions to successfully do this.

## Given:
Inputs: size of macadamia nut, average grip strength, load required to crack macadamia nut.

## Approach
I first researched appropriate values. Taking measuraments from a UN fact sheet [(Link)](https://unece.org/sites/default/files/2025-12/DDP-22-InshellMacadamiaNuts_2025_E.pdf?__cf_chl_rt_tk=SiU2UmhHNwCT5YtbHlciEvC9Hc75zbM53kLXhPOjmRE-1772070993-1.0.1.1-m._g70WAcMCroFbHwOxTeq6XL0f8O1N1DunjdElJFLQ), I found the diameter for macadamia nuts most commonly ranged from 16-28mm. As larger nuts were harder to crack, I chose a diameter slightly higher than the average to work with, 22mm, to enable the nutcracker to better account for all sizes.

Then, I found grip strength values from the website topendsports.com [(Link)](https://www.topendsports.com/testing/norms/handgrip.html). As macadamia nuts are consumed mostly by a younger demographic, Gen Z and Gen X, I took the average grip strength of that age range, 35kg/77.16lb, assuming that most people could reach that value.

Finally, I obtained the average load to crack macadamia nuts from a paper by Schrauf et al [(Link)](https://doi.org/10.1007/s10071-007-0131-2), 22kg/489.43lb.

To calculate necessary dimensions of the nutcracker, it needed to fit the nut while still providing a long enough lever arm to crack it, according to the diagram below.

Nutcracker lever diagram:
![Lever Diagram]({{ site.baseurl }}/assets/images/lever-diagram.png)

With L1 being 3 times the estimated macadamia nut radius, I estimated that the angle should allow a sufficient ease of use and allow for the lever arm to be a reasonable length.

L2 was the total lever arm length in the starting configuration, while L3 and L4 were the distance to the contact point and total length, respectively, for the actual nutcracker.

The "teeth" were also important for the nutcracker in keeping the nut in place, and their height needed to be less than the smallest radius while the distance between them had to be greater than the largest radius. So 5mm was chosen as the height while 30mm was chosen as the width between them. (Note: I accidentally wrote 10mm for the teeth height on the diagram instead of 5mm)

## Calculations
![Calculations](/sp26-portfolio-taidiyue2/assets/images/calculations.png)

I came to the total arm length of 501.46mm, with the nut centered at 79.06mm from the hinge, as shown in the diagram below.

Final diagram:
![Final Design](/sp26-portfolio-taidiyue2/assets/images/macadamia.png)

## Discussion
 This nutcracker is quite large, but as macadamia nuts require several times the load of other nuts, as seen in the paper by Schrauf et al., it is reasonable to expect a similar increase in dimensions from regular nutcrackers. It may be made more efficient by adding a more complex lever mechanism or using actuators, as suggested by the second part of the problem. If actuators were to be used, they would have to be able to reach the 77lb grip strength.

---
Image credits: https://www.ebay.com/itm/285448116474