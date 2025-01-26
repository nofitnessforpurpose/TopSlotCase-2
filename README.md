# Top Slot Case 2
PSION Organiser II - Top Slot Case - With Right Angle Header Support

A 3D Model file of a PSION Organiser II (all family) Top Slot Case 2. The intention to allow design of modified cases and enable part clearance of electronics within the case to be more readily determined. 
This case differs from the <a href="https://github.com/nofitnessforpurpose/TopSlotCase">PSION Organiser II (all family) Top Slot Case</a>, in that it includes support for the smaller headers (See Considerations).

<div align="center">
  <div style="display: flex; align-items: flex-start;">
  <img src="https://github.com/nofitnessforpurpose/TopSlotCase-2/blob/main/images/2024-12-03%20-%20Top%20Slot%20Case%202.png?raw=true" width="400px" alt="PSION Organiser II Top Slot Case. Image copyright (c) 10 August 2024 nofitnessforpurpose All Rights Reserved">
  </div>
</div>
<BR>

[![Organiser](https://img.shields.io/badge/gadget-Organiser_II-blueviolet.svg?%3D&style=flat-square)](https://en.wikipedia.org/wiki/Psion_Organiser)
[![GitHub License](https://img.shields.io/github/license/nofitnessforpurpose/TopSlotCase-2?style=flat-square)](https://github.com/nofitnessforpurpose/TopSlotCase-2/blob/main/LICENSE)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg?style=flat-square)](https://github.com/nofitnessforpurpose/TopSlotCase-2/graphs/commit-activity)
![GitHub repo size](https://img.shields.io/github/repo-size/nofitnessforpurpose/TopSlotCase-2?style=flat-square)
[![Static Badge](https://img.shields.io/badge/format-STEP%20Solid%20Model-blue?style=flat-square)](https://en.wikipedia.org/wiki/ISO_10303)

<br>  
All the files are required for a complete case assembly. The default repository format is STEP (<a target="_blank" rel="noopener noreferrer" href="https://en.wikipedia.org/wiki/ISO_10303"> ISO 10303</a> ) due to its high fidelity.  { STL files are surface geometry as opposed to solid model representations, often containing export processing artifacts }. <br>  
<br>  
<a target="_blank" rel="noopener noreferrer" href="https://www.freecad.org/" > FreeCAD </a> may prove suitable for viewing, handling and, if desired modifying STEP files.
<br>
<br>

## Connector Alignment
Alignment of the connector will require careful attention. For the smallest variant typically available it is likely preferable to solder this component first to a PCB. The author created a jig using a <a target="_blank" rel="noopener noreferrer" href="https://github.com/nofitnessforpurpose/TopSlotSpy">Top Slot Spy</a> and its female connector only, which has had its pins trimmed so as to present a flat lower surface from the bottom of the PCB. The new male header is inserted into the female connector and the new PCB aligned. Guides to keep the PCB square formed from other PCB's may be of assistance to keep the new PCB Square to the jig. Adhesive tape may assist to retain position of various elements. By soldering only the two outer most connections of the header as shown in yellow, taking care not to overheat the assembly, alignment can be subsequently assessed. The PCB is then carefully inspected to verify the achieved alignment.  

<div align="center">
  <div style="display: flex; align-items: flex-start;">
  <img src="https://github.com/nofitnessforpurpose/TopSlotCase-2/blob/main/images/2025-01-26%20-%20Connector%20Alignment.png?raw=true" width="400px" alt="PSION Organiser II Top Slot Case. Image copyright (c) 26 January 2025 nofitnessforpurpose All Rights Reserved">
  </div>
</div>
<BR>
Note the mating female connector pins pre-trimmed on the Top Slot Spy PCB so as to not protrude below the PCB in order to allow placement on a flat surface. The pins of typically available low cost headers are frequently just long enough to align with the bottom of the PCB receiving the header.  
<BR>
Once satisfactory alignment has been obtained the remaining connections can be soldered in place.  

<BR>

## Considerations
The model makes no accomodation for manufacturing tolerances, process or material - see Notes below. 

The original male 8 way 2 row top slot header style connector (marked <a target="_blank" rel="noopener noreferrer" href="https://github.com/nofitnessforpurpose/TopSlotCase/blob/main/images/MXS-70224-02%20(2).jpg">MXS 70224</a>) may have included a custom pin support moulding. Data from a parts list kindly indicated in this <a href="https://www.organiser2.com"> hardware forum</a> seemed to confirm this theory. Readily available 8 way 2 row header connectors tend to have smaller pin support mouldings. The effect of using pin headers with smaller moulding is to permit the PCB to displace vertically in the slot guide channel, resulting in poor alignment with the mating female connector and potential insertion difficulty. There are a number of mitigations, such as changing the height of the male header connector in the PCB and adding material to support the top of a smaller male header pin support moulding. The precise accommodation will depend on your selected pin header moulding.     

<BR>

## Questions / Discussion
See <a target="_blank" rel="noopener noreferrer" href="https://www.organiser2.com/"> Organiser 2 Hardware </a> forum, though see note below first.

<BR>

## Please note:  
All information is For Indication only.
No association, affiliation, recommendation, suitability, fitness for purpose should be assumed or is implied.
Registered trademarks are owned by their respective registrants.
