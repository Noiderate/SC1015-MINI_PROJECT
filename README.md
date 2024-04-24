# Road Accident Severity Prediction

This project aims to predict the severity of road accidents based on environmental conditions using machine learning techniques.


## About

This project is part of the SC1015 (Introduction to Data Science and Artificial Intelligence) course mini-project. We leverage the [Road Accidents CSV and EXCEL dataset](https://www.kaggle.com/datasets/abdulmannann/road-accidents-csv) from Kaggle for building predictive models.
## Introduction
In Singapore, traffic accidents have been on a rise year-on-year. In the first half of 2023, the total number of traffic accidents resulting in injuries or fatalities increased by 11.8% to 3,542, from 3,169 in the first half of 2022. The total number of injured persons and fatalities increased by 17.1% to 4,550, from 3,886 in 2022. Even though the dataset is not set in Singapore, we hope to gain some knowledge about the domain.

![Tampines crash that happened the week we finished this project](https://static1.straitstimes.com.sg/s3fs-public/styles/large30x20/public/articles/2024/04/22/yutampinesaccidentcoll2204.jpg?VersionId=GGwjA_2XTIbaP76m2Y6Hdoi1ImTQw2dx)

## Attributes Included:

| Attribute             | Description                                                                                      |
|-----------------------|--------------------------------------------------------------------------------------------------|
| **Accident ID**       | A unique identifier assigned to each accident for reference and tracking purposes.               |
| **Date and Time**     | The date and time when the accident occurred, facilitating temporal analysis and trend identification. |
| **Location**          | The precise geographical coordinates or address where the accident took place, enabling spatial analysis and mapping. |
| **Severity**          | The severity level of the accident, categorized based on the extent of injuries, property damage, or fatalities. |
| **Weather Conditions**| Information about weather conditions prevailing at the time of the accident, such as clear, rainy, foggy, or snowy weather. |
| **Road Conditions**   | Description of road conditions, including dry, wet, icy, or slippery surfaces.                    |
| **Vehicle Involved**  | Details about vehicles involved in the accident, including types, models, and counts.             |
| **Contributing Factors** | Factors contributing to the accident, such as speeding, distracted driving, drunk driving, road defects, or mechanical failures. |
| **Injuries and Fatalities** | Number of individuals injured or killed as a result of the accident.                           |
| **Vehicle Maneuvers** | Description of maneuvers or actions taken by vehicles involved, such as turning, braking, or overtaking. |


## Algorithms/Libraries used
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- tensorflow (Might need to install if you dont already have it)
- setuptools
- needs update=================
## Contributers
- @Caven-Chew - Data Visualization, Data extraction, EDA, Random forest, Neural network
- @Noiderate - Outcome, Classification Tree, Logistic Regression
## Problem definition
- Are we able to predict the sevirity of car crashes using various features?
<!-- (FCS4_Team 8 Folder) -->
## Data Processing and Analysis

#### [Jupyter Notebook - data_extraction.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/data_extraction.ipynb)
This notebook covers data extraction, cleaning, and preprocessing tasks. It demonstrates how we import the raw data, perform necessary data cleaning procedures, and potentially apply resampling techniques to address class imbalances.

#### [Jupyter Notebook - mini_project.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/mini%20project.ipynb)
This notebook focuses on the exploratory data analysis phase. It includes code to analyze key insights and patterns within our dataset, helping us better understand the distribution and relationships of variables.

## Machine Learning Models

### Random Forest and Neural network Models
- [Jupyter Notebook - r_forest.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest.ipynb)
- [Jupyter Notebook - r_forest2.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest2.ipynb)
- [Jupyter Notebook - r_forest3.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest3.ipynb)

These notebooks demonstrate the implementation of Random Forest models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.

### Classification Tree
- [Classification_Tree.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree.ipynb)
- [Classification_Tree_40k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree_40k.ipynb)
- [Classification_Tree_4k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree_4k.ipynb)

These notebooks demostrates the implementation of Classification Tree models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.

### Logistic Regression
- [Logistic_Regression_model.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model.ipynb)
- [Logistic_Regression_model_40k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model_40k.ipynb)
- [Logistic_Regression_model_4k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model_4k.ipynb)

These notebooks demostrates the implementation of Logistic Regression models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.
## Conclusion
- Dataset is difficult to create a model for, all models returned unfavourable results
- Best model was classification tree but even that only have a accuracy of 46%, which is not much higher than random picking which is 33.33%
- While we had some big improvements in our ML models, none of the results are good enough to predict the outcome of a car crash

## Lessons learnt
- Picking a correct dataset is important
- We learnt about the different types of encoding like label encoding and one hot encoding and how they affect the model performance
- We understood the important of class balancing
- And we also gained knowledge about this topic in terms of how important variables are for prediction through coefficients and feature importance 
## Refrences
- Gunay, D. (2023). Random Forest. Medium. https://medium.com/@denizgunay/random-forest-af5bde5d7e1e
- Mannan, A. (2024). Road Accidents CSV and Excel dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/abdulmannann/road-accidents-csv
- SlidesGo. (n.d.). Driving Center [PowerPoint slides template]. Retrieved from https://slidesgo.com/theme/driving-center
- W3Schools. (n.d.). Home page [Website]. Retrieved from https://www.w3schools.com (used for many small simple functions)