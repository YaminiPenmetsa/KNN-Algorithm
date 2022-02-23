## KNN-algorithm
A simple Project on K Nearest Neighbors Algorithm. 
1. KNN is a **supervised learning algorithm**. It can be used for both classification and regression.
2. It is a **non-parametric algorithm** which means it does not make any assumptions on the dataset and
3. It is **lazy learning algorithm** as it memorizes the training data set.
4. It classifies a new data point to a certain target class based on the neighboring data points. The distance between the data points is calculated using **Manhattan distance** and **Euclidean distance.**

In this project, **Drug classification**  dataset [link] (https://www.kaggle.com/prathamtripathi/drug-classification) is used and **KNN Classifier** is used to classify the drugs into drugA, drugB, drugC, drugX, drugY.

The performance of KNN model:
| ID | Without hyperparameter tuning | With hyperparameter tuning  |
| :-- | :--| :--| 
|**Train accuracy**| 0.95522 | 1.0 |
|**Test accuracy** |0.84848    |0.89393 |
