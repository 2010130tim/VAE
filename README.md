# Models for Infinity Dimensions (MID)

<img src=https://github.com/Bella_cell/VAE/blob/main/doc/MIDLogo.png width=300 p align="right">

The MID project (Machine Learning for analyze high-throughput experimental spectra) aims to produce a machine learning program that can return the physical meaning behind the spectra. Considering the continuously growing research interest in using high throughput experiments in characterizations of newly synthesized samples/materials, tons of spectra data are being conducted, and thus an efficient toolkit for analyzing data is in great need. In this project, the program is built up with an unsupervised machine learning model (analyze data) and a graphical user interface (for dataset determination & output display). The model will lower the dimension of a given dataset and the lower-dimensional representative dataset will be stored in a local file. The users are thus able to access the GUI by specifying peak parameters of interest and the program will return analyzed result based on the reconstruction of lower-dimensional representative dataset to the original dataset.

-----
## Software Dependencies
The MID is available on the web and python is not required. Please see *Interface Instructions* for more information.
For those who would like to run the jupyter and python files, please ensure you have the following:
- Python 3.7
- Python packages listed in `environment.yml`and Installation section.

-----
## Installation
Install and activate the 'MID' environment in your desired directory with the following commands:

`git clone ......`

`cd MID`

`conda env create -f environment.yml`

`conda activate selec`

This enviroment contains the following packages: <br>
- jupyter
- pandas
- numpy
- scikit-learn
- pip
- pip:
  - plotly==5.6.0
  - streamlit

-----
## Organization
```
MID
-----              
```
-----
## Battery Data
The dataset provided in MID is modified from ..... <br>
The data was retrieved from the ..... <br>
To see how spectrum data was obtained, please see `data` directory.

Citation for accompanying publication:



-----
## Graphical User Interface


To run the GUI from local files, follow the instructions in the "Installation" section, then enter the following command from a terminal:

`cd VAE`

`streamlit run VAE.py`

This will return series of URLS on the terminal, which can be copy and pasted into a web browser.

Upon entering the MID interface, there will be ..... Click on the desired parameters, and click the calculate button to start the predictive calculations.


After finishing calculations, the following plots will appear on the GUI........


The user can interact with these plots by:
* Zooming in/out of the image and panning
* Hovering over a point for specific data
* Rotating the 3D plots
* Saving the figure as a png



-----

## Tests
`MID.py` contains all functions from modules in `MID` directory <br>
Change into tests directory and Use the following command to run tests in `MID_test.py`:

`python -m unittest MID_test.py`

-----

## Authors
Bella Wu, Material Science and Engineering <br>
Kim, Material Science and Engineering <br>
Lilo Yeh, Material Science and Engineering <br>
Nick Leu, Material Science and Engineering <br>
William Lin, Material Science and Engineering <br>
