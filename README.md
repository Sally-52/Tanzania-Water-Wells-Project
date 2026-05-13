#  Tanzania Water Wells — Predictive Analysis

> Predicting the functional status of water wells across Tanzania to support data-driven infrastructure decisions.

---

##  Project Overview

Access to clean water is a fundamental human right — yet thousands of water points across Tanzania are non-functional or in need of repair. This project uses real-world water well data to build a machine learning classification model that predicts whether a given well is **functional**, **non-functional**, or **in need of repair**.

The goal: help governments and NGOs prioritize maintenance efforts and allocate resources more effectively.

-

##  Objectives

- Clean and preprocess a large, messy real-world dataset
- Perform exploratory data analysis (EDA) to uncover patterns in well functionality
- Build and evaluate a classification model to predict well status
- Visualize key findings to communicate insights clearly

## Dataset

- **Source:** [DrivenData — Pump it Up: Data Mining the Water Table](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/)
- **Size:** 59,400 water point records across Tanzania
- **Target Variable:** `status_group` — Functional / Non-Functional / Functional Needs Repair
- **Features include:** GPS coordinates, installer, funder, water quality, quantity, pump type, construction year, and more


## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas & NumPy | Data cleaning and manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Machine learning model building & evaluation |
| Jupyter Notebook | Interactive development environment |

---

##  Project Workflow

### 1. Data Cleaning
- Handled missing values and zero-filled coordinates
- Encoded categorical variables
- Removed duplicate and irrelevant columns

### 2. Exploratory Data Analysis
- Mapped well locations and functionality by region
- Analyzed relationships between water quantity, quality, and pump status
- Identified key features correlated with well failure

### 3. Modelling
- Trained a classification model to predict well status
- Evaluated using accuracy, precision, recall, and confusion matrix
- Compared multiple models to select the best performer

### 4. Key Findings
- Wells installed by certain funders showed significantly higher failure rates
- Older construction years correlated strongly with non-functionality
- Water quantity labeled "dry" was the strongest predictor of failure


##  Results

The model successfully classified well status with meaningful accuracy, providing actionable insights for prioritizing repair and maintenance across regions.

##  How to Run

```bash
# Clone the repository
git clone https://github.com/Sally-52/<repo-name>.git
cd <repo-name>

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch the notebook
jupyter notebook
```

---

## 👩🏾‍💻 Author

**Sally Njeri Kinyanjui**  
Data Scientist | Computer Science Professional  
[LinkedIn](https://www.linkedin.com/in/) · [GitHub](https://github.com/Sally-52)

---

> *This project was completed as part of my data science training. The dataset is publicly available via DrivenData.*
