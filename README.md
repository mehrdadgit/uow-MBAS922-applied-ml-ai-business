# MBAS922 – Applied ML and AI in Business

Jupyter Notebooks and Datasets for MBAS922 subject, UOW.


### Hands-on 1: Python Foundations and Introductory Analytics

Introduction to:
- Python basics (variables, control flow, functions)
- NumPy arrays and numerical operations
- Pandas DataFrames and data cleaning
- A first machine learning model using scikit-learn

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/01-python_basics_numpy_pandas_sklearn_intro.ipynb
)

---
### Hands-on 2: K-means Clustering (Bank Customer Segmentation)

This notebook introduces k-means clustering using scikit-learn.

You will:
- Load `vs_bank.csv`
- Select demographic and financial variables
- Standardise features
- Use within-cluster sum of squares (WCSS) to choose k
- Profile and interpret customer segments
- Extend to mixed data using k-prototypes (optional)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/02_kmeans_clustering_vs_bank.ipynb
)

---
### Hands-on 3: Decision Trees and Ensemble Learning

This notebook introduces classification models using scikit-learn, starting with a simple decision tree and then extending to ensemble methods.

You will:
- Load the dataset `vs_bank_part.csv`
- Use a predefined partition (`partition_Indicator`) to create training and validation sets
- Build a **Decision Tree** baseline model
- Improve performance using **Random Forest** and **Gradient Boosting**
- Compare models using multiple evaluation metrics including:
  - Accuracy
  - True Positive Rate (Sensitivity)
  - True Negative Rate (Specificity)
  - F1 Score
- Interpret improvements from ensemble learning


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/03_decision_tree_random_forest_gradient_boosting_vs_bank_part.ipynb
)

---

### Hands-on 4: Neural Networks (MLP) and Support Vector Machines

This notebook introduces two important classification models using **scikit-learn**:

- **Neural Networks** using a Multi-Layer Perceptron (MLP)
- **Support Vector Machines (SVM)**

You will:

- Load the dataset `vs_bank_part.csv`
- Use the provided `partition_Indicator` column to create **training** and **validation** datasets
- Use categorical and numeric predictors to model the binary target variable `b_tgt`
- Fit a **Neural Network (MLP)** model
- Fit a **Support Vector Machine (SVM)** model
- Use a specified cutoff to generate predictions
- Evaluate models using:
  - Confusion matrix
  - Validation misclassification rate
  - ROC curve
  - AUC (Area Under the Curve)
  - KS / Youden statistic
- Compare the performance of the two models
- Experiment with key parameters such as network structure, SVM kernels, and regularisation settings

For faster training, the SVM model is fitted on a **10% sample of the training data**, while still evaluating on the full validation set.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/04_mlp_svm_vs_bank_part.ipynb
)
---

### Hands-on 5: Deep Learning with TensorFlow (MLP, CNN, RNN)

This notebook introduces **deep learning models** using **TensorFlow and Keras** in Google Colab:

- **Basic Multi-Layer Perceptron (MLP)**
- **Deep MLP neural network**

You will:

- Load the dataset `bank-full.csv`
- Use categorical and numeric predictors to model the binary target variable `y`
- Preprocess data using:
  - One-hot encoding
  - Feature scaling
- Split the data into **training** and **validation** sets
- Fit a **basic MLP** model
- Extend it to a **deep MLP** with additional layers and dropout
- Evaluate models using:
  - Confusion matrix
  - Validation accuracy
  - Validation misclassification rate
- Compare basic vs deep neural networks
- Visualise training and validation performance
- Experiment with key parameters such as:
  - Number of layers and neurons
  - Dropout rates
  - Epochs and batch size

The notebook also includes very simple examples of:
- **CNNs** (for image data)
- **RNNs** (for sequence data)

All models are designed to run efficiently in **Google Colab**, with optional GPU acceleration.



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/05_small_deep_learning_colab_notebook.ipynb
)
---
### Hands-on 6: Model Interpretability (Global and Local Explanations)

This notebook introduces **model interpretability techniques** for machine learning models using **scikit-learn, LIME, and SHAP** on the **Bank Marketing dataset (`bank-full.csv`)**:

- **Permutation Feature Importance** (global feature ranking)
- **Partial Dependence Plots (PDP)** (global behaviour)
- **LIME** (local explanation)
- **SHAP** (local explanation)

You will:

- Load the dataset `bank-full.csv`
- Use categorical and numeric predictors to model the binary target variable `y`
- Preprocess data using:
  - One-hot encoding
  - Feature scaling
- Split the data into **training** and **validation** sets
- Fit a **Neural Network (MLPClassifier)** model using scikit-learn
- Evaluate the model using:
  - Confusion matrix
  - Validation accuracy
  - Validation misclassification rate
- Perform **global interpretability** using:
  - Permutation feature importance (feature ranking)
  - Partial dependence plots (average feature effects)
- Perform **local interpretability** using:
  - LIME (local surrogate explanations)
  - SHAP (Shapley value-based explanations)
- Compare global vs local explanations
- Analyse whether different interpretability methods provide consistent insights

The notebook highlights how different interpretability approaches provide **complementary perspectives** on a model’s behaviour, especially for complex models such as neural networks.

All methods are designed to run efficiently in **Google Colab**, with lightweight configurations for SHAP to reduce computation time.



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mehrdadgit/uow-MBAS922-applied-ml-ai-business/blob/main/Notebooks/06_global_local_interpretability_bank_marketing.ipynb
)
---

## How to Open in Google Colab

1. Click the **Open in Colab** badge above.
2. In Colab, select **File → Save a copy in Drive**.
3. Run the notebook cells in order.

---

© MBAS922 Applied ML and AI in Business, UOW