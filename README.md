This repository provides modified code of PyGazeAnalyzer for Tobii eyetracker 
(I tested it successfully to Tobii Pro Nano.)


Try like this:
1) Run `sideshow/experiment.py` to make raw eye-tracking data file. It will output a `txt` and a `tsv` file.
2) And then, run `analysis.py` to analyse fixation, saccade, blink, etc using `txt` and `tsv` files.


Reference: 

[1] PyGaze: https://github.com/esdalmaijer/PyGaze
[2] PyGazeAnalyzer: https://github.com/esdalmaijer/PyGazeAnalyser
