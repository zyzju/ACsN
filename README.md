ACSN
=====
ACSN (Automatic Correction for sCMOS-related Noise) combines an accurate estimation of noise variation with sparse filtering to eliminate the most relevant noise sources in the images of a sCMOS sensor, approaching the performance of an ideal camera. This near-ideal conditions result in a drastic reduction of pixel-dependent noise in sCMOS images and an enhanced stability of denoising performance at a competitive computational speed.
## Install ##
### Graphic Interface ###
To run ACsN graphic interface:

 - (1) Double-click the ACsN_app.mlappinstall file in the ACsN_matlab_app folder.
 - (2) In MATLAB, go to App>My App and double-click on ACsN_app.

### MATLAB Command Line ###
To run ACsN from MATLAB command line:

 - 1) Add the folder ACsN_code to your MATLAB path (including subfolders).
 - 2) In the command line type help ACSN or run the Sample code script in the Test Images folder to see the code usage.

### ImageJ/Fiji ###
To run ACsN from ImageJ/Fiji follow these steps:

 - 1) Add the ImageJ-MATLAB update site to ImageJ. To see how, look at [here][ImageJ-MATLAB] .
 - 2) Go to Edit > Options > MATLAB and enter the file path for MATLAB licence.
 - 3) Add the ACsN_code folder and subfolders to the MATLAB path.
 - 4) Copy the file 'ACsN_.m' to the folder '<ImageJ installation folder name>\plugins\Scripts\Process\'.
 - 5) Select an open image in ImageJ and then press Process > ACsN from the menu toolbar. To test the program you can use images provided in the Test Images folder.

[ImageJ-MATLAB]: https://imagej.net/MATLAB_Scripting#Prerequisites

