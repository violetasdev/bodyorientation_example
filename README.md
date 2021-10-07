# Body Orientation Illustration

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/violetasdev/bodyorientation_example/HEAD)

This repository contains data and code that reproduces a single figure from the paper:

*Sosa, V., Schwering, A., (2021): Detecting social spaces with depth cameras: evaluating location and body orientation as relevant social features. IPIN 2021: 11th International Conference on Indoor Positioning and Indoor Navigation.* (To be published)

## About
We propose a system that uses infrared depth cameras to anonymously derivate body orientation from skeleton joints. The direction of the shoulders and spine, together with the face orientation and the temporal information on occupants' walking trajectories, is used to calculate the body orientation from which socially occupied space is identified. In a user study evaluating the system, we collected data in 32 patterns within two distinct cases: individuals and dyads and assessed the system's accuracy.

The evaluation included the intended orientation and the socially accepted orientation. Our algorithm to detect body orientation contributes to the automated detection of socially occupied spaces.

## Data availability and software
In this repository, you will find:
- *A single dataset for a post-processed body orientation.* From the set of evaluated body orientations (frontal, back, frontal diagonal left and right, back diagonal left and right, side right and side left), we accessed the post-processed joints and evaluated body orientation from Frontal Diagonal Left.
- *A Jupyter Notebook.* An interface with the python script to generate the plot for the body orientation Frontal Diagonal Left with the possibility to display the dataset.
- *Environment requirements*. A .txt file with the library requirements for the python environment.

## Usage

There are 3 main ways in which you can use this repository:

- Download the repository. You can open locally in your Jupyter Notebook installation the file 'BodyOrientations.ipynb' by clicking it on the file list. The code is divided into sections with comments. This is likely to fail in the future when software versions change.
- You can click on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/violetasdev/bodyorientation_example/HEAD), this will open an interactive session of Jupyter Notebooks in your web browser. You can then run or update the code. Rememeber any changes to the code will be lost as soon as you close the browser window.

In general, to use the Jupyter Notebook:
- At the top of this README.md file, click on the **Launch | Binder** icon. You will be redirected to the Binder Website.
- Wait until the interface is loaded with the Jupyter Notebook interface.
- In the left panel is possible to access the files. The **data** folder contains the .csv file with the body orientation dataset.
- From the left panel, select the notebook with the extension BodyOrientations.ipynb
- In the right panel, you will find an interactive interface to run the code. Start from the first cell and run every line with the play button.

## License
MIT License
