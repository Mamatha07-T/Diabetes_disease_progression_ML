# 🏥 Diabetes Disease Progression Prediction

A machine learning project that predicts diabetes disease progression using clinical health metrics. This project uses real-world data from the sklearn diabetes dataset and implements 5 different ML algorithms to find the most accurate predictor.

🎯 Overview

### What Does This Project Do?
This machine learning system predicts how diabetes will progress in patients over one year based on three key clinical measurements:
- **BMI (Body Mass Index)** - Obesity indicator
- **Blood Pressure** - Cardiovascular health marker
- **S5 (Blood Sugar Marker)** - Metabolic health indicator

### Why Is This Important?
Early prediction of disease progression helps:
- ✅ Identify high-risk patients needing immediate intervention
- ✅ Optimize treatment plans and resource allocation
- ✅ Enable preventive care before complications arise
- ✅ Reduce healthcare costs through early detection



## 📊 Dataset

### Source
- **Dataset**: Diabetes Dataset from scikit-learn
- **Origin**: Real patient data from medical study
- **Samples**: 442 diabetes patients
- **Features**: 10 baseline measurements (we use 3 most important)
- **Target**: Quantitative measure of disease progression one year after baseline

### Feature Description
Our model uses **3 clinically significant features**:

| Feature | Description | Clinical Significance | Range |
|---------|-------------|----------------------|-------|
| **BMI** | Body Mass Index | Obesity is a major diabetes risk factor | 15-45 |
| **BP** | Blood Pressure | Hypertension linked with complications | 80-180 mmHg |
| **S5** | Blood Sugar Marker | Direct metabolic risk indicator | 3.0-6.5 |

### Why These 3 Features?
- **Clinically Meaningful**: All three are modifiable risk factors
- **Highly Correlated**: Strongest correlations with disease progression
- **Practical**: Easy to measure in clinical settings
- **Interpretable**: Doctors understand these measurements well

---


## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
```

### Step 2: Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Or use the requirements file:
```bash
pip install -r requirements.txt
```

### Step 3: Run the Project
```bash
python diabetes_prediction.py
```

---

## 💻 Usage

### Basic Usage

1. **Run the script**:
```bash
python diabetes_prediction.py
```

2. **View model comparison**:
The script will automatically:
- Load and analyze the dataset
- Train 5 different models
- Display performance comparison
- Select the best model

3. **Make a prediction**:
When prompted, enter patient measurements:
```
Enter Patient Details:
BMI Range: 15 – 45
Blood Pressure Range: 80 – 180 mmHg
S5 (Blood Sugar Indicator) Range: 3.0 – 6.5

Enter BMI: 28.5
Enter Blood Pressure: 140
Enter S5 Value: 5.2
```

4. **Get results**:
```
Prediction Result:
Predicted Disease Progression Value: 168.45
Risk Category: Moderate Risk 🟠
```


## 📁 Project Structure

```
diabetes-prediction/
│
├── diabetes_prediction.py          # Main Python script
├── README.md                        # This file
├── PROJECT_DOCUMENTATION.md         # Detailed documentation
├── requirements.txt                 # Python dependencies
│
├── visualizations/                 # Generated plots
│   ├── correlation_heatmap.png
│   └── feature_importance.png
│
└── models/                         # Saved models (optional)
    └── best_model.pkl
```

---


<p align="center">Made with ❤️ for better diabetes care</p>
<p align="center">⭐ Star this repo if you found it useful!</p>
