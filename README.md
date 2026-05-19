# Machine Learning: Ensemble Methods for Critical Temperature Estimation in Superconductors

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Project Overview

This project applies **ensemble machine learning methods** to predict the critical temperature ($T_c$) in superconductor materials. The work combines foundational ML techniques (decision trees, ensemble methods) with a practical application in materials physics, demonstrating that traditional ML approaches remain valuable despite the rise of deep learning.

### 🎯 Objectives

- Study and implement ensemble learning methods (Random Forests, Gradient Boosting, etc.)
- Build predictive models for superconductor critical temperature
- Analyze model performance and interpretability
- Compare ensemble methods with traditional approaches
- Provide insights into materials science prediction problems

## 📁 Project Structure

```
│
├── README.md                       # This file
├── .gitignore                      # Git ignore rules
├── requirements.txt                # Python dependencies
│
├── data/                           # Dataset files
│   ├── supercond_data.csv          # Main superconductor dataset
│   └── unique_m.csv                # Unique materials data
│
├── notebooks/                      # Jupyter notebooks
│   └── EDA_Model.ipynb             # Exploratory Data Analysis & Modeling
|
└── docs/                           # Documentation
    ├── memoria_tex/                # Thesis manuscript (LaTeX)
    ├── presentacion_texBeamer/     # Presentation slides (Beamer)
    ├── memoria_pdf.pdf             # Thesis manuscript (pdf)
    └── presentacion_pdf.pdf        # Presentation slides (pdf)
```

## 🚀 Quick Start

### Prerequisites

- **Python 3.10+**

## 📊 Dataset

### Superconductor Dataset

- **File:** `data/supercond_data.csv`
- **Description:** Contains measurements and properties of various superconductor materials
- **Target Variable:** Critical temperature ($T_c$)
- **Use:** Training and evaluation of ML models

### Materials Reference

- **File:** `data/unique_m.csv`
- **Description:** Reference data for unique materials in the dataset

## 📚 Documentation

### Main Thesis
- **Location:** `docs/memoria_pdf.pdf`
- **Content:** Complete thesis document including:
  - Literature review on ensemble methods
  - Theory of superconductivity basics
  - Mathematical foundations of ML algorithms
  - Experimental results and analysis
  - Conclusions and future work

### Presentation
- **Location:** `docs/presentacion_pdf.pdf`

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|-----------|---------|
| **Python 3.10** | Core programming language |
| **Jupyter** | Interactive notebooks for analysis |
| **NumPy** | Numerical computing |
| **Pandas** | Data manipulation & analysis |
| **Scikit-learn** | Machine learning models & preprocessing |
| **Matplotlib/Seaborn** | Data visualization |
| **SciPy** | Scientific computing utilities |

## 📖 Key ML Methods Covered

### Fundamental Concepts
- ✓ Decision Trees
- ✓ Feature importance analysis
- ✓ Model evaluation metrics

### Ensemble Methods
- ✓ Random Forests
- ✓ Gradient Boosting Machines
- ✓ Stacking
- ✓ Cross-validation strategies

### Advantages of This Approach
- **Interpretability:** Understand why models make predictions
- **Efficiency:** Lower computational requirements vs. deep learning
- **Data Efficiency:** Performs well with moderate dataset sizes
- **Stability:** Robust and reliable predictions

## 👤 Author

**Marcos Barba Ballarín**
- Degree: Grado en Física (Physics)
- University: University of Zaragoza
- Advisor: Ricardo López Ruiz
- Year: 2026

## 📖 References & Further Reading

- Breiman, L. (2001). Random Forests. *Machine Learning*, 45(1), 5-32.
- Friedman, J. H. (2001). Greedy function approximation: A gradient boosting machine.
- Zhou, Z. H. (2012). *Ensemble Methods: Foundations and Algorithms*. CRC Press.
- See `docs/memoria_tex/TFGBib.bib` for complete bibliography

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check existing issues or create new ones.

---

**Last Updated:** May 2026  
**Status:** ✅ Completed Thesis Project