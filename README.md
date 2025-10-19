# Animated Ornithopter Mechanism Design
*A SOLIDWORKS Project for Simulating Bird-Like Flight*

This project documents the design, assembly, and simulation of a mechanical ornithopter (bird-like flapping mechanism) using spur gears and linkages, built entirely within SOLIDWORKS.

## 🛠️ Project Overview
The primary goal is to simulate a dynamic, bird-like flapping motion. The design is built from the ground up, starting with standard SOLIDWORKS Toolbox components and incorporating custom-designed parts to complete the linkage system.

* **Software:** SOLIDWORKS
* **Mechanism:** Spur gear drive with a 4-bar linkage system
* **Simulation:** SOLIDWORKS Motion Study

## ⚙️ Design & Component Creation

### Gear Setup
* The drive train begins by inserting **spur gears** from the SOLIDWORKS Toolbox.
* Key gear parameters (e.g., number of teeth (45), module, width) are customized to meet the design requirements.
* A critical best practice is followed: library components are saved as new parts and **never modified directly** to prevent corrupting the standard Toolbox.

### Custom Components
* New parts (like linkages and the chassis) are created by **converting gear sketches** and using extrusion features.
* Support features like holes are added for pins and axles.
* All components are designed **without external references** to ensure assembly integrity and prevent broken mates.

## 🔧 Assembly Techniques
* **Gear Mates** are applied to the spur gears to simulate realistic rotational motion.
* A custom chassis is designed and added to support the entire gear mechanism and linkage assembly.
* The **Mirror Components** feature is used to create the symmetric second wing, saving time and ensuring accuracy.
* Mating issues are carefully resolved to ensure the mechanism moves freely without conflicts.

## 🎞️ Animation & Motion Study
* A **Rotary Motor** is added to the main drive gear to power the simulation.
* Motor parameters (RPM and direction) are adjusted to achieve a realistic flapping speed and movement.
* The **Motion Study** feature is used to calculate the motion, animate the full mechanism, and validate the kinematic design.

## 💡 Tips & Best Practices
* **Warning:** Always avoid direct edits to standard library parts. Save them as new parts first.
* **Recommendation:** Be meticulous with mates and constraints. Over-defined or incorrect mates are the most common source of assembly errors.
* **Explore:** Viewers are encouraged to explore additional tutorials for deeper learning on advanced mates and motion analysis.
