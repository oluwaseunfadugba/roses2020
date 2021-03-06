# roses2020
File Repository for ROSES2020

ROSES = Remote Online Sessions for Emerging Seismologists. ROSES was conceived by the leadership of the Seismology Section of the American Geophysical Union, and ROSES 2020 is organized by Fransiska Dannemann Dugick and Suzan van der Lee. The school is targeted towards advanced Ph.D. students, who have used Python before and are familiar navigating in Linux/Unix. Lectures cover topics at the intersection of Seismology and Data Science. 

Recorded lectures are hosted on the IRIS website: https://www.iris.edu/hq/inclass/course/roses while this repository serves to maintain data exercises and lectures for the seismology community as a whole.  


Summer School Topics and Instructors:

6/25 (Th) ObsPy Sydney Dybing, U. of Oregon

7/2 (Th) Data and Metadata Emily Wolin, USGS

7/9 (Th) Time Series Analysis German Prieto, U. Nacional de Colombia

7/14 (T) Waveform Cross Correlation Elizabeth Berg, U. of Utah

7/21 (T) Array Seismology/Network Analysis Stephen Arrowsmith, S. Methodist U. 

7/28 (T) Polarization Analysis Tolulope Olugboji, U. of Rochester

8/4 (T) Machine Learning Zachary Ross, CalTech

8/11 (T) PyGMT Liam Toney, U. of Alaska Fairbanks

8/18 (T) Inversion, Bayesian Steve Myers, L. Livermore National Lab

8/25 (T) Inversion, kriging Tony Lowry, Utah State U.

9/1 (T) Inversion, gridding (and/or tomography) Suzan van der Lee, Northwestern U.

## Authorship
Individual unit lectures and data exercises are produced by the respective instructor.  This github repository is maintained by Fransiska Dannemann Dugick

## Installation
A .yml file is provided in order to create a python environment for running data exercises.  This environment can be created by running:

```
conda env create -f roses_env.yml
```

If this command executes correctly and finishes without errors, it should print out instructions on how to activate and deactivate the new environment:

To activate the environment use:

```
conda activate roses
```

To deactivate the environment use:

```
conda deactivate
```
