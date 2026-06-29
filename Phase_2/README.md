# Phase 2: Rapid Prototyping & Control Architecture (Months 3 & 4)

Moving from simulation to physical reality, this phase focuses on rapid prototyping using FDM 3D printing, finalizing the structural integrity of the mechanical arms, and developing the core power architecture.

## 📂 Directory Structure

* **`/CAD_Files`**: Refined `.step` files optimized for 3D printing tolerances, including specialized servo housings and linkage arms.
* **`/Code`**: Baseline Python/C++ scripts for synchronized servo actuation and breadboard testing of the control logic.
* **`/Electronics`**: Drafted schematics of the 4-bus power distribution system designed to handle the heavy current draw of the servo array.
* **`/Images`**: Photos of early 3D printed test prints, evaluating material properties (PETG/PLA/ABS) for structural integrity, and electronic breadboard setups.

## 🎯 Phase Milestones Achieved

1. **Iterative Prototyping:** Successfully 3D printed and evaluated the first iterations of the mechanical linkage system, refining slicer settings for optimal layer adhesion and strength under load.
2. **Power Delivery Design:** M. Ali Shahbaz Khan finalized the schematics for the dual-battery setup, isolating the motor power from the logic boards to prevent voltage drops.
3. **Actuation Logic:** Achieved basic synchronized movement across a small test array of servos via the ESP32 microcontroller.
