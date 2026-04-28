# HydroHackathon Indian Institute of Technology (IIT), Madras

https://unstop.com/hackathons/hydrohackathon-iit-madras-1677701

## Problem Statement
Participants are required to develop a computational tool that processes raw ship offset
data and computes key hydrostatic and stability parameters using first-principles numerical methods.
The tool should replicate the core logic of commercial naval architecture software (e.g.,
NAPA) but must be built from scratch, without relying on pre-built hydrostatics libraries.
## Input Data
Participants will be provided with an Excel (.xlsx) file containing the following:
###  Ship offset table (half-breadths at stations × waterlines)
### Station spacing
### Waterline spacing
### Main particulars (e.g., LBP, Beam, Depth)
### Specified draft
### Fluid density (ρ)
### KG (Vertical Center of Gravity)

## Core Task
Participants are required to build a computational tool that performs the following:
## 1. Processes Geometry
• Read and interpret the ship offset table data
• Reconstruct the hull geometry numerically
## 2. Performs Numerical Integration
Using methods such as:
• Trapezoidal Rule
• Simpson’s Rule
• Other suitable numerical schemes
Required Outputs
The computational tool must compute the following:
## • Hydrostatics
– Displacement (∇)
– Waterplane Area (Aw)
– Longitudinal Center of Buoyancy (LCB)
– Longitudinal Center of Flotation (LCF)
## • Stability Parameters
– KB (Vertical Center of Buoyancy)
– BM (Metacentric radius)
– GM (Metacentric height)
## • Stability Curves
– GZ Curve (over a range of heel angles)
– KN Curve (Bonus points)

