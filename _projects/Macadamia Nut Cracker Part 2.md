---
layout: project
title: Macadamia Nut Cracker Deflection
description: ENGRD 2020 Statics Project
technologies: n/a
---
# Macadamia Nut Cracker Project Part 2 - ENGRD 2020 Statics
**Skills used: Beam Deflection Calculations, Inertia Calculations**

<img src="/assets/images/macadamia-nuts.png" width="50%" height="50%">

## Find:
Design problem: For the macadamia nut cracker I designed, calculate location of maximum deflection and then design the lever to deflect less than 2% of length for the applied load, selecting appropriate cross section and material.

## Given:
Inputs: Dimensions of nutcracker lever (501.46mm length), force required to crack nut (489.43lb), required actuator force (77.16lb), deflection limit of 2% of length (10.03mm)

## Approach
I first modeled the lever as a uniform horizontal beam, assuming all loads could be applied perpendicularly to the beam. Then, I found moment equations on A to B and B to C, which could be used to then visualize the deflection pattern. Afterwards, I symbolically calculated maximum deflection, which happens at the unfixed end of the lever.

## Calculations
First, I created a free body diagram of the nutcracker as a beam pinned at one end, assuming all forces applied at a perpendicular angle for max effect.
![FBD](assets/images/leverfbd.jpg)

Then, I used separate FBD's to solve for moment equations and then deflections with the equation EIy'' = M

Moment and deflection equation from A to B:
![AB Moment Calculation](/sp26-portfolio-taidiyue2/assets/images/ABmoment.png)
I solved for y with initial conditions y(0)=0 and y(l) = 0
![AB deflection eqn](/sp26-portfolio-taidiyue2/assets/images/ABeqn.png)

Moment and deflection equation from B to C:
![BC moment calc](/sp26-portfolio-taidiyue2/assets/images/BCmoment.png)
I solved for y with initial conditions y(l) = 0 and y'(l) for AB = y'(l) for BC
![BC deflection eqn](/sp26-portfolio-taidiyue2/assets/images/BCeqn.png)

Although the graphs were hard to visualize I concluded that the maximum deflection would be on the end. 
As such, I calculated the limiting value of EI using the second equation and obtained EI > 2.07N*m
![Final EI calculation](/sp26-portfolio-taidiyue2/assets/images/deflectioncalculation.png)
This value was unrealistic and probably due to a mistake in my calculations. When I solved for the required radius of a steel cylinder with E = 200GPa, I got around 1mm as my answer, which is much too thin to be reasonable.

## Discussion

My I aim to refine my calculations in the near future as I likely had conceptual and algebra errors in my equations.
 

---