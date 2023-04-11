# K-Nearest Neighbors Classifier

    This repository contains a Python script that demonstrates K-Nearest Neighbors Classifier (KNN) on a classified dataset. The goal is to build a KNN model that accurately classifies the data points.
    Dependencies

        Python 3.6 or later
        numpy
        pandas
        seaborn
        matplotlib
        scikit-learn

    You can install the required dependencies using the following command:

    bash

    $ pip install numpy pandas seaborn matplotlib scikit-learn

## How to use

        Clone the repository.
        Run the script knn_classifier.py in your Python environment.

    The script will:

        Load the dataset and display the first few rows.
        Display the dataset information and check the dataset balance.
        Separate the features (X) and the target (y) and perform a train-test split.
        Scale the data using Scikit-Learn's StandardScaler.
        Train the KNN model with different values of k and calculate the error rate for each k (Elbow method).
        Plot the error rate vs the number of neighbors (k).
        Train the final model with the optimal value of k.
        Evaluate the model's accuracy and print the classification report.

## Results

    The elbow method helps to determine the optimal value of k (number of neighbors) for the KNN classifier. In this example, the optimal value of k is found to be 10. The final model trained with k=10 achieves an accuracy of 95% on the test dataset. The classification report provides additional information about precision, recall, and F1-score for each class.

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
