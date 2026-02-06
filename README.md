🏥 Diabetes Progression Prediction - Machine Learning Project

> A comprehensive predictive model for diabetes disease progression using real-world medical data

🎯 Project Overview

This project builds a machine learning model to **predict diabetes disease progression** one year after baseline measurements. The model helps healthcare providers identify high-risk patients early and personalize treatment plans.

📊 Dataset Information

**Source:** Scikit-learn's diabetes dataset (real-world medical data)
- **Patients:** 442 diabetes patients
- **Features:** 10 baseline physiological measurements
- **Target:** Quantitative measure of disease progression (1 year after baseline)

### Features:
| Feature | Description |
|---------|-------------|
| age | Age (normalized) |
| sex | Gender (normalized) |
| bmi | Body mass index |
| bp | Average blood pressure |
| s1-s6 | Six blood serum measurements |

**Note:** All features are normalized and centered around zero.

---

## 🚀 Installation & Setup

### Prerequisites
```bash
Python 3.8 or higher
```

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

**Required Libraries:**
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter (optional, for notebook)

---

## ▶️ How to Run

### Option 1: Run Jupyter Notebook (Recommended)
```bash
jupyter notebook health_prediction_model.ipynb
```
Then click "Run All" to execute all cells.

### Option 2: Run Python Script
```bash
python complete_diabetes_prediction.py
```

### Option 3: Run Standalone Script
```bash
python health_prediction_script.py
```

**Output:** The script will:
1. Display analysis results in the console
2. Show visualizations (charts and graphs)
3. Save trained model as `best_model.pkl`

---

## 📁 Project Structure

```
diabetes-prediction/
│
├── health_prediction_model.ipynb    # Main Jupyter notebook with full analysis
├── complete_diabetes_prediction.py  # Complete Python script (all-in-one)
├── health_prediction_script.py      # Simplified standalone script
│
├── requirements.txt                 # Python dependencies
├── README.md                        # This file
├── DEPLOYMENT.md                    # Deployment guide
│
└── outputs/                         # Generated outputs
    ├── best_model.pkl              # Trained model
    ├── feature_names.pkl           # Feature list
    └── model_metadata.pkl          # Model information
```


## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Programming language |
| **NumPy** | Numerical computations |
| **Pandas** | Data manipulation |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **Scikit-learn** | Machine learning models |
| **Jupyter** | Interactive development |

---

## 📊 Visualizations

The project includes comprehensive visualizations:

✅ **Distribution Plots** - Target variable analysis  
✅ **Correlation Heatmap** - Feature relationships  
✅ **Scatter Plots** - Feature-target relationships  
✅ **Model Comparison Charts** - Performance metrics  
✅ **Prediction Analysis** - Actual vs predicted  
✅ **Residual Plots** - Error distribution  
✅ **Feature Importance** - Top predictors



