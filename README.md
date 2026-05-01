# Dota 2 Match Outcome Prediction — Machine Learning

> Applied PCA, feature engineering, and Random Forest to predict Dota 2 match outcomes across a 10,294-match Kaggle dataset with 117 features — achieving meaningful predictive accuracy on a highly complex, multi-variable problem.

## 🎯 What This Project Does

Predicts the outcome of Dota 2 matches (win/loss) using pre-match team composition data. The challenge: Dota 2 has 100+ heroes, complex synergies, and high variance — making it a genuinely hard ML problem that requires careful feature engineering rather than naive model application.

## 📊 Dataset

| Dataset | Records | Features |
|---|---|---|
| Match Results | 10,294 matches | 117 features |
| Hero Attributes | 33 heroes | 126 attributes per hero |

The hero attribute dataset was integrated to enrich the match feature space — combining compositional data (which heroes were picked) with attribute data (what those heroes actually do).

## 🔬 ML Pipeline

```
Raw Match Data (10,294 matches, 117 features)
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Feature Engineering  ──►  Hero attribute integration (33 heroes × 126 attributes)
    │
    ▼
PCA (Dimensionality Reduction)
    │
    ▼
Random Forest Classifier
    │
    ▼
Model Evaluation  ──►  Accuracy, Feature Importance, Performance Analysis
```

## ⚙️ Tech Stack

- **Python** — core implementation
- **Pandas / NumPy** — data loading, manipulation, preprocessing
- **scikit-learn** — PCA, Random Forest, model evaluation
- **Matplotlib / Seaborn** — data visualization and performance analysis
- **Jupyter Notebook** — exploratory analysis and documentation

## 🔑 Key Techniques

- **PCA** — dimensionality reduction on high-feature dataset to remove noise and improve model generalization
- **Feature Engineering** — merging hero attribute data to create richer, more informative input features
- **Random Forest** — ensemble method suited for high-dimensional, non-linear classification
- **Feature Importance Analysis** — identifying which game factors most strongly predict outcomes

## 🎓 Academic Context

Built as part of the **Machine Learning** course at Humber College, Toronto (July – August 2025).

---

*Part of my AI/ML project portfolio — [github.com/ColdCof63e](https://github.com/ColdCof63e)*
