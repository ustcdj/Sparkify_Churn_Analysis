# Predict Sparkify User Churn
[Table of Contents](#Table_of_Contents)
  - [Background](#background)
  - [Installation](#installation)
  - [File Descriptions](#file-descriptions)
  - [Feature Importance](#feature-importance)
  - [Acknowledgements](#acknowledgements)

## 1. Background
Preventing churn is key to improving revenue for Sparkify, a subscription-based company (fictitious). This project is to analyze data from Sparkify to build a model to predict customer churn.

First, a sample dataset (128MB) was used on a local machine to explore relevant features and develop a working model. Then similar steps were used to develop a final working model for the full dataset(12GB) on the AWS cloud. I have learned:
1. how to deploy a Spark cluster on the cloud using AWS
2. how to manipulate large and realistic datasets with Spark to engineer relevant features to predict churn
3. how to use the machine learning APIs within Spark ML to build and tune models with large datasets

Please check my [blog post](https://medium.com/@ustcdj/sparkify-udacity-data-science-capstone-project-b273b4ab1c8d) for more details.

The detailed codes are at two notebooks below:
- **[`Sparkify.ipynb`](https://github.com/ustcdj/Sparkify_Churn_Analysis/blob/master/Sparkify.ipynb)** (using sample dataset, run on local Windows PC)
- **[`aws.ipynb`](https://github.com/ustcdj/Sparkify_Churn_Analysis/blob/master/aws.ipynb)** (using full dataset, run on AWS EMR cluster)

## 2. Installation
The code was developed using the Anaconda distribution of Python, versions 3.8.1. Python libraries used are `pyspark`, `pandas`, `numpy`, `matplotlib` and `seaborn`.


## 3. File Descriptions
* `Sparkify.ipynb` - the project notebook for the small dataset (128MB)
* `aws.ipynb` - the project notebook for the full dataset (12GB)


## 4. Feature Importance
<img src="gbt_fi.jpg" width=800>


## 5. Acknowledgements
Special thanks to [Udacity](https://www.udacity.com/) for providing the dataset.
