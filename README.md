# HR Attrition Dashboard

![License](https://img.shields.io/badge/License-MIT-blue)
![Python](https://img.shields.io/badge/Python-3.8+-yellow)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChokZB/hr_attrition_dashboard/blob/main/hr_attrition_dashboard.ipynb)
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChokZB/hr_attrition_dashboard/HEAD?urlpath=voila/render/hr_attrition_dashboard.ipynb)
[![Voila](https://img.shields.io/badge/Launch%20App-Voila-orange)](
https://mybinder.org/v2/gh/ChokZB/hr_attrition_dashboard/HEAD?urlpath=voila/render/hr_attrition_dashboard.ipynb)


This project is an **interactive HR Attrition Dashboard** built using Jupyter Notebook, `ipywidgets`, `matplotlib`, `seaborn`, and `Voila`.
It allows users to explore key HR metrics such as attrition, demographics, job satisfaction, and employee engagement.

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

4. **Voila-compatible**: The notebook is fully structured for Voila deployment, turning it into a standalone web application without exposing any notebook code.

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
├── hr_attrition_dashboard.ipynb      # Main dashboard notebook
│
├── requirements.txt                  # Dependency list for reproducibility
│
└── runtime.txt                       # Specify Python version for Binder
```

---

## 💻 Setup & Execution

### Option 1: Run Locally (Recommended for Development)

1. **Clone the repository**

   ```bash
   git clone https://github.com/ChokZB/hr_attrition_dashboard.git
   cd hr_attrition_dashboard
   ```

2. **Install dependencies**

   Install all required packages using the provided `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**

   ```bash
   jupyter notebook hr_attrition_dashboard.ipynb
   ```

   or open it directly in Google Colab. 

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChokZB/hr_attrition_dashboard/blob/main/hr_attrition_dashboard.ipynb)

4. **Run the cell, the dashboard interface will appear inside the notebook.**

---

### Option 2: Run as a Web Application (Voila)

Voila converts the notebook into a clean UI with no code or notebook cells visible.

1. **Install Voila**

   ```bash
   pip install voila
   ```

2. **Launch the dashboard**

   ```bash
   voila hr_attrition_dashboard.ipynb
   ```

Your browser will open a fully interactive dashboard web app (no notebook interface).

---

### Option 3: Launch in Browser (Binder)

Click the button below to run the notebook instantly in the cloud (no installation needed):

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChokZB/hr_attrition_dashboard/HEAD?urlpath=voila/render/hr_attrition_dashboard.ipynb)

---

## 💡 Use Case Highlights

This project demonstrates:

* Building interactive dashboards entirely in Python
* Web-app-style interfaces with ipywidgets + Voila
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
