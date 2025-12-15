---
layout: project
title:  MAE4272 Blade Design
description: Class project with Graphs
technologies: [MATLAB, CAD]
image: /assets/images/windturbine.png
---

### Project overview 

This project was focussed on designing and testing a small scale- wind turbine to maximize power output 
while meeting torque, RPM, stress, and geometry constraints. The blade was intended to operate efficiently 
within the most probable wind speeds determined by the Weibull distribution, while remaining compatible 
with available lab hardware and manufacturing limits. The overall goal was to compare theoretical 
performance predictions to experimental wind tunnel results and evaluate how well simplified aerodynamics 
modesl represent real world behavior. 

### Design process 

The blade was designed using Blade Element Momentum (BEM) theory, with the hypothesis that maximizing
 life-to-drag ratio along the span would maximize power output. The NACA 4412 airfoil was selected for its 
 high Cl/Cd at low Reynolds numbers, and the blade geometry was optimized for average operating conditions 
 (~4.8 m/s wind speed and 1000RPM). Pitch angles were calculated at discrete spanwise locations to maintain 
 an angle of attack near 8deg, and a linearly tapered blade with maximum allowable dimensions was modeled 
 in CAD. Power, torque, and stress predictions were generated to verify that all constraints were satisfied 
 before fabrication and testing. 

 ![CAD Model]({{ "/assets/images/CAD.png" | relative_url }}){: .inline-image-r style="width: 200px"}

### Testing summary

The blades were tested in a wind tunnel across wind speeds from approximately 3-6 m/s using a torque brake 
and LabVIEW data aquisition system. Power and torque were measured by incrementally increaing brake laod at 
each wind speed until the turbine came to a complete stop. Experimental power and torque curves were then 
compared to theoretical predictions. While the blade met all structural and operational constraints, 
experimental power output was roughly 50% of predicted values, and full power curves could not be captured 
at higher wind speeds due to torque brake limitations. These discrepancies highlighted the limitations of
 the simplified, frictionless theoretical model. 

### My contribution

As a group, we equally contributed throughout the design, experimental, and analytical process. I contributed to the inital blade design and experimental process. I planned the preliminary blade 
experimental testing plan and controlled the LabVIEW VI during the actual lab period. I also 
post-processed the collected experimental data to create power and torque curves that were used to compared
to our predicted theoretical models. 

![Power and Torque Curves]({{ "/assets/images/windturbine.png" | relative_url }}){: .inline-image-r style="width: 200px"}

