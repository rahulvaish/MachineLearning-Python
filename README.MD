This repository contains Machine Learning Concepts/Analysis and Algorithms examples.

### Table of Contents
- <a href='#analysis-on-titanic-dataset'>Analysis-Titanic Dataset</a> 
- <a href='#analysis-on-iris-dataset'>Analysis-IRIS Dataset</a> 
- <a href='#analysis-on-house-price-dataset'>Analysis-HousePrice Dataset</a> 
- <a href='#data-wrangling'>Data Wrangling</a> 
  - <a href='#data-cleaning'>Data Cleaning</a> 
  - <a href='#data-consolidation'>Data Consolidation</a> 
  - <a href='#mysql-and-pandas'>MySQL and Pandas</a> 
  - <a href='#pivot-tables'>Pivot Tables and GroupBy</a> 
- <a href='#data-visualization'>Data Visualization</a> 
- <a href='#feature-selection'>Feature Selection</a>
- <a href='#ml-concepts'>ML-Concepts</a>
  - <a href='#performance-measure-classification'>PerformanceMeasure-Classification</a> 
- <a href='#ml-algorithms'>ML Algorithms</a>
  - <a href='#decision-trees'>Decision Trees</a> 
  - <a href='#support-vector-machines'>Support Vector Machines</a>
  - <a href='#k-means-clustering'>K-Means Clustering</a>
  - <a href='#fp-growth'>FP-Growth</a>
  - <a href='#gausian-naive-bayes'>Gausian Naive Bayes</a>
  - <a href='#simple-linear-regression'>Simple Linear Regression</a>

<hr>


- ###### [Analysis on Titanic Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/Titanic)
   ###### This example is analysis on Titanic Dataset. [[source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/Titanic)
  * Load the data[titanic.csv]
  * Clean and Prepare Data
  * Create Sparse Matrix 
  * Split Dataframe as (Train+Test)+(Untouched - Target) </br>
   **Pictorial Representation:** </br>
    ![image](https://user-images.githubusercontent.com/689226/50549588-708d4180-0c85-11e9-8a0e-377368b9fa9c.png)
  * Apply ML Model
  * Make Prediction
  * Cross Validate
  ![image](https://user-images.githubusercontent.com/689226/50550252-f499f600-0c92-11e9-847f-b5c0ef8e7e93.png)
  * Make Predictions
<hr>

- ###### [Analysis on IRIS Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/IRIS)
   ###### This example is analysis on IRIS Dataset. [[source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/IRIS)
  * Load the data[iris.csv]
  * Clean and Prepare Data
  * Split Dataframe as (Train+Test)+(Untouched - Target) </br>
    **Refer [above](#analysis-on-titanic-dataset) for Pictorial representation** 
  * Apply ML Model
  * Make Prediction
  * Cross Validate
![crossvalidation pictorialrepresentation](https://user-images.githubusercontent.com/689226/50550295-ded90080-0c93-11e9-967d-7c00d82a9705.jpg)
  * Make Predictions

<hr>

- ###### [Analysis on House Price Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/HousePriceCompetition)
   ###### This example is analysis on House Price Dataset.[[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/HousePriceCompetition)
   * Load the data[HousePricingTutorial.csv] 
   * Normalize
   * Analyse Correlation
   * Clean and Prepare Data
   * Split Dataframe as (Train+Test)+(Untouched - Target) </br>
     **Refer [above](#analysis-on-titanic-dataset) for Pictorial representation**  
   * Apply ML Model
   * Make Prediction
   * Cross Validate
     **Refer [above](#analysis-on-titanic-dataset) for Pictorial representation**  
   * Make Predictions   
<hr>

- ###### [Data Cleaning](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataCleaning)
   ###### This example explains various methods of cleaning Data. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataCleaning) 
  * Load the data[Loan.csv]
  * Column selection in Dataframe
  * Dropping off Useless Columns
  * Dropping off Rows (on condition)
  * Type Conversion
  * Converting Non-Numerical Columns into Numerical Columns/Sparse
  * Determining Null Values
  * Filtering Data on Threshold Benchmark
  * Handling Missing Values
  * Queries on Dataframe
  * Split Dataframe Column Values[Example: Date]
  * Data Replacment-Unary|Binary|Sparse
  
  
<hr>

- ###### [Data Consolidation](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataConsolidation)
   ###### This example explains various methods of consolidating Data. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataConsolidation)
  * Concatinating Dataframe 
  * Appending Dataframe 
  * Joining Dataframe 
  * Merging Dataframe 
   

<hr>

- ###### [MySQL and Pandas](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/MySQL%2BPandas)
   ###### This example explains the connectivity between MySQL and Pandas. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/MySQL%2BPandas)
   
<hr>

- ###### [Pivot Tables](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PivotTables)
   ###### This example explains the concept of Pivot Tables and GroupBy. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PivotTables)
   * Load the data[schools_with_btoilet.csv/schools_with_gtoilet.csv]
   * Apply Panda's Pivot Method </br>
   ![image](https://user-images.githubusercontent.com/689226/50417338-d9bb2200-084b-11e9-95bc-66772b346dd1.png)



<hr>

- ###### [Data Visualization](https://github.com/rahulvaish/MachineLearning-Python/tree/DataVisualization)
   ###### This example explains how to Visualize data in various forms of Graphs. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataVisualization)   
  * Pair Plot
  * Line Graph
  * Histo Graph
  * Bar Plot
  * Scatter Plots
  * Box Plots
  * Heat Maps
  
  <hr>
  
- ###### [Feature Selection](https://github.com/rahulvaish/MachineLearning-Python/tree/FeatureSelection)
   ###### This example explains common methods used for Feature Selection. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/FeatureSelection) 
  * Load the data[IRIS.csv]
  * Thresholding on Numerical Features
  * Thresholding on Missing Values
  * Thresholding on Binary Feature Variance
  * Feature Selection from Highly Correlated Features
  * Feature Selection on Irrelevant Features for Classification-CHI2|ANOVA
  
  <hr>

- ###### [PerformanceMeasure-Classification](https://github.com/rahulvaish/MachineLearning-Python/tree/MLConcepts)
   ###### This example explains Concepts like Confusion Matrix | Accuracy | Precision | Recall | F1-Score. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLConcepts) 
  * Understanding Confusion Matrix
  * Understanding Accuracy
  * Understanding Precision
  * Understanding Recall
  * Understanding F1-Score
  
  <hr>
  
- ###### [Decision Trees](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains Decison Trees' theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv]
  * Decision Trees Classification using GINI Index
  * Decision Trees Classification using Information Gain
  * Visualizing Decision Trees 
  * Decision Trees Regression
  
  <hr>
  
  
- ###### [Support Vector Machines](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains Decison Trees' basic theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv]
  * Computing SVM </br>
  ![image](https://user-images.githubusercontent.com/689226/51068659-5bca8980-1647-11e9-9592-461b9bb25e81.png)
  
  <hr>
  
 
- ###### [K-Means Clustering](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains K-Means Clustering basic theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv] </br>
  * Computing K-Means Clustering </br>
  * Determining K - Elbow Method | Silhouette Method </br>
  * Mini-Batch K-Means </br>
 ![image](https://user-images.githubusercontent.com/689226/51653477-8a3a5400-1fb9-11e9-9a4b-48b57c41ab69.png)

  <hr>
  
- ###### [FP-Growth](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains FP-Growth basic theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Install pyfpgrowth [pip install pyfpgrowth] </br>
  * Prepare Dummy Data </br>
  * Computing FP-Growth </br>
  
  <hr>
  
- ###### [Gausian Naive Bayes](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains Gaussian Naive Bayes basic theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv] </br>
  * Computing Gaussian Naive Bayes using scikit-learn </br>
  * Computing Gaussian Naive Bayes by logic </br>
  
  
  <hr>
  
- ###### [Simple Linear Regression](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains Simple Linear Regression's basic theory with an implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[SimpleLinearRegression.csv] </br>
  * Computing Simple Linear Regression by logic </br>
  ![image](https://user-images.githubusercontent.com/689226/52331599-993fee00-2a1e-11e9-8c52-eb842eefd392.png)

  
  <hr>
  
