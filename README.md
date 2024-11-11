# Quarto/Rmarkdown/Python <img src="featured.png" align="right" height="130"  alt="" />


### **Create a document for ML project with Python using Quarto in Rstudio**

> You must have a RStudio v2022.07.1 or a later version to render this prohject.
> To upgrade Quarto out of sync with the bundled version in RStudio, follow the directions at https://quarto.org/docs/download/



## About the Dataset

In this case our data coming from two different datasets:  
1. **Items**: this dataset is composed by 792 observations and 9 columns;  
2. **Reviews**: this dataset is composed by 82815 observations and 8 columns;  

Inside this two dataset there is the column *asin* that is and identify unique column. 
It's important to merge our two dataset in one.  
Merging data we obtain one dataset composed by 82815 observations and 16 columns.  
We will select some columns to achieve our goal that is to predict the column rating.

These are the columns:

| Column name | Description   | Type of Variable                                                    
|-----------------------------|------------------|-------------------------|
| **Total Reviews** | Total of reviews about that device | Covariate / Numeric
| **Prices**| Device price | Covariate / Numeric
| **Rating**  | Score Review | *Response* / Numeric
| **Helpful Votes**  | Number of people that vote that review | Covariate / Numeric
| **Brand**  | Device's Brand | Covariate / Categorical

---------------------------------------------------------
## Phases

There are some phases to follow to predict the column rating. They are:
- Pre-Processing
- Normalize the dataset
- Fit the model
Inside this document you can see how to push citations and refrences inside the document also.

Clone this repo and see the results!

# <p align=center>ENJOY!</center>
