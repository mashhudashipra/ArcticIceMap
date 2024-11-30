# Arctic Ice Map Analysis

This project was performed in 2023 as part of the Scientific Programming with Python course as part of M.Sc. Physics program at Uni Bonn. The purpose of this project is to become familiar with working on image data, plotting it, and combining it in various ways for analysis.

The data used in this problem set was/is collected by two different satellite missions: the AMSR-E instrument on the Aqua satellite (data from 2002 to 2011) and the AMSR2 instrument on the GCOM-W satellite (data from 2013 to-date). 
The data consist of maps of the concentration of ice in the Arctic collected between 2002 and 2022 with the exception of 2012.

The data used here has been saved in the directory "/arcticIceData" in a DropBox folder due to its size (ca. 400mb). This is actually a (small) subset of the complete satellite data set, with only two ice maps every month (some are missing though). The code to download the data from the DropBox folder has been included in the Jupyter Notebook.
The download will run once if the directory is not found. To force a new download, simply delete the previously downloaded directory.

## Install
To run this notebook, make sure to install the libraries listed in the ``requirments.txt`` by running the following command:
- ``pip install -r ./requirements.txt``
