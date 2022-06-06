# Models for Infinity Dimensions (MID)

<img src=https://github.com/Bella-cell/VAE/blob/main/doc/MIDLogo.png width=300 p align="right">

The MID project (Machine Learning for analyze high-throughput experimental spectra) aims to produce a machine learning program that can return the physical meaning behind the spectra. Considering the continuously growing research interest in using high throughput experiments in characterizations of newly synthesized samples/materials, tons of spectra data are being conducted, and thus an efficient toolkit for analyzing data is in great need. In this project, the program is built up with several unsupervised analytical methods, including PCA, funtional PCA, tangent PCA and VAE. These mothods will lower the dimension of a given dataset and produce plots of new low-dimensional spectrum. Therefore, it will make it easier for users to understand the physical meaning of the orginally complex data. Moreover, by adding and minusing one standard deviation of each newly generated spectrum, the user will be able to observe new features of the dataset.

-----
## Software Dependencies
For those who would like to run the jupyter and python files, please ensure you have the following:
- Python 3.7
- Python packages listed in `environment.yml`and Installation section.

-----
## Installation
Install and activate the 'MID' environment in your desired directory with the following commands:

`git clone ......`

`cd MID`

`conda env create -f environment.yml`

`conda activate MID`

This enviroment contains the following packages: <br>
- jupyter
- pandas
- numpy
- scikit-learn
- pip
- pip:
  - plotly==5.6.0

-----
## Organization
```
MID
-----              
```
-----
## spectrum Data
The dataset provided in MID is modified from ..... <br>
The data was retrieved from the ..... <br>
To see how spectrum data was obtained, please see `data` directory.

Citation for accompanying publication:


-----

## Authors
Bella Wu, Material Science and Engineering <br>
Kim, Material Science and Engineering <br>
Lilo Yeh, Material Science and Engineering <br>
Nick Leu, Material Science and Engineering <br>
William Lin, Material Science and Engineering <br>
