This repository contains Machine Learning Concepts/Analysis and Algorithms examples.

### Table of Contents
- <a href='#analysis'>Analysis</a>  
  - <a href='#analysis-on-titanic-dataset'>Analysis-Titanic Dataset</a> 
  - <a href='#analysis-on-iris-dataset'>Analysis-IRIS Dataset</a>
  - <a href='#analysis-on-house-price-dataset'>Analysis-HousePrice Dataset</a> 
- <a href='#data-wrangling'>Data Wrangling</a> 
  - <a href='#understanding-dataset'>Understanding Dataset</a> 
  - <a href='#pandas-read-from-url'>Pandas Read From URL</a>
  - <a href='#data-consolidation'>Data Consolidation</a>
  - <a href='#pandas-profiling'>Pandas Profiling</a>
  - <a href='#mysql-and-pandas'>MySQL and Pandas</a> 
  - <a href='#pivot-tables'>Pivot Tables and GroupBy</a> 
- <a href='#data-visualization'>Data Visualization</a> 
- <a href='#feature-engineering'>Feature Engineering</a>
- <a href='#ml-concepts'>ML Concepts</a>
  - <a href='#performance-measure-for-classification'>PerformanceMeasure-Classification</a>
  - <a href='#bias-variance-tradeoff'>Bias-Variance TradeOff</a>
  - <a href='#curse-of-dimentionality'>Curse-Of-Dimentionality</a>
  
- <a href='#ml-algorithms'>ML Algorithms</a>
  - <a href='#decision-trees'>Decision Trees</a> 
  - <a href='#support-vector-machines'>Support Vector Machines</a>
  - <a href='#k-means-clustering'>K-Means Clustering</a>
  - <a href='#fp-growth'>FP-Growth</a>
  - <a href='#gausian-naive-bayes'>Gausian Naive Bayes</a>
  - <a href='#simple-linear-regression'>Simple Linear Regression</a>
  - <a href='#polynomial-linear-regression'>Polynomial Linear Regression</a>
  - <a href='#knn'>KNN</a>
  - <a href='#logistic-regression'>Logistic Regression</a>

<hr>

- ###### [Analysis on Titanic Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/Titanic)
   ###### This example is analysis on Titanic Dataset. [[source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/Titanic)
  * Load the data[titanic.csv]
  * Clean and Prepare Data
  * Create Sparse Matrix 
  * Split Dataframe as:
    ![image](https://user-images.githubusercontent.com/689226/80577735-01646080-8a25-11ea-8557-a8cb8abeba5f.png)
    Representation of Split: </br>
    ![image](https://user-images.githubusercontent.com/689226/80582594-9b7bd700-8a2c-11ea-85ef-43698b361bb2.png)
  * Apply ML Model
  * Make Prediction
  * Cross Validate
  ![image](https://user-images.githubusercontent.com/689226/80578446-168dbf00-8a26-11ea-890a-d3a33ca1d7c3.png)
  * Make Predictions
<hr>

- ###### [Analysis on IRIS Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/IRIS)
   ###### This example is analysis on IRIS Dataset. [[source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/IRIS)
  * Load the data[iris.csv]
  * Clean and Prepare Data
  * Split Dataframe as [above](#analysis-on-titanic-dataset) for Pictorial representation
  * Apply ML Model
  * Make Prediction
  * Cross Validate
  * Make Predictions

<hr>

- ###### [Analysis on House Price Dataset](https://github.com/rahulvaish/MachineLearning-Python/tree/HousePriceCompetition)
   ###### This example is analysis on House Price Dataset.[[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/HousePriceCompetition)
   * Load the data[HousePricingTutorial.csv] 
   * Normalize
   * Analyse Correlation
   * Clean and Prepare Data
   * Split Dataframe as [above](#analysis-on-titanic-dataset) for Pictorial representation
   * Apply ML Model
   * Make Prediction
   * Cross Validate
     **Refer [above](#analysis-on-titanic-dataset) for Pictorial representation**  
   * Make Predictions   
<hr>

- ###### [Understanding Dataset](https://github.com/rahulvaish/MachineLearning-Python/blob/DataWrangling/DataCleaning/PandasCrashCourse.ipynb)
   ###### This example explains basic computing options with Pandas Dataframe/Series [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/blob/DataWrangling/DataCleaning/PandasCrashCourse.ipynb) 
  * Load the data[Loan.csv]
  * Undersatnding Types
  * Column Operations
  * Row Operations
  
  
<hr>

- ###### [Pandas Read From URL](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PandasReadFromURL)
   ###### This example explains how we can access data present on Cloud(Azure Cloud Storage). [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PandasReadFromURL)
  * Storing Data on Cloud (Azure Cloud Storage).
  * Accessing the Data using Pandas Library.


<hr>

- ###### [Data Consolidation](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataConsolidation)
   ###### This example explains various methods of consolidating Data. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/DataConsolidation)
  * Concatinating Dataframe 
  * Appending Dataframe 
  * Joining Dataframe 
  * Merging Dataframe 
   

<hr>

- ###### [Pandas Profiling](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PandasProfiling)
   ###### This example explains how to do Data Profiling using pandas-profiling library. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/DataWrangling/PandasProfiling)
  * Load the Data [iris.csv] 
  * Apply profiling
  * Save the ouput in html
   

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
  
- ###### [Feature Engineering](https://github.com/rahulvaish/MachineLearning-Python/tree/FeatureEngineering)
   ###### This example explains common methods used for Feature Engineering. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/FeatureEngineering) 
  * Load the data[mercedesbenz.csv]
  * Nominal Encoding (One-Hot Normal | One-Hot KDD | Count/Frequncy) 
  * Ordinal Encoding (System | Custom)
  
  <hr>

- ###### [Performance Measure for Classification](https://github.com/rahulvaish/MachineLearning-Python/tree/MLConcepts)
   ###### This example explains Concepts like Confusion Matrix | Accuracy | Precision | Recall | F1-Score. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLConcepts) 
  * Understanding Confusion Matrix
  * Understanding Accuracy
  * Understanding Precision
  * Understanding Recall
  * Understanding F1-Score
  ![image](https://user-images.githubusercontent.com/689226/52333127-6a2b7b80-2a22-11e9-9d1f-037f2f5f8b3d.png)

  
  <hr>
  
- ###### [Bias-Variance TradeOff](https://github.com/rahulvaish/MachineLearning-Python/blob/MLConcepts/BiasVarianceTradeOff.md)
   ###### This [Sheet](https://github.com/rahulvaish/MachineLearning-Python/blob/MLConcepts/BiasVarianceTradeOff.md)  explains the concept of Bias-Variance TradeOff.
 
  <hr>
  
- ###### [Curse-Of-Dimentionality](https://github.com/rahulvaish/MachineLearning-Python/blob/MLConcepts/CurseOfDimentionality.MD)
   ###### This [Sheet](https://github.com/rahulvaish/MachineLearning-Python/blob/MLConcepts/CurseOfDimentionality.MD)  explains the concept of Curse Of Dimentionality.
 
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
  * Computing Simple Linear Regression using Scikit-learn </br>
  ![image](https://user-images.githubusercontent.com/689226/52331599-993fee00-2a1e-11e9-8c52-eb842eefd392.png)

  
  <hr>
  
- ###### [Polynomial Linear Regression](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains Polynomial Linear Regression's implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[DatasetForSimpleAndPolynomialLinearRegression.csv] </br>
  * Computing Simple Linear Regression using Scikit-learn </br>
  * Computing Polynomial Linear Regression </br>
  * Comparision of different Polynomial Linear Regression graphs based on different degrees.
  ![image](https://user-images.githubusercontent.com/689226/52340059-d3b48580-2a34-11e9-9b6f-15645fc5eaa9.png)

  
  <hr>
  
- ###### [KNN](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains KNN Algorithm and its implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv] </br>
  * Compute KNN </br>
  * Compute KNN on different values of K </br>
  
   <hr>
   
- ###### [Logistic Regression](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms)
   ###### This example explains concepts of Logistic Regression Algorithm and its implementation in Python. [[Source Code]](https://github.com/rahulvaish/MachineLearning-Python/tree/MLAlgorithms) 
  * Load the data[IRIS.csv] </br>
  * Compute Logistic Regression </br>
     
   <hr>
