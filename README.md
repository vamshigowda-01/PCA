Iris Dataset PCA Visualization
📌 Project Overview

This project demonstrates Principal Component Analysis (PCA) on the famous Iris dataset. The goal is to reduce the dataset from 4 dimensions to 2 dimensions and visualize how different flower species are distributed.

🚀 Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

📂 Dataset

The dataset used is the built-in Iris dataset from Scikit-learn.

It contains:

150 samples

4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

3 classes:

Setosa

Versicolor

Virginica

⚙️ Installation

Run the following commands to install required libraries:

pip install pandas
pip install numpy
pip install matplotlib
pip install scikit-learn
🧠 Project Workflow
1. Load Dataset

Loaded Iris dataset using sklearn.datasets

2. Data Preprocessing

Converted dataset into Pandas DataFrame

Checked for missing values

Standardized data using StandardScaler

3. Dimensionality Reduction

Applied PCA to reduce features from 4 → 2

Used PCA(n_components=2)

4. Visualization

Created scatter plot using Matplotlib

Each color represents a different species

📊 Output

A 2D scatter plot showing:

Clear separation of Setosa

Slight overlap between Versicolor and Virginica

📷 Sample Output
PCA Scatter Plot
(X-axis: Principal Component 1)
(Y-axis: Principal Component 2)
💡 Key Concepts

Standardization ensures all features contribute equally

PCA reduces dimensionality while preserving variance

Helps in:

Data visualization

Noise reduction

Feature extraction

🛠️ How to Run

Copy the code into a .py file or Jupyter Notebook

Run the script

The PCA scatter plot will be displayed

📈 Future Improvements

Add explained variance ratio plot

Apply clustering (K-Means) after PCA

Build interactive visualization (Plotly)

👨‍💻 Author

Vamshi M S

Data Analyst | Machine Learning Enthusiast
