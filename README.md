# Applied Machine Learning Projects

This repository contains three applied machine learning projects completed as part of the Applied Machine Learning university course of my senior year. Each project focuses on exploring real-world datasets and applying various machine learning and data science techniques. The complexity of the projects gradually increases, from creating meaningful plots, performing EDA and feature engineering to comparing various predictive models. Below is a brief overview of each project:

## Project 1: Economic Connectedness of United States

Project 1 involves replicating plots using Seaborn based on a research paper that explores the economic connectedness of the United States. The goal is to visualize and analyze economic relationships to gain insights into the country's economic landscape.

## Project 2: Sport Repression and Big Sporting Events (Argentina 1978)

Project 2 delves into the topic of sport repression, evaluating the level of repression in a country that hosts a significant sporting event. The project includes plots and regression analysis to examine the historical context of Argentina in 1978 and its correlation with the sports event held during that period.

## Project 3: Predicting CD Index of Academic Papers

Project 3 is the centerpiece of this repository, focusing on predicting the CD Index of academic papers. Various prediction models, including XGBOOST, Random Forest, Multilayer Perceptron (MLP) Regressor, and a Neural Network, have been employed to achieve this task. Additionally, Latent Dirichlet Allocation (LDA) has been used to analyze the abstracts of the papers and assist in feature engineering.

### Techniques and Methods Used:

- **Feature Engineering:** The projects extensively utilize feature engineering techniques to extract meaningful features from the academic paper dataset, enhancing the predictive power of the machine learning models. Additionally, scaling of variables has been performed to standardize the data and improve model convergence.

- **Latent Dirichlet Allocation (LDA):** LDA has been applied to analyze the abstracts of the academic papers, helping to discover underlying topics and themes within the dataset. This analysis has been used in feature engineering and to gain further insights into the research papers.

- **Multilayer Perceptron (MLP) Regressor:** Apart from other prediction models, an MLP Regressor has been utilized for its ability to handle non-linear relationships and capture complex patterns in the data.

- **XGBOOST and Random Forest:** These powerful ensemble learning techniques have been employed to build high-performance predictive models for the CD Index and sport repression projects.

- **Neural Network:** In addition to the MLP Regressor, a more complex neural network architecture has been explored to model and predict the CD Index of academic papers, leveraging deep learning capabilities.

- **Loss Plotting:** For models trained iteratively, such as Neural Networks, the history of the loss function has been plotted to visualize the model's convergence and identify potential overfitting or underfitting issues.

However, please note that the list is not exhaustive, as I utilized a wide range of techniques to tackle different challenges and gain valuable insights into predictive machine learning.

For a more in-depth understanding of the skills and techniques employed in these projects, I invite you to explore the jupyter notebooks of each project. There, you will find a detailed account of the data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation processes, giving you a more comprehensive view of the applied machine learning concepts.

## Directory Structure

The repository is organized as follows:

- `/economic_connectedness`: Contains code, data, and documentation related to Economic Connectedness project.
- `/sport_repression`: Contains code, data, and documentation related to Sport Repression project.
- `/cd_index`: Contains code, data, and documentation related to CD Index Prediction project.

## Prerequisites

Before running the code for each project, make sure you have the following dependencies installed:

- Python3
- Jupyter Notebook
- Libraries: Pandas, NumPy, Seaborn, Scikit-learn, XGBOOST, MLPRegressor, and others (Refer to `requirements.txt` for a detailed list)
- There is a parent `requirements.txt` for all the projects, as well as separate ones for each project. Feel free to install the desired `requirements.txt` file or the general one if you want to replicate all the projects.

## Instructions

To replicate the results or explore the projects:

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the specific project's directory (e.g., `/cd_index`).
3. Install the necessary dependencies using `pip install -r requirements1/2/3.txt`.
4. Open the Jupyter Notebook or Python script corresponding to the project.
5. Execute the code cells (if applicable) to see the visualizations and analysis.
6. For `cd_index`, follow the instructions in the notebook to use the trained models and make predictions on new data.

Feel free to explore the datasets and code to gain insights into the applied machine learning concepts and methodologies.

---
