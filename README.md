# 🏦 Bank Marketing Campaign — Machine Learning Classification Project

> A comprehensive machine learning solution for predicting bank marketing campaign subscription success using advanced classification algorithms, data analysis, and an interactive web dashboard.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-00A3E0?style=for-the-badge&logo=xgboost&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

🌐 **Live Website:**
[View Live Website](https://khaledalzeer.github.io/bank-marketing-ml-project/Bank-Marketing-ML-Project/website/)

---

## 📌 About The Project

This is a **complete machine learning classification project** that predicts whether customers will subscribe to a bank's term deposit. The project combines advanced data science techniques with an interactive, production-ready web dashboard to present findings, visualizations, and model comparisons.

Using the **UCI Bank Marketing Dataset** (45,211 records), we implemented and compared **4 classification models** to identify the most effective approach for customer conversion prediction.

🏆 **Key Achievement:** **XGBoost achieved 88.2% accuracy with 0.79 AUC score** — the best-performing model

Built as an **academic machine learning project** at Al-Zaytoonah University of Jordan.

> ⚠️ **Note:** This project uses the UCI Bank Marketing Dataset for educational and research purposes.

---

## ✨ Project Highlights

- 🤖 **4 Advanced ML Models** — Logistic Regression, Decision Tree, Random Forest, XGBoost
- 📊 **Complete Data Pipeline** — Preprocessing, EDA, SMOTE balancing, model training, evaluation
- 🏆 **Model Comparison** — Detailed metrics (accuracy, precision, recall, F1, AUC)
- 📈 **ROC Curves & Confusion Matrices** — Visual performance analysis
- 🌐 **Interactive Website** — Comprehensive project documentation with smooth navigation
- 📱 **Responsive Design** — Mobile-friendly interface (desktop, tablet, mobile)
- 🎨 **Modern UI** — CSS3 animations, hover effects, gradient designs
- 💡 **Business Recommendations** — Actionable insights for banking campaigns
- 📚 **Jupyter Notebooks** — Complete analysis workflow (preprocessing → EDA → models)

---

## 🗂️ Project Structure

```
bank-marketing-project/
│
├── 📓 notebooks/
│   ├── Preprocessing.ipynb        ← Data Cleaning + SMOTE
│   ├── EDA.ipynb                  ← Exploratory Data Analysis
│   ├── Logistic_Regression.ipynb
│   ├── Decision_Tree.ipynb
│   ├── Random_Forest.ipynb
│   └── XGBoost.ipynb
│
├── 📊 data/
│   ├── bank-full.csv              ← Original Dataset (UCI — 45,211 rows)
│   └── processed/
│       ├── train.csv              ← After SMOTE (63,870 rows)
│       └── test.csv               ← Test Set (9,042 rows)
│
└── 🌐 website/
    ├── index.html                 ← Home page
    ├── roadmap.html               ← Project roadmap
    ├── dataset.html               ← Dataset overview
    ├── eda.html                   ← EDA visualizations
    ├── preprocessing.html         ← Data preprocessing details
    ├── logistic.html              ← Logistic Regression model
    ├── decision_tree.html         ← Decision Tree model
    ├── random_forest.html         ← Random Forest model
    ├── xgboost.html               ← XGBoost model (winner)
    ├── results.html               ← Final model comparison
    ├── conclusion.html            ← Conclusions & recommendations
    ├── team.html                  ← Team information
    │
    ├── css/
    │   └── style.css              ← All styling & animations
    │
    ├── js/
    │   └── main.js                ← Interactivity & animations
    │
    └── images/
        ├── eda/
        │   ├── target_distribution.png
        │   ├── demographics.png
        │   ├── financial_features.png
        │   ├── campaign_features.png
        │   └── correlation_heatmap.png
        ├── models/
        │   ├── confusion_matrix_lr.png
        │   ├── confusion_matrix_dt.png
        │   ├── confusion_matrix_rf.png
        │   ├── confusion_matrix_xgb.png
        │   ├── roc_curve_lr.png
        │   ├── roc_curve_dt.png
        │   ├── roc_curve_rf.png
        │   └── roc_curve_xgb.png
        └── team/
            ├── Khaled.jpg
            ├── Ahmad.jpeg
            └── Hamza.jpeg
```

---

## 📋 Website Sections

| # | Page | Description |
|---|---|---|
| 1 | 🏠 **Home** | Project overview, hero section, key metrics |
| 2 | 🗺️ **Roadmap** | Project workflow (preprocessing → EDA → models → results) |
| 3 | 📊 **Dataset** | Data source, features, statistics, and target variable |
| 4 | 📈 **EDA** | Exploratory visualizations, distributions, correlations |
| 5 | 🔧 **Preprocessing** | Data cleaning, encoding, SMOTE balancing techniques |
| 6 | 📈 **Logistic Regression** | Model details, performance, ROC curve, confusion matrix |
| 7 | 🌿 **Decision Tree** | Model details, performance, ROC curve, confusion matrix |
| 8 | 🌲 **Random Forest** | Model details, performance, ROC curve, confusion matrix |
| 9 | ⚡ **XGBoost** | Model details, performance (88.2% accuracy), best model |
| 10 | 🏆 **Results** | All 4 models compared side-by-side with rankings |
| 11 | 📝 **Conclusion** | Key findings, recommendations, future improvements |
| 12 | 👥 **Team** | Project team members, roles, tech stack, supervisor |

---

## 🚀 Model Performance — Final Comparison

### 🥇 XGBoost — Best Model (🏆 Winner)

| Metric | Score | Rating |
|--------|-------|--------|
| Accuracy | **88.2%** | ⭐⭐⭐⭐⭐ |
| Precision | **0.50** | ⭐⭐⭐⭐ |
| Recall | **0.42** | ⭐⭐⭐⭐ |
| F1-Score | **0.46** | ⭐⭐⭐⭐⭐ |
| AUC Score | **0.79** | ⭐⭐⭐⭐⭐ |

### 📊 Performance Ranking

| Rank | Model | Accuracy | F1 (C1) | AUC | Winner |
|------|-------|----------|---------|-----|--------|
| 🥇 1st | ⚡ XGBoost | **88.2%** | **0.46** | **0.79** | 🏆 |
| 🥈 2nd | 🌲 Random Forest | 87.9% | 0.40 | 0.77 | — |
| 🥉 3rd | 📈 Logistic Regression | 87.6% | 0.42 | 0.73 | — |
| 4th | 🌿 Decision Tree | 81.3% | 0.32 | 0.61 | — |

---

## 🔍 Key Findings

### 📊 Data Insights

- **Original Dataset:** 45,211 customer records
- **Features:** 17 attributes (demographics, financial, campaign-related)
- **Class Imbalance:** 11.7% subscriptions → Balanced to 50% using SMOTE
- **Train Set:** 63,870 samples | **Test Set:** 9,042 samples

### 🎯 Model Insights

1. **XGBoost Dominance** — Sequential error-correction captures complex patterns effectively
2. **High Accuracy** — All top-3 models achieve 87%+ accuracy
3. **Recall is Critical** — Better to contact potential customers than miss opportunities
4. **Random Forest Trade-off** — Decent precision (0.48) but lowest recall (0.34) among top models

### 💡 Business Recommendations

1. **Deploy XGBoost** for production customer scoring
2. **Focus on Recall Optimization** — Maximize customer reach
3. **Optimize Campaign Duration** — Longer interactions → Higher conversion
4. **Demographic Targeting** — Tailor campaigns by age and financial profile

---

## 🛠️ Technologies & Tools

### 🐍 Machine Learning Stack

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core programming language |
| **Pandas & NumPy** | Data manipulation and numerical computing |
| **Scikit-learn** | Classical ML algorithms (Logistic Regression, Decision Tree, Random Forest) |
| **XGBoost** | Gradient boosting framework |
| **Imbalanced-learn (SMOTE)** | Class balancing technique |
| **Matplotlib & Seaborn** | Data visualization |

### 🌐 Web Development Stack

| Tool | Purpose |
|------|---------|
| **HTML5** | Semantic markup |
| **CSS3** | Responsive design + animations |
| **JavaScript (Vanilla)** | Interactivity + smooth navigation |
| **Font Awesome 6** | Icon library |
| **Responsive Grid** | Mobile-first approach |

### 🧪 Development Tools

| Tool | Purpose |
|------|---------|
| **Jupyter Notebooks** | Interactive analysis |
| **Git & GitHub** | Version control |
| **VS Code** | Code editor |

---

## 📈 Data Pipeline Workflow

```
Data Collection (UCI Bank Marketing)
        ↓
Preprocessing (Cleaning + Encoding + SMOTE)
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering & Selection
        ↓
Model Training (4 Algorithms)
    ├── Logistic Regression
    ├── Decision Tree
    ├── Random Forest
    └── XGBoost
        ↓
Model Evaluation (Metrics + Visualizations)
    ├── Confusion Matrices
    ├── ROC Curves
    └── Performance Comparison
        ↓
Results & Recommendations
        ↓
Web Documentation & Dashboard
```

---

## 🚀 How to Use

### Run Jupyter Notebooks

```bash
# Clone repository
git clone https://github.com/khaledAlzeer/bank-marketing-ml-project.git
cd bank-marketing-ml-project

# Navigate to notebooks
cd notebooks/

# Launch Jupyter
jupyter notebook

# Run notebooks in order:
# 1. Preprocessing.ipynb
# 2. EDA.ipynb
# 3. Logistic_Regression.ipynb
# 4. Decision_Tree.ipynb
# 5. Random_Forest.ipynb
# 6. XGBoost.ipynb
```

### View Website Locally

```bash
# Navigate to website directory
cd website/

# Option 1: Open directly in browser
# Double-click index.html

# Option 2: Use local server (recommended)
python -m http.server 8000

# Then open browser and visit:
# http://localhost:8000
```

---

## 👥 Project Team

| Member | Role |
|--------|------|
| 👨‍💼 **Khaled Alzeer** | Project Manager · Data Analyst · Python Developer · Full-Stack Developer . Documentation|
| 👨‍💼 **Ahmad** | Team Member · Data Processing & Model Evaluation |
| 👨‍💼 **Hamza** | Team Member · Data Analysis & Documentation |


- 👨‍🏫 **Supervised by:** Ms. Nesreen Hamad
- 🏫 **Institution:** Al-Zaytoonah University of Jordan (ZUJ)
- 📅 **Academic Year:** 2026

---

## 📚 Dataset Information

**Source:** [UCI Machine Learning Repository — Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

**Citation:**
```
Moro, S., Cortez, P., & Rita, P. (2014).
A data-driven approach to predict the success of bank telemarketing.
Decision Support Systems, 62, 22-31.
```

### Dataset Features

| Category | Features |
|----------|---------|
| 👤 **Demographics** | Age, Job, Marital Status, Education, Default, Housing Loan, Personal Loan |
| 💰 **Financial** | Balance (account balance in euros) |
| 📞 **Campaign Info** | Contact Type, Day, Month, Duration, Campaign Count, pdays, previous, poutcome |
| 📊 **Economic Indicators** | Emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed |
| 🎯 **Target Variable** | Subscription: Yes (1) / No (0) — Imbalanced: 11.7% positive class |

---

## 🎓 Academic Context

| Detail | Information |
|--------|-------------|
| 🏫 Institution | Al-Zaytoonah University of Jordan (ZUJ) |
| 📚 Course | Machine Learning & Data Science |
| 📅 Year | 2026 |
| 👨‍🏫 Supervisor | Ms. Nesreen Hamad |
| 🎯 Project Type | Classification & Predictive Analytics |
| 📊 Dataset | UCI Bank Marketing (Public) |

---

## 📂 Key Files

| File | Purpose |
|------|---------|
| `notebooks/Preprocessing.ipynb` | Data cleaning, encoding, SMOTE balancing |
| `notebooks/EDA.ipynb` | Exploratory visualizations and analysis |
| `notebooks/XGBoost.ipynb` | Best-performing model implementation |
| `website/index.html` | Project homepage |
| `website/results.html` | All models compared side-by-side |
| `website/css/style.css` | All styling and animations |
| `website/js/main.js` | Navigation and interactivity |
| `data/bank-full.csv` | Original dataset (41,188 rows) |
| `data/processed/train.csv` | SMOTE-balanced training set |
| `data/processed/test.csv` | Test set |

---

## ✨ Features Showcase

### 🌐 Website Features

- ✅ **12 Interactive Pages** — Complete project documentation
- ✅ **Responsive Design** — Works on desktop, tablet, and mobile
- ✅ **Smooth Navigation** — Dropdown menus, smooth scrolling
- ✅ **Visual Comparisons** — Side-by-side model metrics
- ✅ **ROC Curves & Confusion Matrices** — Model performance visualization
- ✅ **Mobile Menu** — Full-screen navigation on small screens
- ✅ **Hero Section** — Animated intro with project overview
- ✅ **Team Information** — Project members and roles
- ✅ **Technology Stack Display** — Tools and libraries used

### 🧬 ML Pipeline Features

- ✅ **Data Preprocessing** — Missing values, encoding, scaling
- ✅ **SMOTE Balancing** — Handle class imbalance (11.7% → 50%)
- ✅ **EDA Analysis** — Distribution, correlation, patterns
- ✅ **4 Model Implementations** — Classic to advanced algorithms
- ✅ **Comprehensive Metrics** — Accuracy, precision, recall, F1, AUC
- ✅ **Cross-Validation** — Robust performance evaluation

---

## 📊 Model Comparison Summary

### Why XGBoost Won?

| Reason | Detail |
|--------|--------|
| 🎯 Highest Accuracy (88.2%) | Best overall classification |
| 🏅 Best F1-Score (0.46) | Balanced precision-recall |
| 📈 Highest AUC (0.79) | Excellent discrimination ability |
| ⚡ Advanced Algorithm | Sequential error correction |
| 🔍 Handles Complexity | Captures non-linear patterns |

### Trade-offs Analysis

- **Random Forest:** Decent precision (0.48) but lowest recall (0.34) among top models — More conservative
- **Logistic Regression:** Balanced approach (Precision: 0.46, Recall: 0.38) — simpler model
- **Decision Tree:** Lowest performance (Precision: 0.28, AUC: 0.61) — Prone to overfitting

---

## 🔗 Important Links

- 🌐 **Live Website:** [View Live Website](https://khaledalzeer.github.io/bank-marketing-ml-project/Bank-Marketing-ML-Project/website/)
- 📦 **Repository:** [github.com/khaledAlzeer/bank-marketing-ml-project](https://github.com/khaledAlzeer/bank-marketing-ml-project)
- ☁️ **Google Drive (Project Files + Colab Notebooks):** [ML Project Folder](https://drive.google.com/drive/folders/1w9RMLklaXUzbeOahmasf52B8WRysMDAc)
- 📊 **Dataset Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## 📄 License

This project is created for educational purposes as part of the Machine Learning course at Al-Zaytoonah University of Jordan.

---

## 🤝 Contributing

This is an academic project. For improvements or suggestions, please contact the project team.

---

## 📞 Contact & Support

**Project Manager: Khaled Alzeer**

- 🐙 GitHub: [@khaledAlzeer](https://github.com/khaledAlzeer)
- 📧 Email: kalzyr61@gmail.com
- 👨‍🏫 Supervisor: Ms. Nesreen Hamad
- 🏫 Institution: Al-Zaytoonah University of Jordan (ZUJ)

---

## 🎯 Project Status

### ✅ COMPLETE & PRODUCTION-READY

- [x] Data preprocessing and exploration
- [x] Model training and evaluation
- [x] Website development and design
- [x] Documentation and visualization
- [x] Live deployment

---

## 🏆 Achievements

| Achievement | Detail |
|-------------|--------|
| 🥇 Best Model | XGBoost — 88.2% Accuracy · 0.79 AUC Score |
| 📊 Full ML Pipeline | End-to-end data science workflow |
| 🌐 Interactive Dashboard | Professional web presentation |
| 📚 Full Documentation | Jupyter notebooks + website |
| 👥 Team Collaboration | Multi-disciplinary approach |
