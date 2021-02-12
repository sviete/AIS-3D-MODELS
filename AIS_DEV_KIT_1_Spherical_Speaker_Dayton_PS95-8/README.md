# AI-SPEAKER DEV KIT 1

The assumption of the project is to make an active speaker whose amplifier is powered from the AIS dom gate (5V available on the AIS dom gate board) and whose audio board will be controlled from the AIS system.

<div align="center">
<img src="https://github.com/sviete/AIS-3D-MODELS/blob/master/AIS_DEV_KIT_1_Spherical_Speaker_Dayton_PS95-8/images/1.jpg" alt="apk image" width="90%"/>
</div>

The design was made with care, and appropriate calculators were used to calculate the speaker capacity. The loudspeaker housing has also been professionally designed. The whole set was also auditioned and properly tuned.
In our opinion, the loudspeaker sounds good and will play nicely on the desk. Bearing in mind the assumptions of the project, we believe that the achieved sound is optimal.
As loudspeakers and sound quality are generally important to many people, we want to point out here that this is not a set for audiophiles or for publicizing mass events. If someone has a delicate ear and feels that the gold-plating layer of the audio cable plug is thin ... then to save disappointment and waste of money on parts for the set (which are not cheap), we suggest looking for another audio solution.

## Model

The speaker was designed in SketchUp.
In the basic version, the SketchUp application is available for free from the browser: https://app.sketchup.com/
The files in the repository with the skp extension are the sketchup format.


## STL (Standard Tessellation Language)

Files with the stl extension can be imported to the free PrusaSlicer tool https://github.com/prusa3d/PrusaSlicer/releases in order to split the model into layers and export to G-code format. G-code is a format that cnc machines and 3D printers understand.

## G-code and Print Settings

To make it possible to print the loudspeaker housing on the Prusa MK3 printer, we divided it into 2 parts. Printing the back of the case (bass reflex) in good quality takes about 15 hours. Filament consumption is about 160g.
Good quality printout of the front part takes less than 27 hours for the Prusa MK3. Filament consumption is about 300g.

**Printer Settings**
Printer Brand: Prusa
Printer: i3 MK2S
Rafts: No
Supports: No
Resolution: 0.2
Infill: 15%
