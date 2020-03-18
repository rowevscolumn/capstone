# capstone
*Instructions: Click on the raw button in the upper right hand corner of this box.  Copy and paste the template into the README.md document on your github.  Fill in the titles, information and links where prompted! Feel free to stray a bit to suit your project but try to stick to the format as closely as possible for consistency across DSWG projects.*

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
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)


The [data set can be found on Kaggle](https://www.kaggle.com/c/nfl-big-data-bowl-2020), you need to download it to run the scripts and place it in data/raw directory.

## Featured Notebooks/Analysis/Deliverables
* [01 - Cleaning Raw Data](notebooks/01 - Cleaning Raw Data.ipynb)
  - All the cleaning of the raw data into a technically correct format
* [02 - Univariate Analysis](notebooks/02 - Univariate Analysis.ipynb)
  - Bar graphs and box plots to analyze the attributes, cleaning outliers and removing identifying data
* [03 - Bivariate Analysis](notebooks/03 - Bivariate Analysis.ipynb)
  - Low variance check and Correlation Heatmap
* [04 - Dimensionality Reduction](notebooks/04 - Dimensionalty Reduction.ipynb)
  - Variance threshold, backward elimination, recursive feature elimination and embedded method for the final steps of feature selection
* [05 - Oversampling](notebooks/05 - Oversampling.ipynb)
  - Oversampling and Undersampling the data, into two separate data files
* [111 - Logistic Regression Oversampling](notebooks/111 - Logistic Regression Oversampling.ipynb)
* [112 - Logistic Regression Undersampling](notebooks/112 - Logistic Regression Undersampling.ipynb)
* [113 - Logistic Regression PCA](notebooks/113 - Logistic Regression PCA.ipynb)
  - Using Python's Logistic Regression to make a predictive model.
* [121 - Decision Tree Oversampling](notebooks/121 - Decision Tree Oversampling.ipynb)
* [122 - Decision Tree Undersampling](notebooks/122 - Decision Tree Undersampling.ipynb)
  - Creating a Decision Tree for classification and prediction.
* [131 - Random Forest Oversampling](notebooks/131 - Random Forest Oversampling.ipynb)
* [132 - Random Forest Undersampling](notebooks/132 - Random Forest Undersampling.ipynb)
- Creating a Random Forest for classification to see if the accuracy is better than Decision Tree.
* [141 - K-Nearest Oversampling](notebooks/141 - K-Nearest Oversampling.ipynb)
* [142 - K-Nearest Undersampling](notebooks/142 - K-Nearest Undersampling.ipynb)
  - Creating a K-Nearest Neighbor classification model


[Christopher Rowe](https://github.com/rowevscolumn)
Last updated: March 16th, 2020
