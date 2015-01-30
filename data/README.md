#Data Carpentry data

This directory contains the datasets used as examples for the SQL lessons in the lessons directory. Here is a list of the subdirectories and contents.

### Portal mammals data

This is data on a small mammal community in southern Arizona over the last 35 years. This is part of a larger project studying the effects of rodents and ants on the plant community. The rodents are sampled on a series of 24 plots, with different experimental manipulations of which rodents are allowed to access the plots.

**Publication**: S. K. Morgan Ernest, Thomas J. Valone, and James H. Brown. 2009. Long-term monitoring and experimental manipulation of a Chihuahuan Desert ecosystem near Portal, Arizona, USA. Ecology 90:1708.

**Downloaded from:** [http://esapubs.org/archive/ecol/E090/118/]()

**Used in:** excel, shell, R, python and SQL lessons

**Files**

* plots.csv : a list of the experimental plot IDs and descriptions
* species.csv : a list of the two-letter species code and information about the species
* surveys.csv : the full list of observations of species on plots
* portal_mammals.sqlite : a SQLite database of the mammal data; incorporates plots.csv, species.csv and surveys.csv

