# Ryerson Winter 2020 Capstone Project
This project is part of the [capstone project](https://continuing.ryerson.ca/search/publicCourseSearchDetails.do;jsessionid=1A27012141908DF0EBDA27F4216447CA?method=load&courseId=26431), as part of the [Data Analytics, Big Data, and Predictive Analytics](https://continuing.ryerson.ca/public/category/courseCategoryCertificateProfile.do?method=load&certificateId=171618) fast track course. Each student looks for a data set and gives an analysis report and presentation.

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is to create a classification and predictive model with the NFL dataset. The data comes from the [Kaggle](https://www.kaggle.com/c/nfl-big-data-bowl-2020) website, given by the National Football League, is a collection of every running play from Week 1 of 2017 to Week 12 of 2019. The objective of this project is to see if we can find a way if  we can predict if the play will successfully make the first down.

### Technologies
* Python
* Pandas, jupyter
* MatPlotLib and Seaborn

## Project Description
The objective of this project is to take the dataset of all running plays from 2017-2019 and see if we can see the factors that go into making a first down. This will be done by using machine learning methods like Logistic Regression, Decision Tree and Random Forest, and K-Nearest Neighbors. This will be done with the data, using oversampling and undersampling, and using Principal Component Analysis, and using that to see if we can make a prediction model. All methods used will be compared with each accuracy, precision, recall and F-Score at the end to see which method is better. Visualization methods, as well as some data mining techniques, will be used to identify the features that make the most impact with the data. 

The [data set can be found on Kaggle](https://www.kaggle.com/c/nfl-big-data-bowl-2020), you need to download it to run the scripts and place it in data/raw directory.

## Featured Notebooks/Analysis/Deliverables
* [01 - Cleaning Raw Data](https://github.com/rowevscolumn/capstone/blob/master/notebooks/01%20-%20Cleaning%20Raw%20Data.ipynb)
  - All the cleaning of the raw data into a technically correct format
* [02 - Univariate Analysis](https://github.com/rowevscolumn/capstone/blob/master/notebooks/02%20-%20Univariate%20Analysis.ipynb)
  - Bar graphs and box plots to analyze the attributes, cleaning outliers and removing identifying data
* [03 - Bivariate Analysis](https://github.com/rowevscolumn/capstone/blob/master/notebooks/03%20-%20Bivariate%20Analysis.ipynb)
  - Low variance check and Correlation Heatmap
* [04 - Dimensionality Reduction](https://github.com/rowevscolumn/capstone/blob/master/notebooks/04%20-%20Dimensionalty%20Reduction.ipynb)
  - Variance threshold, backward elimination, recursive feature elimination and embedded method for the final steps of feature selection
* [05 - Oversampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/05%20-%20Oversampling.ipynb)
  - Oversampling and Undersampling the data, into two separate data files
* [111 - Logistic Regression Oversampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/111%20-%20Logistic%20Regression%20Oversampling.ipynb)
* [112 - Logistic Regression Undersampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/112%20-%20Logistic%20Regression%20Undersampling.ipynb)
* [113 - Logistic Regression PCA](https://github.com/rowevscolumn/capstone/blob/master/notebooks/113%20-%20Logistic%20Regression%20PCA.ipynb)
  - Using Python's Logistic Regression to make a predictive model.
* [121 - Decision Tree Oversampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/121%20-%20Decision%20Tree%20Oversampling.ipynb)
* [122 - Decision Tree Undersampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/122%20-%20Decision%20Tree%20Undersampling.ipynb)
  - Creating a Decision Tree for classification and prediction.
* [131 - Random Forest Oversampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/131%20-%20Random%20Forest%20Oversampling.ipynb)
* [132 - Random Forest Undersampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/132%20-%20Random%20Forest%20Undersampling.ipynb)
- Creating a Random Forest for classification to see if the accuracy is better than Decision Tree.
* [141 - K-Nearest Oversampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/141%20-%20K-Nearest%20Oversampling.ipynb)
* [142 - K-Nearest Undersampling](https://github.com/rowevscolumn/capstone/blob/master/notebooks/142%20-%20K-Nearest%20Undersampling.ipynb)
  - Creating a K-Nearest Neighbor classification model


[Christopher Rowe](https://github.com/rowevscolumn)
Last updated: March 16th, 2020
