# RobotArmProject

<h2> Description </h2>

This project showcases me designing and building a robotic arm from scratch. It combines my CAD design, the electrical build, and the code I used to operate the arm. 

This project allowed me to develop my mechanical design skills, alongside learning more about servo movement and coding.

# Software used

- SolidWorks
- Python
- C++ / Arduino IDE

# Complete Arm

<p allign='centre'>
<img src="Images/FinishedRobotArm.png" width="350">
<img src="Images/ControlPanelLayout.png" width="400">
<br>
<em> Finished Arm </em>
</p>

# Parts designed

<p allign='centre'>
<img src="Images/WholeArmAssembly.png" width="400">
<br>
<em> Finished Arm </em>
</p>

<h3>Base</h3>

The base holds the bottom servo, which controls the rotation of the whole arm. Inside this base the servo horn is attached to and drives the lower side of a sun gear, in my planetary gear box. 

<p allign='centre'>
<img src="Images/Base.png" width="300">
<img src="Images/BaseSchematic.png" width="300">
<br>
</p>

<h3>Planetary Gear Box Mechanism</h3>

This gear box includes a sun gear, 3 planet gears and an outer ring gear. This multiplies the torque of the servo by 5, allowing for easy rotation of the arm. The linkage that connects the planet gears output is connected to the under side of the base servo mount through a lazy Susan bearing.

<p allign='centre'>
<img src="Images/PlanetaryGearboxSchematic.png" width="300">
<br>
</p>

<h3>Gear Box Lid</h3>

<p allign='centre'>
<img src="Images/PlanetaryGearBoxCap.png" width="300">
<img src="Images/PlanetaryGearBoxSchematic.png" width="300">
<br>
</p>

<h3>The Base Servo Mount</h3>

This base holds 2 servos either side, rotating in different directions. The first linkage sits between these.

<p allign='centre'>
<img src="Images/BaseServoMount.png" width="300">
<img src="Images/BaseServoMountSchemetics.png" width="300">
<br>
</p>

<h3>The First Linkage</h3>

The first linkage rotates from the base servo pair.

<p allign='centre'>
<img src="Images/Linkage1(View1).png" width="300">
<img src="Images/Linkage1(View2).png" width="300">
<img src="Images/Linkage1Schematics.png" width="300">
<br>
</p>

<h3>The Second Linkage</h3>

The second linkage is driven by a servo connected to the first linkage. On the other side there is a bearing that allows for smooth rotation around that axis.

<p allign='centre'>
<img src="Images/Linkage2(View1).png" width="300">
<img src="Images/Linkage2(View2).png" width="300">
<img src="Images/Linkage2Schematic.png" width="300">
<br>
</p>

<h3>The Third Linkage (Wrist) </h3>

This linkage holds 2 servos, one being to point the wrist up and down, and the other on the end to rotate the claw. There is also a bearing on the other side of the wrist. 

<p allign='centre'>
<img src="Images/Linkage3.png" width="300">
<img src="Images/Linkage3(View2).png" width="300">
<img src="Images/Linkage3Schematic.png" width="300">
<br>
</p>

<h3>Claw Mechanism</h3>

The claw design involves using 2 interlocking linkages that force the jaws to close together. The gear linkages use a smaller servo (SG90) compared to the rest of the arm.

<p allign='centre'>
<img src="Images/ClawAssembly(View1).png" width="300">
<img src="Images/ClawAssembly(View2).png" width="300">
<img src="Images/ClawAssemblySchematic.png" width="300">
<br>
</p>

<h3>Leg</h3>

<p allign='centre'>
<img src="Images/Leg.png" width="300">
<img src="Images/LegSchematic.png" width="300">
<br>
</p>

# Python code

