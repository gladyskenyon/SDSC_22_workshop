# SDSC_22_workshop (18/05/22)
## Exploring the housing market in Spanish cities 
Gladys and Juanra will take you through an exploratory spatial analysis and market segmentation of property listings data from idealista. The city of focus is Madrid, the capital of Spain. You will create a range of visualuations and maps, and implement an unsupervised machine learning algorithm (k-means), to create clusters of properties. The analysis will be done in Python, every required step of the method is coded for you. If you are comfortable writing Python code, there are optional exersises to extend the analysis to other cities (Barcelona and Valencia). 

## Running the notebook 
The analysis is done in a jupyter notebook. You will need to bring a laptop to run the notebook. You have the option to run it locally or to run it through the internet. 

### Locally 
Follow these [instructions](https://gdsl-ul.github.io/soft_install/) to install and run Python from your own computer. You will need sufficient storage space for the software and data. 
Doing it this way will mean you are set up for future analysis and you can save your work and come back to it later! 

If you want to run the notebook locally, it is recommended to create a new conda environment based on the environment.yml file.

```
conda env create -f environment.yml
```
Alternatively, Make sure all the required packages are up to date and available in your environment:
  - geopandas
  - contextily
  - seaborn
  - pygeos
  - pysal
  - scikit-learn

### Run online 
Open in an interactive in-browser environment. On the day there will be a binder link here, you do not need to do anything beforehand. Once you close the browser tab your changes will not be saved.

## Data Source
Properties listing datasets and spatial segmentation have been brought thanks to [idealista](https://idealista.com/en/).

A detailed explanation of the methodology can be accessed via this _Data in Brief_ [working paper](https://github.com/paezha/idealista18/blob/master/data-in-brief/dib-idealista18.pdf), 
authored by David Rey Blanco, Pelayo González Arbués, Fernando López Hernández & Antonio Páez.

### Terms of use
Use of this dataset is subject to the license CC 4.0, as indicated at https://github.com/paezha/idealista18/blob/master/LICENSE.md
