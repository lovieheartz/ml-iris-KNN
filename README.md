# 🌸 KNN Classification on Iris Dataset

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers based on sepal and petal dimensions. The dataset used is the classic Iris dataset.

## 📁 Dataset
The dataset (`Iris.csv`) includes:
- **150 samples** with 4 features: `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`
- **Target**: Species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)

## ✅ What’s Included
- **Data Preprocessing**: Label encoding, normalization, and train-test split
- **Model Training**: KNN classifier with optimal `k` selection using cross-validation
- **Evaluation**: Accuracy score, confusion matrix, classification report
- **Advanced Visuals**:
  - Confusion matrix heatmap
  - Classification report heatmap
  - Cross-validation accuracy curve
  - t-SNE projection of data in 2D space

## 🛠 How to Run
1. Upload `Iris.csv` in your Google Colab or local notebook environment.
2. Run the code cells step-by-step.
3. Analyze outputs and tweak `k` if needed.

## 📌 Requirements
- Python 3.x
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## 📊 Results
Achieved **90%+ accuracy** on test data with K=3. Cross-validation confirms model generalizes well on unseen data.

---

Enjoy exploring this beautiful dataset with machine learning! 🌼
