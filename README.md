Python environment with an environment.yml
Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mgeorgati/GAN_assignment/master)

A Binder-compatible repo with an environment.yml file.

Access this Binder at the following URL

https://mybinder.org/v2/gh/mgeorgati/GAN_assignment/master




## Setting up the environment

The file [environment.yml] contains a specification of a virtual environment with all the Python modules needed for this course. To get up and running:

1. Create a new environment from the file, either by running `conda env create -f geoanalysis-env.yml` on the command line, or by [importing it in Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#importing-an-environment). This is going to take a while, we are now downloading a bunch of modules and all of their dependencies.
2. Activate the environment by typing `conda activate geoanalysis-env`, then `jupyter notebook`. Alternatively, in [Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#using-an-environment), click the arrow button next to geoanalysis, then choose Jupyter Notebook.
