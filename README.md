# Machine_Learning

This repository showcases two illustrative examples, shedding light on the power of learning-based methods.

## Example 1: Breast Cancer Prediction

Breast cancer is a global health concern, demanding urgent attention. Just in 2020 alone, breast cancer claimed 685,000 lives worldwide. Hence, acccurate prediction of breast cancer plays a crucial role in our current world. 
For this manner, a typical example is predicted, here:
The dataset, named “breast_cancer.csv,” serves as the foundation for this example.
The predictive model is implemented in the Jupyter notebook file titled “LogisticRegression_Prediction.ipynb”

### Key Steps:
 1. Data Preprocessing: Detecting and handling missing values and outliers.
 2. Feature Visualization: Properly visualizing the distribution of dataset features.
 3. Correlation Analysis: Estimating the impact of different parameters on each class.
 4. Model Training: Employing the Logistic Regression approach.
 5. Model Assessment: Evaluating the model using the Confusion Matrix.

## Example 2: Dielectric Performance Prediction

Dielectrics in Industry: These materials, used in capacitors and semiconductor devices, hold immense promise for applications like artificial muscles.
 1. Assessing Performance: A comprehensive dataset is employed to assess dielectric performance.
 2. Prediction Approach: A non-linear regression method predicts material performance based on the maximum voltage applied to dielectrics.
 3. Educational Purpose: This example serves as a basic tutorial for students, introducing them to regression approaches.
 4. Code Reference: The Jupyter notebook “Nonlinear_Regression.ipynb” contains the implementation.
 5. Three different Kernel are implemented: RBF (Radial Basis Function), Second-order polynomial kernel and Sigmoid kernels
 6. L2-Regularization is applied to the models.

Moreover, they are implemented in a straightforward manner. Therefore, it’s useful to explore them through a basic example.

## Example 3: Classification of Perennial Plants Using K-Nearest Neighbors (KNN)

These examples demonstrate the intersection of theory, data, and practical applications, fostering a deeper understanding of machine learning and its impact on real-world challenges.
K-Nearest Neighbors (KNN), being non-parametric algorithms, rely on similarity and flexibility. This makes them valuable tools in various machine learning scenarios. 
The Iris Dataset will be utilized for classifying perennial plants based on their sepal width, sepal length, petal width, and petal length.
The K-Nearest Neighbors (KNN) algorithm will be applied, and a confusion matrix will be generated to evaluate model performance.

### Key Steps
	1. Normalization: Data normalization will be performed to ensure that all features contribute equally to the distance calculation.
				Genre and Popularity Prediction for Music Dataset
	2. Data Preprocessing: The “name,” “year,” and “artist” columns will be removed from the music dataset.
				The “popularity” column will be split into five sections (e.g., low, moderate, high, very high, extremely high).
	3. Quantification and One-Hot Encoding: A new column called “new_genre” was created and filled base on one-hot encoding method.
	4. Data Features’ Distribution: The distribution of features in the dataset will be visualized to gain insights.
	5. Normalization and Correlations: Feature normalization will be applied, and correlations between different features will be explored.
	6. Data Splitting: The data will be split into training, validation, and test sets.
	7. KNN Algorithm: The KNN algorithm will be employed to predict genres based on the features.
				Hyperparameters will be tuned to find the best model in terms of accuracy.
	8. Reporting Genres: The most and least frequent genres in the dataset will be reported.
