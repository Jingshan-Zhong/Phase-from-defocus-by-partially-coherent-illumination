# Phase-from-defocus-by-partially-coherent-illumination


****************************** INTRODUCTION**************************
This code is used to recover phase and source for partially coherent defocus stack. The code is only for academic and nonprofit use. 

The Input parameters:
Ividmeas: defocused intensity stack measured along the propagation axis
z: the positions of the measured intensity images [m]
ps: pixel size [m]
lambda: wavelength [m]
nfocus: the index of images which is focused
NA_obj: NA of objective lens

parametere for running of GPU:
IsGPUprogram=1; %choose whether run on gpu. 1 = yes; 0 = no.

 
Output:
ahatOriginal：Recovered complex field
EstSourceOri：Recovered source

ahat0: low-pass filtered version of recovered complex field
EstSource：low-pass filtered version of recovered source
ps_source：pixel size of source (unit: NA)

Experimental Data:
A example of the defcous stack of partially coherent illumination, measured on microscope by experiment, could be downloading
from this dropbox link:
https://www.dropbox.com/s/xy7cxuictuxliaa/MFC10PC0228Medium.mat?dl=0

