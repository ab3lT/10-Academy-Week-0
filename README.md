# Week 0 Challenge - 10Academy Artificial Intelligence Mastery

Welcome to the GitHub repository for the **Week 0 Challenge** of the 10Academy Artificial Intelligence Mastery program. This repository contains all code, documentation, and deliverables for the tasks completed during the challenge.

---

## **Overview**
This project covers multiple aspects of artificial intelligence, programming, and data analysis. Key areas include:

- **Python Programming**: Task-specific assignments to enhance programming skills.
- **Git and GitHub**: Repository management, version control, and collaborative workflows.
- **Exploratory Data Analysis (EDA)**: Extracting actionable insights from data.
- **CI/CD**: Understanding and implementing automated pipelines.
- **Streamlit**: Developing and deploying an interactive dashboard.

---

## **Repository Structure**
The repository follows a structured organization for ease of navigation and collaboration:

```
├── .streamlit/               # Streamlit configuration files
│   └── config.toml
├── .vscode/                 # VSCode workspace settings
│   └── settings.json
├── .github/                 # GitHub workflows
│   └── workflows
│       └── unittests.yml    # CI/CD pipeline for unit tests
├── src/                     # Source code for data processing and EDA
├── notebooks/               # Jupyter notebooks for analysis
│   ├── example.ipynb
│   └── README.md
├── tests/                   # Unit tests for validation
├── app/                     # Streamlit application files
│   ├── main.py              # Main Streamlit app script
│   ├── utils.py             # Utility functions for visualization and processing
├── scripts/                 # Additional Python scripts
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
├── .gitignore               # Files and directories to ignore in Git
```

---

## **Setup Instructions**

To get started with this project:

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Repository:**
   ```bash
   cd <repository-folder>
   ```

3. **Set Up a Virtual Environment:**
   ```bash
   python -m venv env
   source env/bin/activate   # For Linux/MacOS
   env\Scripts\activate     # For Windows
   ```

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Streamlit Dashboard:**
   ```bash
   streamlit run app/main.py
   ```

---

## **Tasks and Deliverables**

### **Task 1: Git and GitHub**
- Set up a Python development environment.
- Create a `task-1` branch for Day 1 analysis.
- Commit work with descriptive messages (minimum of 3 commits per day).
- Follow a structured folder hierarchy.

### **Task 2: Exploratory Data Analysis (EDA)**
- Perform detailed data analysis, including:
  - Summary statistics.
  - Data quality checks and cleaning.
  - Time-series analysis and visualizations.
  - Correlation analysis and anomaly detection.
- Document insights and cleaning steps.

### **Task 3: Dashboard Development with Streamlit**
- Design an interactive dashboard with:
  - Dynamic visualizations.
  - Intuitive navigation.
  - Interactive elements (e.g., sliders, dropdowns).
- Deploy the dashboard to Streamlit Community Cloud.

---

## **Key Features**
- **Automated Testing**: Integrated CI/CD pipeline for running unit tests.
- **Interactive Visualizations**: Utilize Streamlit for dynamic and engaging dashboards.
- **Data Cleaning**: Comprehensive handling of anomalies and missing values.

---

## **Contributing**
Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or raise an issue in the GitHub repository.

---

## **Author**
This repository was developed as part of the 10Academy Artificial Intelligence Mastery program by Abel Tadesse.

---
