# SAMPLING-  By:
Sampling assignment 

### Sampling Definition
Sampling of a dataset is the process of selecting a subset of data from a larger dataset for the purpose of analysis or modeling. In other words, it involves taking a representative portion of the data that can be used to draw conclusions about the larger dataset.

There are several types of sampling methods, including:

1. Random Sampling: This involves selecting a random subset of the data without any bias.

2. Stratified Sampling: This involves dividing the dataset into strata (groups) based on some characteristic, and then randomly selecting a sample from each stratum.

3. Cluster Sampling: This involves dividing the dataset into clusters (groups) based on some characteristic, and then randomly selecting a sample of clusters to analyze.

4. Systematic Sampling: This involves selecting every nth item in a dataset, where n is a predetermined interval.

The choice of sampling method depends on the research question, the available data, and the analysis techniques being used. Sampling can help to reduce the time and resources required for data analysis while still providing accurate and reliable results.

### Analysis :
The dataset used is highly imbalanced. The number 0's were 763 and number of 1's were 9. As we can see sampling is needed as trainig the model on the current Dataset will only give 0 for all input .
So we have used Oversampling for the same .

Sampling used are as follow:

1. Simple / Random Sampling (RS)
2. Proportional Stratified Sampling (PSS)
3. Disproportional Stratified Sampling (DSS)
4. Cluster Sampling (CS)
5. Systematic Sampling (SS)

Model used are:

1. Support Vector Machine (SVM)
2. Decision Tree Classifier (DT)
3. K-Nearest Neighbours (KNN)
4. Naive Bayes (NB)
5. Random Forest (RF)

### Model Evaluation:

The accuracy of these models are as follow :
|      |   RS    |     SS     |   CS     |     PSS    |     DSS    |
|------|-------: |------------|--------- |------------|----------- |
| SVM  |  0.8888 |    0.9000  |  0.9000  |    0.9301  |    0.9301  |
| DT   |  0.7777 |    0.7000  |  0.9685  |    0.9781  |    0.9781  |
| KNN  |  0.5555 |    0.6000  |  0.8455  |    0.8209  |    0.8209  |
| NB   |  0.6666 |    1.0000  |  0.8481  |    0.8995  |    0.8995  |
| RF   |  0.8333 |    0.7000  |  0.9895  |    0.9956  |    0.9956  |

