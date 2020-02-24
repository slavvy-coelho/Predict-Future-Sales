# PREDICT FUTURE SALES
In this project, I dealt with data about shops, the corresponding items they hold and historical time series data about the transactions to predict future sales. We will go through various steps like cleaning the data, performing some analysis, useful clustering to finally make our way to predicting how the sales would look like in near future.

### Data
https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data

### Approach
The project was attempted in 5 stages:
1. Exploratory data analysis and data cleaning
2. Feature Engineering
3. Clustering
4. Design and Implementation of Predictive Models
5. Train and Test of Models

### Implementation
The jupyter notebook, RMS.ipynb comprises the entire code. However, while working on LightGBM model, we have added lag features and date features to the training and testing dataset. It contained 44 columns and the total size of data became around 17GB. We tried to run our model on Google Colab, SFU cluster, AWS and GCP but it failed due to high computation power and limited storage. Finally, we used Compute Canada cluster to train the model with 2GPUs and 50 CPUs. 

### Result
1. Kaggle Score: 0.88904
2. Rank: 164 (as of Feb 24, 2020)
