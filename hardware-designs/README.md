# FILES

The "hardware-designs" folder contains the following folders and contents:

* .../3d-print: Solidworks and STL files for 3D printed version of the vortex whistle
* .../dxf: Drawing files which can be used for laser cutting of the Oilboard and Sticker Paper parts
* .../postcard: Single SVG file with the main oilboard components and QR code for the postcard
* .../solidworks: Solidworks part and drawing files of the whistle components



# DESIGN

## Main Design

The Oilboard Core and Sticker Paper Outlet Skin files comprise the drawings needed for the laser cut components of the low cost vortex whistle. All dimensions were initially based upon the spirocall paper (https://dl.acm.org/doi/10.1145/2858036.2858401), but has been slightly modified through iterations of the project. They generally remain similar to their original dimensions in the Spirocall paper.
\
\
In order to created a more streamlined process for users, the postcard design contains all needed pieces in a single image file (an example can be found at ".../postcard/postableSpirometry.svg"). Additionally, this postcard design could include a QR code which links to an assembly guide to aid users in assembly of the whistle.
\
\
The process of assembly consists of taking the oilboard core pieces and putting them together in the same shape as a 3D printed vortex whistle model. To tape pieces together and seal connections to be airtight, use waterproof medical adhesive tape (very thin, flexible, amazon link below for reference). The sticker paper is used to seal the outlet of the whistle and join it to the top face of the whistle (labelled base 3).


## Components

The oilboard core is the primary structure for the whistle. It consists of the following parts:

* Base 1: Main section/body of the whistle which is folded into a cylidrical shape, joining the 35mm sides.
* Base 2: Lower face of the whistle which joins to base 1. No internal circle.
* Base 3: Upper face of the whistle which join to base 1 and the outlet. Has internal circle for outlet.
* Outlet: Outlet nozzle which sits on top of base 3. Fold to join the 27mm sides
* Inlet: Inlet nozzle with tabs to fold outward to seat better in the main whistle body, and also create the needed angle for the entering air. The two thinner tabs are to be joined together when folding the inlet and face the top of the whistle when the inlet is seated in base 1 (through the small hole cutout).

The sticker paper skin for the outlet replaces a thin tape seal on the outlet, and also has tabs which are folded back during construction. When joining base 3 and the outlet, these sticker paper tabs hold both pieces together, before the thin tape is added on top for a better air seal. 


## Materials

The following information is additional information in regards to the material and laser cut settings used in the project:

* Oilboard: N/A
* Sticker paper: PPD-36
* Laser Cutter: Epilog Laser Cutter

### Epilog Laser Cutter Software Material Configurations:

Oilboard Settings: Oilboard vector preset: 
* Power: 50
* Speed: 45  
* Frequency: 5

Sticker Paper Settings: 
* -Power: 100
* -Speed: 65  
* -Frequency: 5

### Other Materials Notes

Ensure that the glossy side is facing down on the laser cutter (the paper side should face the laser beam). This helps to ensure the cut goes through properly.


Amazon Link to waterproof medical adhesive tape: https://www.amazon.com/Transparent-Adhesive-Waterproof-Bandages-Dressing/dp/B08CXMCPG7/ref=sr_1_15?keywords=medical+tape+waterproof&qid=1692652463&sr=8-15
