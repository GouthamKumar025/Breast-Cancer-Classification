<h1>Breast Cancer Classification Using Logistic Regression</h1>

<p>This repository contains code for a breast cancer classification project using logistic regression. The goal of this project is to predict whether a tumor is malignant or benign based on various features extracted from breast cancer biopsies.</p>

<h3>Table of Contents</h3>
<ul>
  <li>Introduction</li>
  <li>Dataset</li>
  <li>Installation</li>
  <li>Usage</li>
  <li>Results</li>
</ul>

<h3>Introduction</h3>
<p>Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate diagnosis are crucial for successful treatment. Machine learning techniques, such as logistic regression, can assist in the classification of breast tumors based on features derived from diagnostic tests.

In this project, logistic regression is employed to classify breast tumors as malignant or benign using a dataset containing various features computed from digitized images of breast cancer biopsies.</p>

<h3>Dataset<h3>
<p>The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset, which is publicly available in the UCI Machine Learning Repository. It consists of features computed from digitized images of fine needle aspirates (FNA) of breast masses, and the target variable indicates whether the tumor is malignant (M) or benign (B).</p>

<h3>Installation</h3>
<p>To run the code in this repository, you need to have Python installed along with the following libraries:</p>
<ul>
  <li>numpy</li>
  <li>pandas</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ul>

<p>You can install these dependencies using pip:</p>

```bash
     pip install numpy pandas scikit-learn matplotlib seaborn
```

<p>Clone this repository to your local machine using:</p>

```bash
git clone https://github.com/GouthamKumar025/breast-cancer-classification.git
```

<h3>Usage</h3>
<p>After installing the required dependencies and cloning the repository, you can run the breast_cancer_classification.ipynb notebook to train the logistic regression model and evaluate its performance.</p>

```bash
jupyter notebook breast_cancer_classification.ipynb
```
<p>Follow the instructions provided in the notebook to execute each cell and observe the results.</p>

<h3>Results</h3>
<p>The logistic regression model achieved an accuracy of X% on the test set. A detailed analysis of the model's performance, including precision, recall, and confusion matrix, is provided in the notebook.</p>
