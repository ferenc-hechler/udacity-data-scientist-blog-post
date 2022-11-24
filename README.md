# Udacity Data Scientist Blog post

For the Udacity DataScientist course the AirBnB Dataset should be analyzed using the CRISP-DM process and the results should be published. 
This repository contains all the sources used to analyze the data.

# How to setup your environment

```
conda create -n udacity python=3.10
conda activate udacity
pip install numpy pandas matplotlib scipy scikit-learn seaborn
pip install jupyter
```

## Getting the Data

The AirBnB Seatlle data is provided by AirBnB in the Kaggle platform and can be downloaded from there:
https://www.kaggle.com/datasets/airbnb/seattle?resource=download

In the notebooks, the extracted ZIP file is expected in the subfolder -/data/

## Start local Jupyter Notebook

```
cd .../udacity-data-scientist-blog-post
jupyter notebook
```

# Questions

The following business questions should be answered in this analysis:

* Is a higher price rectified by a higher customer satisfaction?
* Is the number of reviews related to the customer satisfaction?
* Did customer stop using AirBnB in Seattle after they gave a bad rating?

# Files

The notebook AirBnB-Seattle-Data-Analysis.ipynb is used to load and analyze the data.

# Licenses

Sources are under GPL v3 License.
Credit to AirBnB for providing the data. 
You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/airbnb/seattle). 


