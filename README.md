# 🔍 NCRB 2021 Crime Motive Analytics

### Data-Driven Crime Analysis, Machine Learning & Intelligence Dashboard

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

**NCRB 2021 Crime Motive Analytics** is a Data Science and Machine Learning project that analyzes crime motive statistics across Indian States and Union Territories using the National Crime Records Bureau (NCRB) 2021 dataset.

The project applies Exploratory Data Analysis (EDA), statistical techniques, machine learning algorithms, clustering, dimensionality reduction, and association rule mining to identify patterns, understand regional differences, and explore relationships among recorded crime motives.

It also generates a professional analytical dashboard and structured reports to communicate key findings through data visualization.

## 🎯 Project Objectives

- Analyze crime motive distribution across Indian States and Union Territories.
- Identify the most frequently recorded crime motives.
- Compare regional crime statistics and rankings.
- Examine relationships and correlations among crime motives.
- Analyze regional concentration using Pareto analysis.
- Apply machine learning algorithms for exploratory modeling.
- Discover regional patterns using clustering techniques.
- Reduce data dimensions using Principal Component Analysis (PCA).
- Identify frequently co-occurring motive categories using association analysis.
- Develop an integrated dashboard for analytical reporting.

## 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| Programming Language | Python 3.13 |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistical Analysis | Descriptive Statistics, Correlation |
| Development Environment | Anaconda Spyder |
| Dataset Format | CSV |
| Version Control | Git & GitHub |

## 📊 Project Workflow

1. **Data Collection:** Load NCRB 2021 crime motive statistics.
2. **Data Preprocessing:** Handle missing values, convert numeric columns, validate records, and prepare analytical datasets.
3. **Exploratory Data Analysis:** Analyze motive distributions, regional comparisons, and statistical relationships.
4. **Machine Learning:** Apply regression and classification algorithms for exploratory analysis.
5. **Clustering:** Group regions based on crime motive composition.
6. **Dimensionality Reduction:** Apply PCA to study underlying data patterns.
7. **Association Analysis:** Identify frequently co-occurring crime motive categories.
8. **Dashboard Development:** Combine major analytical findings into a unified visualization dashboard.
9. **Report Generation:** Export analytical results, model evaluations, and project summaries.

## 📈 Analytical Modules

### 1. Crime Motive Distribution Analysis
- Identify the top 10 recorded crime motives.
- Calculate motive-wise case distribution.
- Visualize leading motives using bar charts and donut charts.

### 2. State/UT Comparison
- Rank regions according to recorded cases.
- Compare the highest-count States and Union Territories.
- Identify regional variations in recorded statistics.

### 3. Regional Motive Composition
- Generate a regional motive composition heatmap.
- Compare motive percentages within individual regions.
- Identify differences in regional motive profiles.

### 4. Pareto Concentration Analysis
- Rank regions based on recorded cases.
- Calculate cumulative percentage contributions.
- Examine the concentration of recorded cases across regions.

### 5. Correlation & Relationship Analysis
- Analyze relationships between selected motive categories.
- Generate correlation matrices.
- Visualize statistical associations.

## 🤖 Machine Learning Implementation

The project explores multiple machine learning algorithms.

### Regression Algorithms
- Linear Regression
- Random Forest Regressor

Evaluation metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Classification Algorithms
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest Classifier

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score

### Clustering Algorithms
- K-Means Clustering
- Hierarchical Agglomerative Clustering

Evaluation:
- Silhouette Score
- Cluster visualization using PCA

### Dimensionality Reduction
- Principal Component Analysis (PCA)
- Explained Variance Analysis
- Cumulative Variance Visualization

### Association Rule Mining
- Support
- Confidence
- Lift

The association analysis examines frequently co-occurring motive categories across regions.

## 📊 Professional Dashboard

The project generates an integrated dashboard containing:

- Total Recorded Cases
- Number of Regions Analyzed
- Number of Motive Categories
- Leading Crime Motives
- Highest-Count Regions
- Regional Motive Composition Heatmap
- Regional Concentration Analysis
- Association Rule Analysis
- PCA Explained Variance
- Classification F1-Score Comparison

## 📁 Project Structure

```text
NCRB-2021-Crime-Motive-Analytics/
│
├── NCRB_Crime_Analytics.py
│
├── README.md
│
├── dataset/
│   └── NCRB_2021.csv
│
├── outputs/
│   └── NCRB_Professional_Project_Output/
│       │
│       ├── cleaned_dataset.csv
│       ├── 01_motive_summary.csv
│       ├── 02_state_ranking.csv
│       ├── 03_regional_motive_composition_pct.csv
│       ├── 04_pareto_concentration.csv
│       ├── 06_model_evaluation.csv
│       ├── 07_clustering_assignments.csv
│       ├── 08_pca_variance.csv
│       ├── 09_association_rules.csv
│       │
│       ├── analysis_01_motive_distribution.png
│       ├── analysis_02_regional_comparison.png
│       ├── analysis_03_motive_heatmap.png
│       ├── analysis_04_pareto.png
│       ├── analysis_05_relationships.png
│       │
│       ├── model_01_classification_diagnostics.png
│       ├── model_02_clustering_pca.png
│       ├── model_03_pca_variance.png
│       │
│       ├── NCRB_2021_Professional_Dashboard.png
│       └── README_project_results.txt
```

*Note: The output directory and dataset folder are created or organized separately from the Python script. Some output files are generated conditionally depending on dataset characteristics.*

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/NCRB-2021-Crime-Motive-Analytics.git
```

### Step 2: Navigate to Project Directory

```bash
cd NCRB-2021-Crime-Motive-Analytics
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Step 4: Configure Dataset Path

Place the NCRB 2021 CSV dataset in your Downloads folder or update the dataset path in the Python script.

Example:

```python
download_folder = r"C:\Users\Lenovo\Downloads"
```

The script automatically searches for the appropriate CSV file in that folder.

### Step 5: Run the Project

```bash
python NCRB_Crime_Analytics.py
```

Alternatively, execute the script using Anaconda Spyder.

## 📦 Output Files

The project automatically generates:

- Cleaned analytical dataset.
- Motive-wise statistical summaries.
- State/UT ranking tables.
- Regional composition percentages.
- Machine learning evaluation results.
- Clustering assignments.
- PCA explained variance results.
- Association rule results.
- High-resolution analytical charts.
- Professional crime intelligence dashboard.
- Project summary report.

## 🔍 Key Insights

The project is designed to help explore:

- Which crime motive categories have the highest recorded counts.
- How recorded cases differ across States and Union Territories.
- Which regions have similar motive compositions.
- How recorded cases are distributed among regions.
- Which motive categories frequently occur together across regions.
- How regional patterns can be grouped using unsupervised learning.

Actual findings should be interpreted from the generated dataset analysis rather than assumed in advance.

## ⚠️ Limitations

- The analysis uses aggregated NCRB 2021 data.
- Recorded case counts do not necessarily represent actual crime prevalence.
- The analysis does not account for population differences between regions.
- Correlation does not establish causation.
- Regression and classification experiments use features and labels derived from the same aggregate dataset, so their results are not independent predictive evidence.
- Clustering results are exploratory and depend on feature scaling and parameter selection.
- The project should not be used for crime prediction, policing decisions, or policy conclusions without additional validated data.

## 🚀 Future Enhancements

- Integrate NCRB datasets from multiple years.
- Develop population-adjusted crime rate analysis.
- Build an interactive dashboard using Streamlit or Power BI.
- Implement geographic crime visualization.
- Introduce temporal trend analysis.
- Explore more rigorous predictive modeling using independent features and future-year validation.
- Develop automated data ingestion and reporting.

## 👨‍💻 Author

**Dheeraj**  
B.Tech Computer Science & Engineering  
Data Science Enthusiast

**Areas of Interest:**  
Data Science | Machine Learning | Data Analytics | Data Visualization | Python

## 📄 Data Source & Acknowledgement

Dataset: National Crime Records Bureau (NCRB), India — 2021 crime statistics.

Please include the original dataset source, publication title, and applicable usage or attribution terms when distributing the dataset.

## 📜 License

This project is intended for educational and research purposes. Add an appropriate open-source license before permitting reuse or redistribution.

---

⭐ If you find this project useful, consider giving the repository a star!

**Developed with Python, Data Science, and Machine Learning.**
