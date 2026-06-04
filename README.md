# Loan Risk Analysis and Prediction using Python

## Project Overview

This project performs **Loan Risk Analysis and Loan Amount Prediction** using **Python, Machine Learning, Data Analysis, and Data Visualization** techniques.

The system analyzes loan-related data, cleans the dataset, performs statistical analysis, visualizes insights, categorizes loan risk, and predicts loan amounts using a **Linear Regression Model**.

The project also includes **interactive dashboards using Plotly** for better data visualization.

---

## Features

- Dataset loading using embedded CSV data
- Data cleaning and preprocessing
- Missing value checking
- Interest rate conversion
- Employment length conversion
- Loan status encoding
- Categorical variable encoding
- Descriptive statistics generation
- Loan default analysis
- Risk category identification
- Data visualization using Matplotlib and Seaborn
- Correlation heatmap analysis
- Loan amount prediction using Machine Learning
- Model evaluation using:
  - R² Score
  - Mean Absolute Error (MAE)
- Interactive dashboards using Plotly

---

## Technologies Used

### Programming Language
- Python

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn

---

## Project Structure

```bash
Loan-Risk-Analysis/
│── loan_analysis.py
│── README.md
```

---

## Dataset Information

The dataset contains loan-related details such as:

| Column Name | Description |
|-------------|-------------|
| loan_amnt | Loan amount requested |
| term | Loan duration |
| int_rate | Interest rate |
| annual_inc | Annual income |
| emp_length | Employment length |
| home_ownership | Home ownership type |
| purpose | Loan purpose |
| grade | Loan grade |
| loan_status | Loan repayment status |

### Loan Status Mapping

- Fully Paid → 0
- Charged Off → 1

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/loan-risk-analysis.git
```

### Step 2: Move into Project Folder

```bash
cd loan-risk-analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

---

## How to Run the Project

Run the Python file:

```bash
python loan_analysis.py
```

---

## Project Workflow

### 1. Data Collection
- Load embedded CSV dataset

### 2. Data Cleaning
- Remove `%` symbol from interest rates
- Convert loan term into numeric values
- Convert employment length into integers

### 3. Data Preprocessing
- Encode categorical variables
- Convert loan status into numerical format

### 4. Data Analysis
- Calculate:
  - Average loan amount
  - Average annual income
  - Average interest rate

### 5. Data Visualization
The project generates:

- Loan default distribution
- Annual income distribution
- Loan amount distribution
- Income vs loan amount scatter plot
- Interest rate vs loan status boxplot
- Correlation heatmap

### 6. Risk Analysis
Risk categories are classified as:

| Interest Rate | Risk Category |
|---------------|---------------|
| Less than 10% | Low Risk |
| 10% to 18% | Medium Risk |
| Greater than 18% | High Risk |

### 7. Machine Learning Model
The project uses:

**Linear Regression Algorithm**

Input Features:
- Annual Income
- Interest Rate
- Loan Term

Target Variable:
- Loan Amount

### 8. Model Evaluation
Performance metrics used:

- **R² Score**
- **Mean Absolute Error (MAE)**

---

## Sample Output

```text
Dataset Loaded Successfully

Average Loan Amount:
6590.0

Average Annual Income:
50145.2

Model Evaluation
R2 Score: 0.85
Mean Absolute Error: 1200.45
```

---

## Project Insights

1. Higher interest rates indicate greater default risk.
2. Annual income influences loan approval amount.
3. Employment length may affect repayment behavior.
4. Risk categories help identify possible loan defaulters.
5. Machine learning improves loan prediction accuracy.

---

## Future Improvements

- Add larger real-world datasets
- Use advanced ML algorithms
  - Random Forest
  - Decision Tree
  - XGBoost
- Build a web application using Flask or Django
- Create a live dashboard

---

## Author
p.karthihai selvan

---

## License

This project is open-source and available under the **MIT License**.



<img width="740" height="493" alt="image" src="https://github.com/user-attachments/assets/9863a4b7-9577-404e-8b5d-f007219ce03a" />
<img width="922" height="593" alt="image" src="https://github.com/user-attachments/assets/3a515c91-3e7d-4a9f-92c0-9e2b7036dbb2" />
<img width="931" height="591" alt="image" src="https://github.com/user-attachments/assets/4006cb12-77e0-4986-8909-8bc296c7b6c4" />
<img width="914" height="616" alt="image" src="https://github.com/user-attachments/assets/c4c7b746-e79d-4b52-a2bc-b60ac633d096" />
