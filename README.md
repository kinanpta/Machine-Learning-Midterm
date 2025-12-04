# Machine Learning Midterm – Telkom University

This repository contains my work for the **Machine Learning Midterm Examination** at **Telkom University**. All tasks follow the instructions provided by the lecturer and cover multiple topics including regression, classification, clustering, and model evaluation.

Because several datasets exceed GitHub’s file size limit, they **cannot be uploaded directly to the repository**. To keep everything accessible, all datasets used in this midterm are stored on Google Drive.

---

## Dataset Access

All datasets required for the midterm tasks can be downloaded from the link below:

👉 **Google Drive Folder:**  
(https://drive.google.com/drive/folders/1QLLxdfzGGystgrTS-RkiByVhiq3jnJ1h?usp=drive_link)

**Included datasets:**  
- `clusteringmidterm.csv`  
- `midterm-regresi-dataset.csv`  
- `train_transaction.csv`  
- `test_transaction.csv`  

These files are used across different sections of the midterm. Since their sizes range from hundreds of MBs, GitHub cannot host them directly.

---

## Midterm Summary

This midterm consists of tasks designed to evaluate understanding of core Machine Learning concepts:

### 1. Regression Task
- Exploratory Data Analysis (EDA)
- Data preprocessing & feature selection
- Model development (Linear Regression, etc.)
- Performance evaluation using RMSE, MAE, R²
- Error analysis & interpretation

### 2. Classification Task
- Handling imbalanced data
- Feature engineering
- Model comparison (e.g., Random Forest, Logistic Regression)
- Confusion matrix, ROC-AUC, accuracy analysis

### 3. Clustering Task
- Unsupervised learning with K-Means / Hierarchical clustering
- Finding optimal number of clusters (Elbow, Silhouette Score)
- Visualization and cluster interpretation

### 4. Discussion & Conclusion
- Key findings from each model
- Comparison between methods
- Insights gained from the dataset

---

## How to Run the Notebooks

Because the datasets are large, it is recommended to use **Google Colab**.

1. Open the `.ipynb` files in the `notebooks/` folder using Google Colab.  
2. Mount Google Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
```
3. Load your dataset:
```python
import pandas as pd
df = pd.read_csv('/content/drive/MyDrive/Machine-Learning-Midterm-Datasets/train_transaction.csv')
df.head()
```
4. Run the models and complete the analysis to the instructions.

---

## Tools & Libraries

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

## License

This project is licensed under the MIT License.
You are free to use, modify, and distribute the code for educational or research purposes.
