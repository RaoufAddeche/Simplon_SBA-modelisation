# <p align="center">Loan Approval Prediction for US SBA</p>
<p align="center">
    <img src="images/project_logo.png" alt="Project Logo" width="200">
</p>

## ➤ Menu

* [➤ Project Structure](#-project-structure)
* [➤ How to Run](#-how-to-run)
* [➤ Requirements](#-requirements)
* [➤ Outputs](#-outputs)
* [➤ Evaluation Criteria](#-evaluation-criteria)
* [➤ Performance Metrics](#-performance-metrics)
* [➤ License](#-license)
* [➤ Authors](#-authors)

---

## Project Structure

This project is divided into multiple phases corresponding to different development stages:

### **Phase 1: Machine Learning**
This phase includes:
- **Data Cleaning**: `notebooks/data_cleaning.ipynb`
- **Exploratory Data Analysis (EDA)**: `notebooks/EDA.ipynb`
- **Modeling and Selection**: `notebooks/modeling.ipynb`
- **Database for Optuna**: `database/optuna.db`
- **Source Data**:
  - `data/dataset.csv`
  - `data/dataset_cleaned.csv`
- **Dependencies File**: `requirements.txt`

### **Phase 2: Web Development (In Progress)**
- API with **FastAPI**  
- Web Interface with **Django**  

### **Phase 3: Deployment**
- Containerization with **Docker**  
- Hosting on **Azure**  

---

## How to Run

Follow these steps to execute the project:

1. **Clone the repository**:

```bash
git clone https://github.com/username/project_name.git
cd project_name
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

3. **Run the notebooks for analysis and modeling** (via Jupyter Notebook or VS Code).  

4. **Upcoming: Launching the API and Web Application**.

---

## Requirements

- Python >= 3.x
- Required Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost / catboost / lightgbm
  - optuna
  - matplotlib / seaborn
  - FastAPI (for API, upcoming)
  - Django (for web interface, upcoming)
- Additional Tools:
  - Docker (for containerization, upcoming)
  - Azure (for deployment, upcoming)

---

## Outputs

The project aims to predict whether a company will repay its loan or not.  

### **Expected Outputs:**
- **Model Scores** (accuracy, precision, recall, F1-score, ROC-AUC).
- **Feature Importance Visualizations**.
- **SHAP Value Charts for Model Interpretability**.

---

## Evaluation Criteria

### **Context**
The US Small Business Administration (SBA) seeks to optimize loan approvals for small businesses by predicting their repayment capacity.

### **Project Organization**
- **Phase 1: Machine Learning** (Feb 3 - Feb 14)
  - Data cleaning and exploratory analysis
  - Modeling and selecting the best algorithms
  - Interpreting results using SHAP
- **Phase 2: API and Web Application Development** (Feb 17 - Feb 28)
  - API with FastAPI
  - Frontend with Django
- **Phase 3: Deployment** (Mar 3 - Mar 14)
  - Containerization with Docker
  - Hosting on Azure

### **Expected Deliverables**
- **Phase 1**: Cleaning, EDA, and modeling notebooks + oral presentation
- **Phase 2**: API and Web Application source code
- **Phase 3**: Deployment on Azure + screenshot of deployed instance

---

## Performance Metrics

Model performance will be evaluated based on multiple criteria:

- **Model Quality**:
  - F1 Score, ROC-AUC, Precision-Recall
  - Feature importance
- **Code and Documentation Clarity**
- **Proper Use of Git** (regular commits, structured branches)
- **Model Interpretability** (SHAP values)
- **Functional Deployment of API and Web Application**

---

## License

[MIT License](LICENSE)

---

## Authors
**Raouf Addeche**
**Khadija Aassi**
**Ludivine Raby**  
<a href="https://github.com/YourGitHubProfile" target="_blank">
    <img loading="lazy" src="images/github-mark.png" width="30" height="30" style="vertical-align: middle; float: middle; margin-left: 30px;" alt="GitHub Logo">
</a>
