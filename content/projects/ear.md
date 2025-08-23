---
title: "EBME 370/380 - Unobtrusive Ear-EEG for Long-Term Seizure Monitoring"
date: 2025-05-31
draft: false
# author: "Gurusabarish"
tags:
  - Arduino
  - SOLIDWORKS
  - Machine Learning
image: /img/EAR/overall.jpg
description: ""
toc: 
--- 

## EBME 370 - First Iteration
As a part of my senior project, my group designed a unobtrusive and discreet device that allows individuals with temporal lobe epilepsy (TLE) to passively collect EEG data and store it to and SD card. This device could allow for more accurate assessments, so clinicians can more effectively manage patient conditions, prescribe medication, and detect TLE events.​

We considered a total of 43 functional specifications pertaining to the device components and their composition, and realized measurable technical specifications from there. Of those specifications, we emphasized discreetness, durability, user comfort, obstructiveness, and ease of use.

 <mark>The device was initally split into 3 sections:</mark>
  1. Ear Piece
  2. Machine Learning Algorithm
  3. Electronic Components


{{< figure src="/img/EAR/ear_design.jpg">}}

As the CAD lead for the team, it was my job to design the over-the-ear device casing to achieve comfortability, durability and overall material biocompatability.

The design needed to fit around an average-sized ear, and also have space for electrodes to be caputred in the device casing. 
{{< figure src="/img/EAR/ear1.JPG">}}
<!-- {{< figure src="/img/EAR/ear2.jpg">}} -->

After researching anthromophoric dimensions of ear lobes and mastoid bone, as well as taking a survey of students in my class by measuring their mastoid bone to inform my model. The approach I took to modeling the device casing was to have the medial surface contacting the skin capture the mastoid bone and the anterior surface model the mastoid bone as is protudes from behind the ear.
<!-- {{< figure src="/img/EAR/IMG_0486.jpg">}} -->
{{< figure src="/img/EAR/IMG_0488.jpg">}}

We decided to print the first prototypes in ABS, as it satisfied the durability constraints we set while also being biocompatible. Later on we switched to PETG because it was researched to be a better material for devices coming into contact with the skin and bodily fluids. We also experimented with painting the casings in different skin toned coatings to make it more discrete.

{{< figure src="/img/EAR/jay.jpg">}}


## EBME 380 - Second Iteration
To iterate upon our previous work, we decided to revamp our system architecture by packaging the electronics subassembly inside the device casing to improve user comfortability and reduce complications due to exposed wiring along the back of the neck.
{{< figure src="/img/EAR/ear_design_2.jpg">}}
The device casing itself was also redesigned with the new packaging constraints for both the left and right ear lobes. Utilizing similar surfacing techniques and itterative fitment tests as was done in EBME 370. A connective band was also added to connect the two device casings and cover exposed wiring.
{{< figure src="/img/EAR/ear3.jpg">}}
<!-- {{< figure src="/img/EAR/ear4.jpg">}} -->
The final design was printed using Flex PLA and the electronics were installed via the clamshell like opening that occurred when opening the device casing rather than the previously shown pocket design due to prototyping constraints.
{{< figure src="/img/EAR/overall2.jpg">}}
{{< figure src="/img/EAR/jay2.jpg">}}