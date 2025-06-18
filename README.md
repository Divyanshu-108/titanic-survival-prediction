# 🚢 Titanic Survival Prediction using Machine Learning

This project is a machine learning solution to predict passenger survival on the Titanic using data from the famous Kaggle Titanic dataset. I used a **Decision Tree Classifier** and achieved an impressive **97% accuracy**.

---

## 📌 Project Highlights

- ✅ Achieved **97% accuracy** using a Decision Tree model
- 🧪 Performed **hyperparameter tuning** to optimize the model performance
- 🔍 Conducted **Exploratory Data Analysis (EDA)** to find key survival indicators
- 💡 Identified that **Sex**, **Pclass**, and **Age** play a major role in survival
- 📊 Visualized correlations, survival rates, and confusion matrix
- 💬 Built the project in **VS Code** using the **Jupyter Notebook extension**

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**
   - Handled missing values in `Age` and `Embarked`
   - Encoded categorical variables (`Sex`, `Embarked`, etc.)

2. **Exploratory Data Analysis**
   - Correlation heatmaps and bar charts
   - Survival distribution based on sex and passenger class

3. **Model Training**
   - Trained multiple models (tested Logistic Regression, Random Forest)
   - Finalized **Decision Tree Classifier** for its high accuracy and interpretability

4. **✅ Hyperparameter Tuning**
   - Used **GridSearchCV** to fine-tune hyperparameters like:
     - `max_depth`
     - `min_samples_split`
     - `min_samples_leaf`
     - `criterion` (`gini` or `entropy`)
     - criterion= 'entropy',
     - max_features,
     - random_state, 
     - max_leaf_nodes,
 
 splitter = 'random'
   - Improved model performance and avoided overfitting

5. **Evaluation**
   - Evaluated with **confusion matrix**, **precision**, **recall**, and **F1-score**
   - Visualized model results with graphs

---

## 📊 Visuals

- ✅ Correlation of features with survival
- ✅ Confusion matrix showing true vs predicted outcomes
- ✅ Bar chart of survival rate by gender
- ✅ Decision Tree structure (optional visualization)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook (in VS Code)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for ML model and GridSearchCV)

---

## 📂 Files Included

- `titanic_model.ipynb` – Main notebook with code and output
- `titanic.csv` – Titanic dataset (can also be downloaded from Kaggle)
- `output_graphs/` – Graphs and visualizations
- `requirements.txt` – Python dependencies
- `README.md` – Project overview

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
