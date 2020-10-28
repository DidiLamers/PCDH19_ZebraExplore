# PCDH19_ZebraExplore
 
Collaborative effort by the Ratto lab to analyse ephys data. This version is the version I used in all my analyses during my thesis work on PCDH19. 

Note that the main program to run is ZebraExploreApp, from there all other scripts are called if needed. It requires the chronux package to run 
(Bokil et al. 2010), as well as the Signal Processing Toolbox.

The scripts abfload.m, allegoXDatFileReader.m, edfread.m, findpeaks.m, and inputdlgcol.m were already existing Matlab functions (not written by us).

Specifically I:
1) Calculated RMS signal strength in various band passes
2) Detected up states and calculated some of their metrics, such as up state slope
3) Detected presence of beta oscillations and hypersynchronous peaks
4) Detected high frequency units