# This package was forked from the owners on October 29th 2019. 
Any updates to this package were made by Bonnie Zuckerman for use in the Concepts and Cognition lab. Find the orginal GazeR package [here](github.com/dmirman/gazer).

## Updates By Bonnie (October 2019)

- Edit to merge_pupil function to replace "." with NAs 


# gazeR:A package to analyze gaze position and pupil size data

For a detailed overview of how to use gazeR, please see the vignettes and posted pre-print (https://psyarxiv.com/gvcxb/). 

<p align="center"><img src="https://user-images.githubusercontent.com/18429968/46034046-472caa80-c0c5-11e8-89c3-ff3f463a1868.jpeg" height="200px" width="200px" />

## Updates (September 2019)

- Read in edf files directly
- Blink/saccades/fixation algorithm 
- Comptability with other eye trackers
- add Binder functionality to run package in the cloud

## Synopsis

This package contains functions for reading in raw eye-tracking data, formatting it for (growth curve) analysis, converting from gaze coordinates to areas of interest, binifying and aggregating data, and various helper functions for GCA and plotting. In addition to gaze-position data, it can handle pupillometric and other time course data.

## Installing Package

``` r
# install devtools
install.packages("devtools")

# install gazer from GitHub
devtools::install_github("dmirman/gazer")
``` 
# Citation
Geller, J., Winn, M., Mahr, T., Mirman, D. (2018). GazeR:A package to analyze gaze position and pupil size data. Retrieved from github.com/dmirman/gazer. 
