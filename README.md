# Clustering and Predictive Modeling for Student Performance Analysis

This project analyzes student performance using clustering and regression techniques to uncover learning patterns and predict academic outcomes. By applying K-Means and DBSCAN clustering on features like attendance, participation, and homework scores, the model segments students into meaningful groups. Further, predictive models such as Ridge Regression, XGBoost, and Random Forest are used to estimate final exam scores, helping identify key academic drivers. The insights derived from each cluster support actionable recommendations to enhance student engagement and academic success.

---

## 📌 Objectives

- Group students into clusters based on academic behavior.
- Predict final exam scores using regression models.
- Derive actionable academic insights from patterns in the data.

---

## 🧠 Techniques Used

### Clustering
- **K-Means Clustering**: For segmenting students into performance-based groups.
- **DBSCAN**: To detect clusters and outliers in student behavior.

### Predictive Modeling
- **Ridge Regression**: To predict final scores while handling multicollinearity.
- **Random Forest**: For capturing nonlinear relationships in performance data.
- **XGBoost**: For high-accuracy predictive modeling.

---

## 📊 Features Used

- Attendance Rate  
- Homework Submission Scores  
- Class Participation  
- Quiz and Midterm Grades  
- Final Exam Score (Target Variable)

---

## 📁 Project Structure

```
Student_Performance_Analysis/
│
├── Student_performance.ipynb      # Main Jupyter Notebook
├── student_dataset.csv            # Input data file
├── README.md                      # Project documentation
└── requirements.txt               # List of required libraries (optional)
```

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- XGBoost
- Pandas, NumPy
- Seaborn, Matplotlib

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Student_Performance_Analysis.git
   cd Student_Performance_Analysis
   ```

2. (Optional) Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Student_performance.ipynb
   ```

---

## 🔮 Future Work

- Include demographic or socio-economic indicators for deeper insights.
- Extend to time-series tracking for academic performance trends.
- Deploy as a web dashboard for real-time academic analysis.

---

## 📬 Contact

For queries or collaboration: kurraswethavanaja@gmail.com
