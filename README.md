# PCDH19_ZebraExplore

## General Information  
Collaborative effort by the Ratto lab to analyse ephys data. 

## Use in PCDH19 project
This version is the version I used in all my analyses of LFP data during my thesis work on PCDH19. 
Specifically I:
1) Calculated RMS signal strength in various band passes
2) Detected up states and calculated some of their metrics, such as up state slope
3) Detected presence of beta oscillations and hypersynchronous peaks
4) Detected high frequency units

## Usage
The main program to run is ZebraExploreApp, from there all other scripts are called if needed. It is possible to import a variety of ephys data formats,
add band pass filters to the data, find the RMS strength of the data in various band pass filters, calculate the power spectrum, detect up states and 
find up states metrics, extract 'single unit' activity, inspect the data, visualise the spectrogram, and many more features. 

## Contributors
Gian Michele Ratto, Enrico Pracucci, Gabriele Nardi, and me.
The scripts abfload.m, allegoXDatFileReader.m, edfread.m, findpeaks.m, and inputdlgcol.m were already existing Matlab functions (not written by us).

## Dependencies
Zebra requires the chronux package to run (Bokil et al. 2010), as well as the Signal Processing Toolbox.