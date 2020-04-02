# Content

## standalone-reading-afm-functions

Functions: 

``read_nanonis_experiment``: reads the type of experiment from the header of any nanonis file. Examples:
- 'Experiment' for freq. sweep files
- 'bias spectroscopy'
- 'Z spectroscopy'
    

``read_nanonis_fsweep_header``: read the header of a fsweep file into a python dictionary (f_res (Hz), Phase (deg), Amp/Exc (nm/mV))
    

``read_nanonis_curve``: read the numeric data from ASCII nanonis file

## Examples in the folders

- bias-distance
- freq-sweep
- force-distance
