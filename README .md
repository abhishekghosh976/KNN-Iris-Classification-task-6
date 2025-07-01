
# Task 6 - KNN Classification using Iris Dataset

## 🔍 Objective:
Implement the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset.

## 📦 Dataset:
- **Source**: [UCI Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Iris Species (Setosa, Versicolor, Virginica)

## ⚙️ Steps Performed:
1. Loaded and cleaned the dataset (dropped 'Id' column if present).
2. Normalized features using `StandardScaler`.
3. Split data into training and testing sets (80/20).
4. Trained KNN models using various values of **k**.
5. Evaluated performance using **accuracy**, **confusion matrix**, and **classification report**.
6. Visualized **decision boundaries** using 2D features.

## 📈 Best Accuracy:
Achieved with **k = 3**

## 🛠 Tools Used:
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📁 Files Included:
- `Iris.csv` — original dataset
- `Cleaned_Iris.csv` — processed dataset
- `KNN_Iris_Classification.ipynb` — main code
- `README.md` — this file

## ✅ How to Run:
Run the notebook `KNN_Iris_Classification.ipynb` in Google Colab or Jupyter Notebook.

## 📤 Submission:
Upload all files to GitHub and submit your repository link.
