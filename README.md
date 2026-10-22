# 🏦 Banking Insights — Customer Financial Data Analysis

A data analysis project exploring banking customer demographics and financial attributes using Python, exploratory data analysis (EDA), and data visualization.

## 📌 Project Overview

The objective of this project is to explore banking data and understand patterns in customer age, estimated income, savings, loans, deposits, and account balances.

Using Python's data analysis and visualization libraries, the project examines numerical distributions and helps identify patterns, variations, and potential outliers in financial data.

## 🎯 Objectives

* Explore customer demographics and financial attributes.
* Analyze income, savings, loans, and deposits.
* Identify patterns in numerical data through visualization.
* Investigate potential outliers and variations.
* Communicate findings through data visualizations.
* Develop an interactive Power BI dashboard as a complementary reporting component.

## 📊 Dataset Information

* **File:** `Banking.csv`
* **Format:** CSV
* **Content:** Banking customer and financial attributes.
* **Key variables:** Age, Estimated Income, Superannuation Savings, Credit Card Balance, Bank Loans, Bank Deposits, Checking Accounts, Saving Accounts, Foreign Currency Account, Business Lending, and Fee Structure.

*Column definitions and units should be verified against the original dataset documentation.*

## 🔄 Project Workflow

**Banking Data → Data Inspection → Exploratory Data Analysis → Statistical Visualization → Insight Generation → Power BI Reporting**

## 🛠️ Steps Involved

### 1. Data Loading & Inspection

* Imported the CSV dataset using Pandas.
* Examined the dataset structure, column names, and data types.
* Checked for missing values and duplicate records.

### 2. Exploratory Data Analysis (EDA)

* Explored customer age and estimated income.
* Examined savings, deposits, loans, and credit card balances.
* Analyzed other banking and financial variables.

### 3. Data Visualization

* Created histograms to understand numerical distributions.
* Used Kernel Density Estimation (KDE) curves to visualize distribution patterns.
* Examined variations and potential outliers.

### 4. Insight Generation

* Investigated customer financial patterns.
* Examined the distributions of income, savings, loans, and deposits.
* Identified areas for further analysis based on the visualizations.

### 5. Power BI Dashboard

* Planned interactive visualizations for banking metrics.
* Intended to present customer and financial data through clear charts and summary indicators.

*Update this section with the implemented dashboard features once the Power BI report is complete.*

## 💻 Technologies Used

| Technology       | Purpose                               |
| ---------------- | ------------------------------------- |
| Python           | Data analysis                         |
| Pandas           | Data manipulation                     |
| NumPy            | Numerical operations                  |
| Matplotlib       | Data visualization                    |
| Seaborn          | Statistical visualization             |
| Jupyter Notebook | Interactive analysis                  |
| Power BI         | Interactive reporting, if implemented |

## 📂 Project Structure

```text
Banking-Dashboard/
│
├── data/
│   └── Banking.csv
│
├── eda/
│   └── BankEDA.ipynb
│
├── powerbi/
│   └── BankingDashboard.pbix
│
├── README.md
└── .gitignore
```

*This is an example structure. Adjust filenames and folders to match the files actually included in your repository.*

## 🚀 Getting Started

### Prerequisites

* Python 3
* Visual Studio Code or Jupyter Notebook
* Required Python libraries
* Power BI Desktop, if using the Power BI report

### 1. Clone the Repository

```bash
git clone https://github.com/devyansh-01/Banking-Dashboard.git
```

### 2. Navigate to the Project Directory

```bash
cd Banking-Dashboard
```

### 3. Install Dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

### 4. Open the Notebook

Open `eda/BankEDA.ipynb` in VS Code or Jupyter Notebook and select an appropriate Python kernel.

### 5. Load the Dataset

Ensure `Banking.csv` is available locally. Update the file path in the notebook if needed.

Example:

```python
import pandas as pd

df = pd.read_csv("../data/Banking.csv")
```

This relative path assumes the notebook's working directory is the `eda` folder.

### 6. Run the Analysis

Execute the notebook cells to inspect the data, perform EDA, and generate visualizations.

### 7. Open the Power BI Report

If a `.pbix` report is included, open it using Microsoft Power BI Desktop.

## 📈 Results & Insights

The notebook explores the distributions of customer demographics and financial attributes.

This section can be expanded with verified findings, such as:

* Customer age distribution.
* Estimated income patterns.
* Savings and deposit distributions.
* Loan and credit card balance patterns.
* Relationships between selected financial variables.

*Specific numerical findings should be added after validating the analysis results.*

## 📚 Skills Demonstrated

* Data Analysis with Python
* Data Manipulation using Pandas
* Exploratory Data Analysis
* Statistical Data Visualization
* Data Quality Inspection
* Data Interpretation
* Jupyter Notebook
* Power BI Reporting, if implemented

## 👨‍💻 Author

**Devyansh Singh**

GitHub: [devyansh-01](https://github.com/devyansh-01)

---

⭐ If you find this project interesting, feel free to explore the repository.