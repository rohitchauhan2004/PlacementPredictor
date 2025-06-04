
🎓 Placement Prediction Project
This project focuses on analyzing student data to predict campus placement outcomes using machine learning. The core model used is a Random Forest Classifier, which achieved an accuracy of 79%.

🧠 Objective
To understand key academic and demographic factors influencing student placements and develop a reliable prediction model.

📁 Project Structure
Placement_Project.ipynb — Main Jupyter Notebook including:
Data preprocessing
Exploratory data analysis
Model training and evaluation
Visualizations (heatmaps, graphs)
📂 Dataset
Source: Campus Placement Dataset
Key Features:
gender, ssc_p, ssc_b, hsc_p, hsc_b, hsc_s
degree_p, degree_t, workex, etest_p, mba_p
status (Target: Placed / Not Placed)
🔍 Methodology
1. Data Exploration
Summary statistics and null value check
Distribution of placement status, gender, streams, etc.
2. Data Preprocessing
Encoding categorical variables
Splitting data into training and test sets
Balancing dataset using class_weight='balanced' for fairness
3. Model Training
Used RandomForestClassifier from Scikit-learn
Parameters: random_state=42, class_weight='balanced'
4. Evaluation Metrics
Accuracy: 79%
Confusion Matrix:
[[52  4]
 [12 13]]
Classification Report:
            precision    recall  f1-score   support

  Not Placed       0.81      0.93      0.87        56
      Placed       0.76      0.52      0.62        25

  accuracy                           0.79        81
 macro avg       0.79      0.73      0.74        81
weighted avg 0.79 0.79 0.78 81


### 5. Visualization
- Heatmap of Confusion Matrix using Seaborn
- Distribution plots for various attributes affecting placement

---

## 🛠️ Tech Stack

- **Python**
- **Libraries**:
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Placement_Project.ipynb` in Jupyter Notebook or [Google Colab](https://colab.research.google.com).
3. Run the notebook cells step-by-step to follow the complete pipeline.

---

## 📌 Key Insights

- Students with higher academic scores and MBA percentages are more likely to be placed.
- Work experience positively correlates with placement.
- The Random Forest model effectively handles feature interactions and imbalances.

---

## 👨‍💻 Author

**Rohit Chauhan
[GitHub: rohitchauhan2004] (https://github.com/rohitchauhan200)
📧 rohitchauhan8446@gmail.com
