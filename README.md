# Road Accident Severity Prediction

This project aims to predict the severity of road accidents based on environmental conditions using machine learning techniques.


## About

This project is part of the SC1015 (Introduction to Data Science and Artificial Intelligence) course mini-project. We leverage the [Road Accidents CSV and EXCEL dataset](https://www.kaggle.com/datasets/abdulmannann/road-accidents-csv) from Kaggle for building predictive models.

### Algorithms/Libraries used
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- tensorflow
- tensorflow
- needs update=================
## Contributers
-@Caven-Chew
-@Noiderate
## FCS4_Team 8 Folder
### Data Processing and Analysis

#### [Jupyter Notebook - data_extraction.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/data_extraction.ipynb)
This notebook covers data extraction, cleaning, and preprocessing tasks. It demonstrates how we import the raw data, perform necessary data cleaning procedures, and potentially apply resampling techniques to address class imbalances.

#### [Jupyter Notebook - mini_project.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/mini%20project.ipynb)
This notebook focuses on the exploratory data analysis phase. It includes code to analyze key insights and patterns within our dataset, helping us better understand the distribution and relationships of variables.

### Machine Learning Models

#### Random Forest Models
- [Jupyter Notebook - r_forest.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest.ipynb)
- [Jupyter Notebook - r_forest2.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest2.ipynb)
- [Jupyter Notebook - r_forest3.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/r_forest3.ipynb)

These notebooks demonstrate the implementation of Random Forest models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.

#### Classification Tree
- [Classification_Tree.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree.ipynb)
- [Classification_Tree_40k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree_40k.ipynb)
- [Classification_Tree_4k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Classification_Tree_4k.ipynb)

These notebooks demostrates the implementation of Classification Tree models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.

#### Logistic Regression
- [Logistic_Regression_model.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model.ipynb)
- [Logistic_Regression_model_40k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model_40k.ipynb)
- [Logistic_Regression_model_4k.ipynb](https://github.com/Caven-Chew/SC1015-MINI_PROJECT/blob/main/Logistic_Regression_model_4k.ipynb)

These notebooks demostrates the implementation of Logistic Regression models for predicting accident severity based on our preprocessed dataset. Each notebook explore using different ration of the dataset with eddort to improve the overall accuracy of the model.

### Refrences
Gunay, D. (2023). Random Forest. Medium. https://medium.com/@denizgunay/random-forest-af5bde5d7e1e