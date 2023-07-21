## CD Index: Consolidation-Disruption Index Prediction of Academic Papers

### Overview:

This project focuses on predicting the Consolidation-Disruption (CD) index of academic papers. The CD index is a metric that quantifies the extent to which a paper consolidates or disrupts existing research in its domain. We employ various prediction models, including XGBoost, Random Forest, and Neural Network, to forecast the CD index. Additionally, we use Latent Dirichlet Allocation (LDA) to analyze the abstracts of papers and perform feature engineering to enhance model performance.

### Data Source:

The dataset used in this analysis is derived from It is derived from the alexandria3k package written by Professor Diomidis Spinellis, which you can download it through the `disruptive_science_assignment (1).ipynb` file. It consists of academic papers along with their CD index values, abstracts, and relevant features.

### CD Index Metric:

The CD index is a novel metric proposed in [https://www.nature.com/articles/s41586-022-05543-x], which measures the impact of an academic paper in terms of its consolidation (building upon existing research) or disruption (introducing novel ideas that diverge from the existing literature).

### Instructions to Replicate Results:

1. Install the required packages from the `requirements3.txt` file or the general `requirements.txt` in the parent folder:

   ```
   pip install -r requirements3.txt
   ```

2. Open the Jupyter Notebook `cd_index.ipynb` to view the code, data preprocessing, and model training.

### Notebooks and Files:

- `cd_index.ipynb`: Jupyter Notebook containing the code for CD index prediction and LDA analysis.
- `publications_graph.db`: SQLlite database, which you need to download as described in the data source section, containing the dataset used in the analysis.

### Dependencies:

- Scikit-learn
- NumPy
- Pandas
- XGBoost
- TensorFlow
- (refer to the requirements file for the detailed list of the dependencies)
