# 🌾 Seasonal Agriculture Performance Analysis

A data analysis project that investigates how **Kharif, Rabi, and Zaid** agricultural seasons differ in yield, profitability, environmental conditions, water efficiency, and disease/pest risk.

## 👤 Project Information

| Field | Details |
|---|---|
| **Student** | Shivayogi Mruthunjaya Urolagin |
| **USN** | 1DS23RI047 |
| **College** | Dayananda Sagar College Of Engineering |
| **Program** | VOIS 2026–27 |

## 🎯 Objective

The project analyzes seasonal agricultural performance and identifies relationships among environmental conditions, irrigation practices, water utilization, crop yield, profitability, and disease/pest risk.

### Analytical Questions

1. Which agricultural season delivers the highest average yield and the most stable profit distribution?
2. How do rainfall and temperature vary across seasons, and how are these environmental differences reflected in yield outcomes?
3. How does the interaction between irrigation method and season affect water efficiency and disease/pest risk?

## 📊 Dataset

The dataset contains **4,000 farm-level records** and **28 features** covering:

- Farm, state, district, crop, and season information
- Rainfall, temperature, humidity, sunlight, soil pH, and soil moisture
- Nitrogen, phosphorus, potassium, fertilizer, pesticide, and seed quality
- Yield, production, market price, cost, revenue, and profit
- Water usage, water-efficiency, and disease/pest risk

The dataset is included in `data/` for reproducibility.

## 🔬 Analysis Workflow

1. Load and inspect the agricultural dataset.
2. Check structure, descriptive statistics, missing values, and seasonal distribution.
3. Compare yield and profitability across seasons.
4. Examine rainfall and temperature patterns and their relationship with yield.
5. Compare water efficiency and disease/pest risk across seasons.
6. Analyze the interaction between **irrigation method × season**.
7. Summarize the findings into practical agricultural recommendations.

## 💡 Key Findings

- **Rabi** shows the strongest overall stability in yield and profitability distributions.
- **Kharif** is associated with higher rainfall and warm conditions, supporting water-intensive crops while also increasing disease/pest pressure.
- **Zaid** experiences greater heat and stronger dependence on irrigation, making efficient water management especially important.
- **Drip irrigation** records the highest water-efficiency levels across seasons in the analysis.
- **Flood irrigation** shows the weakest water efficiency.
- The analysis indicates a practical sustainability trade-off between seasonal productivity, disease/pest risk, profitability, and water use.

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Repository Structure

```text
Seasonal-Agriculture-Performance-Analysis/
├── README.md
├── requirements.txt
├── notebooks/
│   └── Seasonal_Agriculture_Analysis.ipynb
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
└── outputs/
    └── figures/
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Dreamer-26/Seasonal-Agriculture-Performance-Analysis.git
cd Seasonal-Agriculture-Performance-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Launch Jupyter Notebook or JupyterLab and open:

```text
notebooks/Seasonal_Agriculture_Analysis.ipynb
```

The notebook should load the dataset from the repository's `data/` folder after the relative dataset path is updated accordingly.

## 📌 Project Status

Completed academic data-analysis project prepared for the **VOIS 2026–27** program.

## 👨‍💻 Author

**Shivayogi Mruthunjaya Urolagin**  
USN: **1DS23RI047**  
Dayananda Sagar College Of Engineering

---

⭐ This repository contains the notebook, source dataset, analysis workflow, and supporting project documentation.