# 🍷 Wine Classifier using Random Forest 🌿

## 🔍 Project Overview
This project builds a **Machine Learning model** that classifies wine samples as **🍇 Legit** or **🚫 Fraudulent** based on their **chemical properties**. Using the **🌲 Random Forest Classifier**, the model learns patterns from various physicochemical parameters to ensure **wine authenticity** and **quality verification**.

---

## 🧠 Objective
Develop a reliable classification system to detect fraudulent wine samples by analyzing quantitative features like acidity, density, alcohol content, and more.

---

## 📂 Dataset
The dataset includes several chemical composition features such as:
- 🧪 Fixed acidity  
- 💨 Volatile acidity  
- 🍋 Citric acid  
- 🍬 Residual sugar  
- 🧂 Chlorides  
- 💧 Free sulfur dioxide  
- 🌫️ Total sulfur dioxide  
- ⚖️ Density  
- 🧫 pH  
- 💥 Sulphates  
- 🍶 Alcohol  
- 🏷️ Quality Label (Legit/Fraud)

📊 **Source:** Open-source dataset (Kaggle / UCI ML Repository)

---

## ⚙️ Workflow

1. **🧹 Data Preprocessing**
   - Handling missing values and outliers  
   - Encoding categorical variables  
   - Scaling numeric features  

2. **📊 Exploratory Data Analysis (EDA)**
   - Feature distribution visualization  
   - Correlation heatmap for feature importance  

3. **🤖 Model Building**
   - Algorithm: 🌲 Random Forest Classifier  
   - Train-test split for model validation  
   - Hyperparameter tuning using GridSearchCV  

4. **📈 Model Evaluation**
   - Metrics: Accuracy ✅ | Precision 🎯 | Recall 🔁 | F1-score 🏅  
   - Confusion Matrix visualization  

5. **🧾 Prediction on Unseen Data**
   - Model (`wine_classifier_model.pkl`) predicts authenticity on new samples  

---

## 🧩 Results
✅ High accuracy on test data  
🍷 Successfully distinguishes **legit** vs **fraudulent** wines  
🌿 Random Forest outperformed baseline models (Logistic Regression, Decision Tree)

---

## 💡 Key Insights
- 🍶 Alcohol and ⚖️ Density strongly correlate with wine authenticity  
- 🧠 Ensemble models improve generalization  
- 📊 Balanced preprocessing enhances model reliability  

---

## 🛠️ Technologies Used
| Tool | Purpose |
|------|----------|
| 🐍 Python | Core programming language |
| ⚙️ Scikit-learn | ML model building |
| 📊 Pandas, NumPy | Data processing |
| 📉 Matplotlib, Seaborn | Data visualization |
| 💻 Jupyter / Google Colab | Interactive development |

---

## 📦 Files in Repository
| File | Description |
|------|--------------|
| `Wine_Classifier(RF).ipynb` | Model training notebook |
| `wine_data.csv` | Dataset used for training |
| `wine_classifier_model.pkl` | Saved trained model |
| `README.txt` | Documentation file |

---

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Wine-Classifier-RF.git
   ```
2. Navigate to the project folder  
   ```bash
   cd Wine-Classifier-RF
   ```
3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook  
   ```bash
   jupyter notebook Wine_Classifier(RF).ipynb
   ```

---

## 🔮 Future Enhancements
- 🌐 Deploy using Flask/Django web app  
- 🧩 Integrate deep learning models (ANN, CNN)  
- 💬 Add explainability (SHAP/LIME) for feature importance visualization  

---

## 🏆 Author
👤 **Your Name**  
💬 Passionate about Data Science & ML | Building Intelligent Systems  
📧 your.email@example.com  

⭐ *If you like this project, consider giving it a star!* 🌟


🏆 Author

Harshita Sharma
💬 Passionate about Data Science & ML | Building Intelligent Systems
E-mail: harshitash1107@gmail.com
