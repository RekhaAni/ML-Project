 # Student Performance Prediction — Machine Learning Project

##  Overview
This project predicts student performance based on various academic and demographic factors using machine learning techniques. The dataset provides insights into how variables like gender, parental education, lunch type, and test preparation affect students’ scores in math, reading, and writing.

The project demonstrates a complete ML workflow — from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and saving the trained model for future use.

---

##  Project Structure
```
mp student/
│
├── StudentsPerformance.csv             # Dataset used for model training
├── Student performance ML project.ipynb # Main Jupyter notebook
├── model.joblib                        # Saved trained ML model
├── Untitled.ipynb                      # Experimental or test notebook
└── .ipynb_checkpoints/                 # Auto-saved notebook checkpoints
```

---

##  Key Features
- Data exploration and visualization using **Pandas**, **Matplotlib**, and **Seaborn**
- Data preprocessing (handling categorical variables, normalization, etc.)
- Model building using **Scikit-learn**
- Model evaluation (accuracy, confusion matrix, etc.)
- Model persistence using **Joblib**

---

## 📊 Dataset Description
The dataset `StudentsPerformance.csv` contains the following features:

| Column Name              | Description |
|--------------------------|-------------|
| gender                   | Student’s gender |
| race/ethnicity           | Student’s race group |
| parental level of education | Highest education level of parents |
| lunch                    | Type of lunch (standard/free) |
| test preparation course  | Whether the student completed the prep course |
| math score               | Student’s math score |
| reading score            | Student’s reading score |
| writing score            | Student’s writing score |

---

## ⚙️ How to Run

### **1. Clone or Download the Repository**
```bash
git clone https://github.com/yourusername/student-performance-ml.git
cd "mp student"
```

### **2. Install Required Packages**
Make sure you have Python 3.8+ installed. Then run:
```bash
pip install -r requirements.txt
```

If no `requirements.txt` exists, manually install:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter
```

### **3. Open the Jupyter Notebook**
```bash
jupyter notebook "Student performance ML project.ipynb"
```

### **4. Run All Cells**
Follow the notebook step-by-step to:
- Explore data
- Train and evaluate the model
- Save/load the trained model (`model.joblib`)

---

## 🧩 Model Information
The trained model (`model.joblib`) can be loaded in Python as follows:

```python
import joblib

model = joblib.load("model.joblib")
# Example: model.predict([[feature_values]])
```

---

## 📈 Results
The notebook provides detailed visualizations and evaluation metrics (such as accuracy and confusion matrix) to assess model performance.

---

## 🧾 Requirements
- Python 3.8 or higher  
- pandas  
- numpy  
- seaborn  
- matplotlib  
- scikit-learn  
- joblib  
- jupyter  

You can generate a `requirements.txt` file with:
```bash
pip freeze > requirements.txt
```

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests to improve this project.

---

 
