# AmphiGlide: A Biomimetic Amphibious Robot

**AmphiGlide** is a capstone Final Year Project focused on replicating efficient natural movement using biomimetic sinusoidal locomotion and undulating fin propulsion. 

This repository documents the hardware development lifecycle, mechanical design principles, and control architecture of the prototype.

## 🛠️ Engineering & Development

### Mechanical & Industrial Design
* **Iterative Design:** The core mechanisms were developed using extensive Computer-Aided Design (CAD) and 3D Modeling. 
* **Simulation:** Computational Fluid Dynamics (CFD) was utilized to inform and refine the complex mechanical linkages required for fluid movement.
* **Rapid Prototyping:** The physical structure and chassis were manufactured using 3D printing to allow for rapid testing and finalization of the drive system.
* **Material Innovation:** To simulate biological fin properties within budget constraints, a repurposed gym mat was utilized. This provided the ideal flexibility and material characteristics comparable to expensive silicone rubber, enabling highly effective undulating propulsion.

### Electronics & Control Architecture
* **Processing:** The core logic and control scripts are orchestrated by a Raspberry Pi 4 working in tandem with an ESP32 microcontroller.
* **Actuation:** The sinusoidal movement is driven by an array of synchronized servo motors.
* **Power Delivery:** The internal architecture features a robust, custom power delivery system utilizing 2 distinct batteries distributed across 4 dedicated power buses.

## 🚀 Testing & Validation
The initial project scope aimed to deploy and test AmphiGlide entirely underwater. Due to unforeseen procurement issues with specific marine-grade components, the testing strategy was adapted. 

The robot's sinusoidal locomotion capabilities were successfully evaluated and validated on land. This rigorous dry-testing phase proved the viability of the core locomotion mechanism, validated the mechanical linkage design, and provided essential data for future amphibious iterations.

## 👥 Team
* **Taimour:** Lead Mechanical & Industrial Design (CAD, CFD, 3D Printing, Mechanism Design)
* **M. Ali Shahbaz Khan:** Electronics Hardware Design, Component Integration, & System Controls
