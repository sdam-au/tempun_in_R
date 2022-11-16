# How to use *tempun* Python package within R

---

## Purpose
The purpose of this repository is to provide a tool, that makes it easier to apply python code when working in R. Specifically this repository makes a broad introduction to the R package 'reticulate' and it introduces more deeply to using the python module tempun inside RStudio.

---
## Authors
* Victor Harbo Johnston, Student Assistant, vhol@kb.dk

## License
CC-BY-SA 4.0, see attached License.md

### References
[tempun, https://github.com/sdam-au/tempun]

---
# How to use this repository
I would suggest that you start your exploration of this repository in the file how_to_reticulate.rmd. When you have an understanding of the reticulate package you should move on to use the python tempun module in the Using_the_tempun_package_in_R.rmd. 

In short, this repository can be used to run python code inside RStudio. 

## Sources and prerequisites
The data used in this project is from the EDH (Epigraphic Database Heidelberg) database.
To make these scripts run you will have to know where python is installed on your machine as the rmd file requires you to specify where python is installed on your system. If you are using virtuelenv or conda it is enough to know the name of your environment, when setting up.

### Software
1. R, minimum version 4.0.3
2. R Studio, minimum version 1.3.1093
3. Python, minimum version 3.9.6

### Hardware
1. Computer with multiple-screens
1. Mouse
1. Coffee

---
## Installation

Installation and setup are further described in the R-markdown file how_to_reticulate.rmd. To run the software you need to have python, R and R studio installed on your machine. The python modules used in this script has to be installed with either pip or conda before working with tempun in R. This means that you have to run python on your command line before the script can be used in RStudio. One way to install the python dependencies is to use the requirements.txt file from this repository. This file can be used to install all the python dependencies at once. This is done with:
    
    pip install -r requirements.txt
    
When all the python modules has been installed you are ready to move to RStudio and you do not have to return to your command line interface before you have to install other python modules for some other project you are doing.

---
## Instructions 
1. First, you follow the guide in how_to_reticulate.rmd. Here you will learn how to navigate python inside R Studio
1. Second, you try to follow along with the tempun package in RStudio. If you don't know what the tempun package can do for you, then consult the package information
1. Third, you celebrate that you now are able to write and run code in python and R inside RStudio





