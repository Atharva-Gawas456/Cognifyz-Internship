
# 📘 Project README  

## 🔹 Overview  
This repository contains three machine learning tasks, implemented in Jupyter Notebooks, that progressively build understanding of rating prediction, recommendation systems, and classification models.  

### Tasks Included
1. **Task 1 - Rating**: Predicting restaurant ratings using machine learning.  
2. **Task 2 - Recommendation**: Building a recommender system for restaurants.  
3. **Task 3 - Classification**: Performing classification on restaurant-related data.  

---

## 📂 Project Structure
```
├── Task 1 - Rating.ipynb
├── Task 2 - Recommendation.ipynb
├── Task 3 - Classification.ipynb
└── README.md
```

---

## ⚙️ Requirements
Make sure you have the following installed:

- Python 3.8+
- Jupyter Notebook / JupyterLab
- Required libraries (install via pip):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📑 Tasks Details  

### **1. Task 1 - Rating**  
**Goal:**  
- Predict restaurant ratings based on dataset features.  
- Perform exploratory data analysis (EDA).  
- Apply regression techniques to predict ratings.  

**Key Steps:**  
- Data loading and cleaning  
- Feature engineering  
- Model training (Linear Regression, Random Forest, etc.)  
- Performance evaluation (R², RMSE)  

---

### **2. Task 2 - Recommendation**  
**Goal:**  
- Build a restaurant recommendation system based on **city, cuisines, and price range**.  

**Key Steps:**  
- Data preprocessing  
- Content-based filtering (city, cuisines, price range)  
- Output top recommendations with restaurant name and address  

**Expected Output Example:**  
```
Recommended Restaurants:
1. Restaurant A - Address A
2. Restaurant B - Address B
3. Restaurant C - Address C
```

---

### **3. Task 3 - Classification**  
**Goal:**  
- Perform classification (e.g., predicting restaurant category or rating class).  

**Key Steps:**  
- Exploratory Data Analysis (EDA)  
- Data preprocessing  
- Model training (Logistic Regression + another classifier such as Random Forest/SVM)  
- Performance evaluation using accuracy, confusion matrix, and classification report  
- Visualization of confusion matrix and accuracy graphs  

---

## ▶️ How to Run
1. Clone the repository or download the notebooks.  
2. Open the notebook you want to run:  
   ```bash
   jupyter notebook "Task 1 - Rating.ipynb"
   ```  
3. Run the cells step by step.  
4. Modify parameters (like city, cuisine, price range) in **Task 2** to test recommendations.  

---

## 📊 Visualizations
- **Task 1:** Rating distribution plots, regression evaluation.  
- **Task 2:** Recommendation results in tabular form.  
- **Task 3:** Confusion matrix, accuracy vs epochs graph.  

---

## ✅ Conclusion
- **Task 1** demonstrates predictive modeling for ratings.  
- **Task 2** builds a practical recommender system.  
- **Task 3** applies supervised classification with performance evaluation.  

This progression covers **regression → recommendation → classification**, giving a solid understanding of ML workflows in the restaurant domain.  
