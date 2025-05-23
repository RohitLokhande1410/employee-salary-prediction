# 🧠 Employee Salary Prediction Using Machine Learning

This project aims to predict employee salaries using a machine learning regression model based on structured employee data. The solution demonstrates the use of data preprocessing, model building, and performance evaluation using Python's scikit-learn library.

---

## 📁 Project Structure

- `Employee_Salary_ML_Report.pdf` - 📘 A comprehensive project report detailing methodology, tools used, and results.
- (Optional) `employees.csv` - Dataset containing employee details.
- (Optional) `Employees_Project.ipynb` - Jupyter notebook with complete code and analysis.

---

## 🚀 Tools & Technologies

- **Python 3**
- **Pandas, NumPy** - Data manipulation
- **Scikit-learn** - Model building & evaluation
- **Matplotlib** - Visualization
- **FPDF** - Report generation

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Dropped null values
   - Encoded categorical columns using LabelEncoder
   - Scaled numeric features using StandardScaler

2. **Model Training**
   - Used Linear Regression to predict salary
   - Split data into training and test sets (80/20)
   - Evaluated using R² score and Mean Squared Error

3. **Visualization**
   - Scatter plot showing Actual vs Predicted Salaries

---

## 📊 Results

The model demonstrated solid performance with a high R² score, suggesting strong predictive power. A visual comparison of actual vs. predicted salaries further confirmed its accuracy.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-salary-prediction.git
   cd employee-salary-prediction
