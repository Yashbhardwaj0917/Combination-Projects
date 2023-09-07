# Password Data Analysis and Strength Prediction

## Introduction

In today's digital world, password security is paramount. This repository contains two distinct but related Jupyter Notebooks that provide insights into password data and predict password strength using a Support Vector Machine (SVM) classifier. The analysis and prediction aim to improve password security and user awareness.

## Dataset
https://www.kaggle.com/datasets/utkarshx27/passwords

### Overview of the Notebooks

#### Analysis of Password Data

The "Analysis of Password Data" notebook explores a dataset containing password information, focusing on categories and strengths. The notebook is structured as follows:

1. **Importing Dependencies:** Essential libraries like Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn are imported to conduct a comprehensive analysis.

2. **Loading Dataset:** The dataset "passwords.csv" is loaded for analysis.

3. **Initial Exploration and Cleaning:** This section explores the dataset's structure, checks for missing values, and visualizes the distribution of password strengths.

4. **Password Category (Qualitative Analysis):** Qualitative analysis examines different password categories, including frequency tables, relative absolute frequencies, and cumulative absolute frequencies. Visualizations such as bar plots and Pareto charts are provided.

5. **Password Strength (Quantitative Analysis):** Quantitative analysis studies the distribution of password strengths through line plots, scatter plots, and histograms. Extreme cases (e.g., exceptionally high or low strength passwords) are identified and analyzed.

#### Password Strength Prediction using SVM

The "Password Strength Prediction using SVM" notebook predicts password strength using SVM classification. The notebook's key sections include:

1. **Importing Dependencies:** Essential libraries for machine learning and data analysis are imported.

2. **Loading Dataset:** The dataset containing password samples and strength labels is loaded.

3. **Initial Exploration and Cleaning:** Initial exploration examines the dataset's dimensions, checks for missing values, and visualizes the distribution of password strengths.

4. **Machine Learning:**

    - **Test Train Split:** The dataset is divided into training and testing sets.
    - **Vectorization:** Passwords are vectorized using TF-IDF representation.
    - **Parameters (Defining and Searching):** Grid search is performed to find the best hyperparameters for the SVM model.
    - **Training and Testing:** The SVM classifier is trained, tested, and evaluated for accuracy using a confusion matrix.

5. **Interactive Password Strength Prediction:** An interactive component allows users to input a password, and the trained SVM model predicts its strength as "Strong password" or "Weak password."

### Conclusion

These notebooks offer valuable insights into password data analysis and provide a means to predict password strength using machine learning. By using the analysis findings and the interactive SVM model, users can make informed decisions to enhance their online security.

## Getting Started

To use these notebooks, follow these steps:

1. Clone the repository to your local machine:

2. Install the required libraries specified in the Jupyter Notebooks.

3. Run the "Analysis of Password Data" notebook to explore the dataset and understand password categories and strengths.

4. Run the "Password Strength Prediction using SVM" notebook to predict password strength and interactively check the strength of passwords.

Feel free to contribute, customize, or provide feedback to improve password security practices and cybersecurity awareness.

