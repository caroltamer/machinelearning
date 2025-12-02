# Healthcare Provider Fraud Detection Project



## Project Overview
Machine learning project to detect fraudulent healthcare providers for Medicare using the Healthcare Provider Fraud Detection dataset.

## Repository Structure
- `data/`: Dataset files (gitignored)
- `notebooks/`: Jupyter/Colab notebooks for analysis
- `reports/`: Technical report and presentation

## 📊 Current Progress

### ✅ **Notebook 1 Completed - Data Exploration & Feature Engineering**
### ✅ **Notebook 2 Completed** - Model Training  
### ✅ **Notebook 3 Completed** - Model Evaluation & Business Impact

**Key Accomplishments:**
- **Data Loading & Quality Checks** - Successfully loaded 4 healthcare datasets
- **Target Analysis** - Explored fraud vs non-fraud distribution (imbalanced dataset)
- **Feature Engineering** - Created comprehensive provider-level features:
  - Claims volume and inpatient/outpatient ratios
  - Financial metrics (total reimbursement, average claim amounts)
  - Patient demographics (average age, chronic conditions)
  - Physician utilization patterns
- **Final Dataset** - Built processed dataset with 14 features ready for modeling

**Files Created:**
- `01_data_exploration_and_feature_engineering.ipynb` - Complete analysis notebook
- `final_provider_dataset.csv` - Processed dataset for modeling

## 🚀 Next Steps
- **Notebook 2** - Model Training & Evaluation
  - Load processed dataset
  - Train machine learning models (Random Forest, XGBoost, etc.)
  - Evaluate performance metrics
  - Feature importance analysis

## Setup
1. Clone this repository: `git clone https://github.com/caroltamer/machine-learning.git`
2. Download dataset from Kaggle and place in `data/` folder
3. Open notebooks in Google Colab or Jupyter

**Final Results:**
*Will be updated after model training and evaluation*
- **Best Model**: [Add which model performed best - e.g., Random Forest]
- **Fraud Detection Rate**: 85.1% (86 out of 101 fraudulent providers detected)
- **Key Metrics**:
  - PR-AUC: [Add value]
  - ROC-AUC: [Add value]
  - Precision (Fraud): [Add value]
  - Recall (Fraud): [Add value]
 
- **Business Impact:**
- Reduced manual investigation burden through intelligent prioritization
- Cost savings through targeted fraud detection
- Actionable insights for fraud investigators



## 🚀 Project Complete
All three notebooks successfully executed end-to-end fraud detection pipeline.
