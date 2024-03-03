<h1>Breast Cancer Diagnosis Prediction</h1>

<h2>Overview</h2>
This project aims to predict breast cancer diagnosis using machine learning techniques. The dataset utilized contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. A Support Vector Machine (SVM) classifier is employed to predict the diagnosis (malignant or benign) based on these features.

<h2>Dataset</h2>
The dataset used in this project is sourced from [https://github.com/Vedu36/Breast-Cancer-Prediction-using-SVM/blob/main/Breast_Cancer.csv].

The dataset consists of 569 samples and 32 features. Each sample includes an ID number, diagnosis (malignant or benign), and ten real-valued features computed for each cell nucleus:

Radius (mean of distances from center to points on the perimeter)

Texture (standard deviation of gray-scale values)

Perimeter

Area

Smoothness (local variation in radius lengths)

Compactness (perimeter^2 / area - 1.0)

Concavity (severity of concave portions of the contour)

Concave points (number of concave portions of the contour)

Symmetry

Fractal dimension ("coastline approximation" - 1)

The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. All feature values are recoded with four significant digits. 

<h2>Installation</h2>

To run the code, follow these steps:

Clone the repository: git clone https://github.com/Vedu36/Breast-Cancer-Prediction-using-SVM.git
Install the required dependencies usage

Ensure you have Python installed on your system.

Run the breast_cancer_prediction.ipynb notebook to execute the code.
Follow the instructions within the notebook to explore the dataset, preprocess the data, train the SVM model, and evaluate its performance.

<h2>Results</h2>
  
Accuracy Score: 98.24561403508771]

F1 Score: 97.61904761904763

ROC AUC Score: 97.67441860465116

Precision Score: 100.0

<h2>Future Enhancements</h2>

Explore alternative machine learning algorithms for comparison.
Conduct feature engineering to derive more informative features.
Fine-tune model hyperparameters for improved performance.




