
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files_des)
4. [Requirements](#requirements)
5. [Fast guide](#Fast_guide)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Colombia Housing Properties Price available at kaggle:

1. Are there significant differences in property prices between different regions of the country?
2. Is there a natural way to group properties based on their characteristics?
3. Which variables allow us to better predict the price of a property and how much precision is achieved?

The database used is not offered integrated into this repository due to space reasons, but it can be downloaded [here](https://www.kaggle.com/julianusugaortiz/colombia-housing-properties-price)


## File Descriptions <a name="files_des"></a>

There is an only notebooks available here to showcase work related to the above questions. In the data folder we have several files:

1. **regiones.csv:** Allows mapping departments to regions, and offers a key for merging between shapefile and kaggle database
2. **depto files:** They contain all the relevant information from the department layer. These files are required to create the Choroplet
3. **co_properties.csv:** This file is not actually included, however the code allows you to connect to the kaggle site and automatically download it to the data folder, as long as you have the authentication credentials that the kaggle library requires for these purposes. Here is a documentation about it. If you have problems with the download try downloading the file manually and disabling the download function in the notebook.

## Requirements <a name="requirements"></a>

The most important packages required are: geopandas, folium, sklearn, kaggle, numpy, pandas


## Fast guide<a name="Fast_guide"></a>

For a quick demo of map display you can check my post on Medium [here](https://hector-montes.medium.com/porqu%C3%A9-folium-y-geopandas-son-la-mejor-combinaci%C3%B3n-para-modelado-de-datos-georreferenciados-240d99f4cdde).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/julianusugaortiz/colombia-housing-properties-price).  Otherwise, feel free to use the code here as you would like!