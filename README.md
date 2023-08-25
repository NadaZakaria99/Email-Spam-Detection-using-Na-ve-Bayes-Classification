# Email-Spam-Detection-using-Na-ve-Bayes-Classification
This project focuses on utilizing various Naïve Bayes classifiers to classify email messages as spam or non-spam (ham). 
The dataset used is the Spambase dataset from the UCI Machine Learning Repository.
### Project Overview
The project involves the following main steps:

1-Data Preprocessing: The dataset is loaded and split into training and testing sets. The features are separated from the target labels.

2-Naïve Bayes Classifiers: Three different Naïve Bayes classifiers are employed: Gaussian Naïve Bayes, Multinomial Naïve Bayes, and Bernoulli Naïve Bayes. Each classifier is trained on the training data and evaluated on the testing data.

3-Evaluation and Visualization: The accuracy, precision, recall, and F1-score are calculated for each Naïve Bayes classifier. Confusion matrices and classification reports are generated for further evaluation. Heatmaps are used to visualize confusion matrices.

4-Subset Analysis: The training data is divided into four subsets, and Bernoulli Naïve Bayes classifiers are trained on each subset. The accuracy of each subset classifier is compared.
### Usage
1- Clone the repository to your local machine.

2- Install the required libraries by running: pip install pandas numpy seaborn matplotlib scikit-learn
### Dependencies

1- pandas

2- numpy

3- seaborn

4- matplotlib

5- scikit-learn

