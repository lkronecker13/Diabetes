# Diabetes EDA

This small project is an exploratory data analisis of a diabtes dataset from [from Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database). 


## Project structure

### Notebooks

In the root folder of the project you will find two notebooks prepended with a number:

```
1. Preparation.ipynb
2. Univariate analysis.ipynb
3. Multivariate analysis.ipynb
```

This files are to be opened in order so that the flow in which the project was developed can be followed. 

### Data

The folder data contains the following paths:

```
1_original: Contains the original data as was received. The contents of this folder should never be modified so we always have a backup.
2_prepared: Data ready for analysis.

## Project setup

In order to successfully run the project make sure that Anaconda (https://www.anaconda.com/downloads) is installed in your system since it is used as an 
environment/package manager. 

Once conda is installed in your system navigate to the project's root in your terminal (where the file transit_env.yml) and run the
following command:

```conda env create -f transit_env.yml```

This will create the environment that will be used to run the project. Once all the packages are installed run the command:

```jupyter notebook```



