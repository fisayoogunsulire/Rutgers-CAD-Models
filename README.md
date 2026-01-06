# Research Assets: MOSFET Dynamics in AC Fields

## Project Overview
**Affiliation:** Rutgers University
**Research Context:** Under Professor Shan

This repository contains the mechanical engineering assets designed to assist in experimental research regarding the movement of MOSFETs in aqueous environments under the influence of alternating current (AC) fields.

The primary design challenge was to create stable, buoyant fixtures that could suspend a MOSFET adapter in water while allowing for precise, variable placement of connecting wires (electrodes) in the introduced the AC field.

All designs were created in **Autodesk Fusion 360**.

---

## File Manifest & Design History

The files in this repository represent an iterative design process, moving from initial prototypes to refined experimental fixtures.

### 1. Square Floating Fixture (`Square_MOSFET_Boat.f3d`)
**Status:** Initial Prototype
* **Description:** A rectangular floating chassis designed to hold the MOSFET adapter on the water's surface.
* **Features:** Includes pass-through holes at the bottom of the hull to allow connection wires to travel from the MOSFET adapter directly into the water medium.
* **Outcome:** Served as a proof of concept for the floating mechanism.

### 2. Cylindrical Floating Fixture (`Circle_MOSFET_Boat.f3d`)
**Status:** Improved Design (Recommended)
* **Description:** An iteration on the square design, converting the hull to a circular geometry with increased wall height.
* **Improvements:**
    * **Symmetry:** The circular shape provided better stability and uniform interaction with the water surface compared to the square prototype.
    * **Buoyancy:** Taller walls prevented accidental water intake during experimentation.

### 3. Modular Electrode Bridge (`Extended_ORing_Bridge_v2.f3d`)
**Status:** Experimental Tooling
* **Description:** A mounting bridge designed to sit atop a separate O-ring structure.
* **Function:** This component allows for the precise positioning of the wires connected to the MOSFET.
* **Key Feature:** The design facilitates variable spacing, allowing researchers to adjust the distance between electrodes in the water to test different field configurations.

### 4. Integrated Electrode Bridge (`Extended_ORing_Bridge_v3.f3d`)
**Status:** Refined Tooling
* **Description:** A unified version of the previous bridge design.
* **Improvement:** Instead of requiring a separate O-ring assembly, the O-ring geometry is integrated directly into the print. This simplifies the experimental setup and reduces the number of moving parts.

---

## Usage
* **Software:** These files are native Fusion 360 Archives (`.f3d`). They contain the full parametric design history, allowing you to roll back the timeline to see how the sketches and extrusions were created.
* **Fabrication:** These parts are designed for 3D printing (FDM or SLA). Standard PLA or PETG is recommended for buoyancy, though waterproofing post-processing may be required for the "Boats" depending on print density.

## License
[All Rights Reserved to Rutgers University]
