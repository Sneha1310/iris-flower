# iris-flower
## 📌 Conclusion

In this project, I built a supervised machine learning model to classify iris flowers into three species — Setosa, Versicolour, and Virginica — using features such as sepal length/width and petal length/width.

The dataset was clean and balanced, making it ideal for exploratory analysis. Through visualizations like pairplots, heatmaps, violin plots, and scatter plots, I observed that **petal length and petal width** were highly discriminative features, especially in separating Setosa from the other two species.

Three classification algorithms were applied:
- **K-Nearest Neighbors**
- **Logistic Regression**
- **Support Vector Machine (Linear Kernel)**

All three models achieved **100% accuracy** on the test set, which reflects the separability of the classes and effectiveness of the features. Confusion matrices and classification reports confirmed perfect precision, recall, and F1-scores across all classes.

### 🔍 Key Takeaways:
- The Iris dataset is an excellent example of how simple models can perform remarkably well when the data is well-structured and features are informative.
- Petal dimensions are the most important features for classification.
- All three models performed equally well, but SVM is often preferred for high-dimensional and real-world cases.

### 🚀 Future Improvements:
- Try non-linear kernels with SVM (like RBF)
- Apply cross-validation and GridSearch for hyperparameter tuning
- Deploy the model using Flask or Streamlit for web interaction

This project gave me hands-on experience with the entire ML pipeline — from data exploration and preprocessing to modeling and evaluation — making it a valuable part of my data science journey.
