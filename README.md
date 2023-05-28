# Glass Classification Dataset

This repository provides a dataset for glass classification, which aims to identify the type of glass based on various attributes. The dataset is obtained from the UCI Machine Learning Repository and was originally motivated by criminological investigations, where correctly identifying the type of glass left at the scene of a crime can serve as evidence.

## Dataset Description

The dataset contains the following attributes:

1. Id number: An identifier ranging from 1 to 214 (not to be used for classification).
2. RI: Refractive index.
3. Na: Sodium (measured in weight percent in the corresponding oxide).
4. Mg: Magnesium.
5. Al: Aluminum.
6. Si: Silicon.
7. K: Potassium.
8. Ca: Calcium.
9. Ba: Barium.
10. Fe: Iron.

The class identifier, which represents the type of glass, is provided in the last column. The dataset consists of seven classes:

1. Building Windows (Float Processed)
2. Building Windows (Non-Float Processed)
3. Vehicle Windows (Float Processed)
4. Vehicle Windows (Non-Float Processed) (None in this database)
5. Containers
6. Tableware
7. Headlamps

All the attributes are continuous variables.

## Dataset Source

The dataset can be accessed from the following link: [Glass Identification Dataset](https://archive.ics.uci.edu/ml/datasets/Glass+Identification)

## Classification Evaluation

To evaluate the classification performance of an HMM (Hidden Markov Model) classifier, the dataset suggests using 5-fold cross-validation. The following performance metrics should be calculated:

1. Confusion Matrix: A matrix representing the classification results, showing the counts of true positive, true negative, false positive, and false negative predictions for each class.
2. Sensitivity: Also known as true positive rate or recall, it represents the proportion of correctly identified positive instances.
3. Specificity: The true negative rate, indicating the proportion of correctly identified negative instances.
4. Total Accuracy: The overall accuracy of the classifier.
5. F1-Score: A measure that combines precision and recall, providing a balanced assessment of the classifier's performance.
6. ROC Curve: A plot showing the true positive rate against the false positive rate at different classification thresholds.
7. Area Under Curve (AUC): The area under the ROC curve, which represents the classifier's overall performance.

## Usage

To evaluate the classification performance of an HMM classifier on the Glass dataset, follow these steps:

1. Download the Glass dataset from the provided link.
2. Preprocess the dataset as necessary, such as handling missing values or normalizing the attribute values.
3. Implement an HMM classifier using appropriate libraries or tools (such as scikit-learn or specialized HMM libraries).
4. Perform 5-fold cross-validation to evaluate the classifier's performance.
5. Calculate the confusion matrix, sensitivity, specificity, total accuracy, F1-score, ROC curve, and AUC.
6. Analyze the results to gain insights into the classifier's performance.

## Acknowledgments

The Glass Identification dataset was sourced from the UCI Machine Learning Repository.
