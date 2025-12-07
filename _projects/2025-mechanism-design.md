---
layout: project
title: Mechanism Design bold
description: Mechanism To Lift Maximum Weight
image: /assets/images/statics-portfolio.jpg 
---
/assets/images/secondary_design.jpg

__Problem Statement__ design a frame/mechanism to lift the maximum possible weight to the highest possible height. Assume all the supports and bar/actuator are rigid.

**Design Constraints** Given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length, 3 pin supports of which two need to be mounted on the ground, and a linear actuator.

**Degrees of Freedom** 3


I designed a mechanism where the actuator is at an angle theta with the ground, pushing up and right on the rigid bar. Based upon the Tolomatic IMA catalog, I picked the IMA55-RN05 with a peak thrust of 35.81 kN. I found the length of the actuator to be 79.72cm from an equation in the catalog, and theta to be 38.84 degrees. I used the sum of the moments about point A to find that the maximum weight the actuator could lift is 26.13kN. I will be continuing this project and calculations throughout the semester.

**Design Part 2**: For part two of this assignment we were asked to modify our system to no longer assume a rigid beam. We needed to design a cross section and pick a material for our system.

I designed an I-beam cross section, specifically W920X499 to minimize the necessary mass. I picked structural steel to make my beam from, with an elastic modulus of 200GPa. I chose these properties in order to minimize the weight necessary for the beam, and assumed the length and loads were the same as part one of the problem.
