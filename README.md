# HR Attrition Dashboard

![License](https://img.shields.io/badge/License-MIT-blue)
![Python](https://img.shields.io/badge/Python-3.8+-yellow)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChokZB/hr_attrition_dashboard/blob/main/hr_attrition_dashboard.ipynb)

This project is an **interactive HR Attrition Dashboard** built using Jupyter Notebook, `ipywidgets`, `matplotlib`, and `seaborn`. It allows users to explore key HR metrics such as attrition, demographics, job satisfaction, and employee engagement.

The dashboard behaves like a **web application**, letting users filter employees dynamically by:

* **Department**
* **Gender**
* **Age Range**

All visualisations update instantly as filters change.

---

## 🎯 Objectives

Analysing attrition helps companies understand:

* **Predictive factors of attrition**: Identify which characteristics (e.g., age, work-life balance, job role) influence employee turnover.
  
* **Areas for intervention**: Spot potential improvements in HR practices such as workload balance, career progression, or employee well-being.
  
* **Employee engagement and satisfaction**: Understand correlations between job satisfaction, environment satisfaction, and attrition risk.

---

## 🗃️ Dataset

**File:** [`data/hr_analytics.csv`](data/hr_analytics.csv)

The dataset used in this project is a **HR Employee Attrition dataset**, originally found on Kaggle (exact source link not available anymore).

It includes **1,480 employee records** with fields such as:

* **Demographics:** Age, Gender, Marital Status
* **Work environment:** Job Role, Department, Business Travel
* **Satisfaction metrics:** Job Satisfaction, Work-Life Balance
* **Performance attributes:** Performance Rating, Years at Company
* **Attrition status:** Whether the employee left the company

---

## 🚀 Key Features

1. **Real-time interactivity**: Built with `ipywidgets`, the dashboard reacts instantly to filter inputs, no rerunning cells required.

2. **Multiple visualisations**: Donut charts, (horizontal/vertical/clustered) bar charts, violin plot

3. **Clean, user-friendly UI**: Using `VBox`, `HBox`, and structured layout design, the filters and charts are arranged into a dashboard-like interface that feels similar to BI tools (Power BI/Tableau).

4. **Voilá-compatible**: The notebook is fully structured for Voilá deployment, turning it into a standalone web application without exposing any notebook code.

---

## 📁 Project Structure

```
hr_attrition_dashboard/
│
├── data/
│     └── hr_analytics.csv            # Dataset
│
├── media/
│     └── dashboard_demo.gif          # A short demo of the dashboard
│
├── .gitignore                        # Files/folders excluded from Git
│
├── LICENSE                           # MIT License
│
├── README.md                         # Project overview and instructions
│
├── environment.yml                   # Conda environment for local setup
│
└── hr_attrition_dashboard.ipynb      # Main dashboard notebook
```

---

## 🔧 Setup & Execution

This project can be run in several ways depending on preference, from local development to cloud execution. The options below are arranged from most flexible to most convenient.

### Option 1: Run Locally (Recommended for Development)

1. **Clone the repository**

   ```bash
   git clone https://github.com/ChokZB/hr_attrition_dashboard.git
   cd hr_attrition_dashboard
   ```

2. **Install dependencies**

   ```bash
   conda env create -f environment.yml
   conda activate hr-attrition-env
   ```

3. **Run the notebook**

   ```bash
   jupyter notebook hr_attrition_dashboard.ipynb
   ```

   The dashboard interface will appear inside the notebook after running all cells.

---

### Option 2: Run Locally with Voilá (View as a Clean Web App)

Voilá turns the notebook into a standalone web application with no visible code.

1. **Install Voilá**

   ```bash
   pip install voila
   ```

2. **Launch the dashboard**

   ```bash
   voila hr_attrition_dashboard.ipynb
   ```

   A browser window will open displaying the dashboard as a full interactive app.

---

### Option 3: Run in Google Colab (No Installation Needed)

Open the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChokZB/hr_attrition_dashboard/blob/main/hr_attrition_dashboard.ipynb)

---

## 💡 Use Case Highlights

This project demonstrates:

* Building interactive dashboards entirely in Python
* Web-app-style interfaces with ipywidgets + Voilá
* Data preprocessing, visualisation, and UI engineering
* Real-world HR domain analytics
* Visual storytelling with multiple chart types
* An alternative to BI tools using only code

---

## 👨‍🏫 Dashboard Demo

![dashboard_demo](media/dashboard_demo.gif)

---

## 🧑‍💻 Author

**Chok Zu Bing**

GitHub: [@ChokZB](https://github.com/ChokZB)

---

## 🪪 Licence

This project is released under the [MIT License](LICENSE).