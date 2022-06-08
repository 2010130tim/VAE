# Models for Infinity Dimensions (MID)

<img src=https://github.com/Bella-cell/VAE/blob/main/doc/MIDLogo.png width=300 p align="right">

The MID project aims to produce a machine learning toolkit that can return the physical meaning behind the complex dataset. Considering the continuously growing research interest in using high throughput experiments in characterizations of newly synthesized samples/materials, tons of spectra data are being conducted, and thus an efficient toolkit for analyzing data is in great needed. In this project, the toolkit is built up with several unsupervised analytical methods, including normal PCA, tangent PCA and VAE. These methods will lower the dimension of a given dataset and produce plots of new low-dimensional spectrum. Therefore, it will make it easier for users to understand the physical meaning of the originally complex data. Moreover, by adding and subtracting one standard deviation of each newly generated spectrum, the user will be able to observe more information of the data and even make prediction for their future experiments.

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


- UW Chemical Engineering<img src=https://github.com/Bella-cell/VAE/blob/main/doc/organization_iamge.png width=600 p align="right">
- Clean Energy Institute 
- UW Direct           



-----
## spectrum Data
The dataset is obtained from UV-vis spectroscopy of a kind of material in prof. Lilo Pozzo’s laboratory. Since the dataset is composed of 448 samples with 101 features, the original dimension of the dataset in 101, which is too complex to analyze and need further dimension reduction. Moreover, the data are functional data, which means they couldn’t be simply express by vectors and need more advanced analytical methods such as tangent PCA and VAE to process them.
To see how spectrum data was obtained, please see `data` directory.

Citation for accompanying publication:
[Link](https://s3.eu-west-1.amazonaws.com/assets.prod.orp.cambridge.org/59/95672707d54c79b14a3bbae3a87aa9_no_meta.pdf?AWSAccessKeyId=ASIA5XANBN3JMTIBZD3O&Expires=1654493193&Signature=W4erv8fST7sAJQ6VLgwp6h5A0cw%3D&response-cache-control=no-store&response-content-disposition=inline%3B%20filename%20%3D%22multivariate-analysis-of-peptide-driven-nucleation-and-growth-of-au-nanoparticles.pdf%22&response-content-type=application%2Fpdf&x-amz-security-token=FwoGZXIvYXdzEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDKFLn3XpZbPpHP2s4iKtAQM5zs%2BbclVzzKPoUgGkgwuJ5YJn1VUUdzpHMocPMgdV7A%2FZdX%2BuBTf4vw7DLrDTiZAJq70ieyG684a%2FHjnAApgx4eOYnaj%2F8OervYom6JVcnxDndrp7UndafWXNqG324bKjc8F%2BQUh%2BWq4NGg0gictyFXTbhcF7C7kJHdFVyOxzdNMrx3d7UYRvbzgdpsJZ05CehfYfWAEtiNJSjZNLM7sVUnk8Etv8D8zEa2yFKLOc9pQGMi19wei5JKfp9QRcXTeH7WcGT3MNVdxwpwtPcrBF%2FY7W%2BL%2Fhknv9E2hphz8K0%2FE%3D)

-----

## Authors
Bella Wu, Material Science and Engineering <br>
Kim, Material Science and Engineering <br>
Lilo Yeh, Material Science and Engineering <br>
Nick Leu, Material Science and Engineering <br>
William Lin, Material Science and Engineering <br>
