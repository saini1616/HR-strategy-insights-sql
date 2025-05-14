# 📊 Analyzing Employee Trends

This project explores employee data using SQL and Python to uncover trends and insights related to workforce composition, tenure, department distributions, and more.

## 🗂️ Files

- **Analyzing Employee Trends.sql**: SQL script with queries used for data analysis.
- **Analyzing Employee Trends.csv**: Dataset containing employee-related information.
- **requirements.txt**: Python dependencies to set up the environment.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/employee-trends-analysis.git
cd employee-trends-analysis
```

### 2. Set up the environment

Install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Analysis

- Option 1: Use your preferred SQL editor to run `Analyzing Employee Trends.sql`
- Option 2: Load the CSV in Python and replicate SQL queries using pandas

```python
import pandas as pd

df = pd.read_csv("Analyzing Employee Trends.csv")
print(df.head())
```

## 📈 Analysis Objectives

The analysis covers:

- Employee distribution by department
- Hiring and termination trends over time
- Average employee tenure
- Demographic breakdowns
- Potential retention risks

## 🧰 Technologies Used

- SQL
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook (optional)

## 📝 License

This project is open-source and available under the MIT License.
