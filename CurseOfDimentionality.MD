#### Curse Of Dimentionality

The below graph illustrales the relation between number of Features versus Accuracy. There exists a threshold where the accuracy of a ML model is highest.
![image](https://user-images.githubusercontent.com/689226/79692235-a6db3f80-8281-11ea-984b-307d50e73d91.png)

#### Example:
The below example illustrates that if we train our model on all features - it becomes overfitted and responds incorrectly (for football).
![image](https://user-images.githubusercontent.com/689226/79694675-81edc900-828f-11ea-8e5f-2a7fe9acc4ed.png)

Instead, if we choose our features appropritely (i.e, define a threshold by leaving out "Red" column), and then train-test our model, the model then reponds correctly :)
![image](https://user-images.githubusercontent.com/689226/79694722-c4170a80-828f-11ea-9452-31717d2e0f1c.png)
