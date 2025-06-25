# 🚢 Titanic - Exploratory Data Analysis (EDA)

Unlocking the stories hidden in data from one of the most iconic shipwrecks in history.

---

## 🎯 Objective

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset. We'll explore trends, distributions, correlations, and outliers to understand which factors influenced passenger survival.

---

## 📊 Dataset Overview

- **Dataset**: Titanic Passenger Manifest  
- **Format**: CSV  
- **Source**: [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic)  
- **Features**:
  - Passenger details (Age, Gender, Class, etc.)
  - Family relations (SibSp, Parch)
  - Fare and Embarkation
  - Survival outcome

---

## 🧰 Tools & Libraries

| Tool         | Purpose                        |
|--------------|--------------------------------|
| `Pandas`     | Data manipulation              |
| `Seaborn`    | Statistical visualizations     |
| `Matplotlib` | Plotting and customization     |
| `Plotly`     | *(optional)* Interactive plots |

---

## 📌 EDA Process

### 🧮 1. Descriptive Statistics
- Checked data structure using `.info()`
- Calculated summary stats via `.describe()`, `.median()`
- Counted missing values and handled `inf` / `-inf`

### 📊 2. Visual Distributions
- Created **histograms** and **boxplots** for:
  - `Age`
  - `Fare`
  - `SibSp`
  - `Parch`

### 🔗 3. Correlation Heatmap
- Visualized correlations using `sns.heatmap`
- Highlighted strongest linear relationships

### 🔍 4. Feature Interaction
- Used `pairplot` (colored by survival) to explore multivariate patterns
- Converted categorical features to improve readability

---

## 🔎 Key Insights

| Feature         | Observation                                                   |
|------------------|---------------------------------------------------------------|
| **Fare**         | Passengers who paid more had better survival rates            |
| **Pclass**       | 1st class passengers had the highest survival chances         |
| **Age**          | Children were more likely to survive                          |
| **SibSp/Parch**  | Smaller families (1–2 members) had slightly better outcomes    |

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/NSCodegame/EDA-_Task2.git
cd EDA-_Task2

