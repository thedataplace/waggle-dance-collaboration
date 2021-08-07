# waggle-dance-collaboration

## Contents

### Motion detection

* Detects areas of a screen that change from frame to frame
* Basic image processing using opencv-python free library

### Binary classification

* Detects if a specific bee is carrying pollen
* KLOE abandoned: all bees incoming should be carrying pollen so this analysis is redundant

### Bee tracker

* Draws a line on the video showing where an individual bee has gone

### Optical flow

* Outputs a visual map showing where individual bees have gone

### Particle image velocimetry 

* Creates a vector map of bee movements in the frame
* Exploration of PIV as a way of tracking individual bee movements.
Works well with stock footage from US observation hives but was found to have 
issues when applied to footage from the Plymouth hive due to reflections in the viewing window.

### Assets

A few image assets for testing and debugging code.
