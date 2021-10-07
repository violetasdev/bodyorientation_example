# Body Orientation Illustration

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/violetasdev/bodyorientation_example/HEAD)

This repository contains data and code that reproduces figures from the paper

*Sosa, V., Schwering, A., (2021): Detecting social spaces with depth cameras: evaluating location and body orientation as relevant social features. IPIN 2021: 11th International Conference on Indoor Positioning and Indoor Navigation.* (To be published)

## About
We propose a system that uses infrared depth cameras to anonymously derivate body orientation from skeleton joints. The orientation of the shoulders and spine, together with the face orientation and the temporal information on occupants' walking trajectories, is used to calculate the body orientation from which socially occupied space is identified. In a user study evaluating the system, we collected data in 32 patterns within two distinct cases: individuals and dyads and evaluated the system's accuracy. 

The evaluation included the intended orientation and the socially accepted orientation. Our algorithm to detect body orientation contributes to the automated detection of socially occupied spaces.

## Data availability and software
In this repository, you will find:
- _A single dataset for a postprocessed body orientation._ From the set of evaluated body orientations (frontal, back, frontal diagonal left and right, back diagonal left and right, side right and side left) we give access to the postprocessed joints and evaluated body orientation from Frontal Diagonal Left.
- _A Jupyter Notebook._ It will generate the plot for the body orientation and display the dataset. 

## Usage
Run the Jupyter Notebook. Each step explains the output and the goal.

## License
MIT License
