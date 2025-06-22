# iris-flower
# 🌸 Iris Flower Classification

This project uses machine learning to classify iris flowers into three species — Setosa, Versicolour, and Virginica — based on features such as sepal and petal length and width. It demonstrates a full ML workflow including data visualization, preprocessing, model training, and evaluation.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Size**: 150 samples (50 samples per species)
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)

---

## 🧠 ML Workflow

1. **Import and load the dataset**
2. **Exploratory Data Analysis (EDA)** using:
   - Pairplots
   - Boxplots & Violin plots
   - Heatmaps & Correlation analysis
3. **Data preprocessing**:
   - Label encoding
   - Feature scaling with `StandardScaler`
4. **Train-test split** with stratification
5. **Model training**:
   - K-Nearest Neighbors (KNN)
   - Logistic Regression
   - Support Vector Machine (SVM)
6. **Evaluation** using:
   - Accuracy
   - Classification report (precision, recall, F1)
   - Confusion matrix

---

## 📊 Results

All three models achieved **100% accuracy** on the test data, confirming the simplicity and separability of the Iris dataset.

| Model                  |Accuracy|
|------------------------|--------|
| K-Nearest Neighbors    |  1.00  |
| Logistic Regression    |  1.00  |
| Support Vector Machine |  1.00  |

---

## 📌 Conclusion

This project highlights how classical ML models can achieve perfect accuracy on well-structured, linearly separable datasets like Iris. Petal length and width were the most informative features. The results emphasize the importance of EDA and model evaluation in building reliable classifiers.

---

## 🔧 Tech Stack

- Python (Jupyter Notebook)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 📁 Project Structure
Iris-Flower-Classification/
├── README.md                  
├── iris.csv                   
├── iris_flower.ipynb         

---

## 👩‍💻 Author

**Sneha Jha** 
BCA (Data Science), 5th Semester  
Aspiring Data Scientist

---

## 📝 License

This project is licensed under the [MIT License](./LICENSE).



