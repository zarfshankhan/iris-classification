# Iris Flower Classification Using Machine Learning

## 📌 Project Overview

Iris Flower Classification is a supervised machine learning project that predicts the species of an iris flower based on its physical measurements. The model uses four features: sepal length, sepal width, petal length, and petal width.

The project classifies flowers into three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## 🎯 Objectives

- Clean and preprocess the Iris dataset.
- Explore and visualize flower measurements.
- Split the dataset into training and testing sets.
- Train a Random Forest classification model.
- Evaluate performance using standard classification metrics.
- Predict the species of new iris flowers.
- Identify important features for flower classification.

## 🚀 Goals

- Develop an accurate and reliable flower classification model.
- Understand the practical implementation of supervised machine learning.
- Gain experience with data preprocessing, visualization, model training, and evaluation.
- Learn how to use Python libraries for machine learning applications.

## 📊 Dataset Description

The Iris dataset contains 150 flower samples and four numerical features.

| Feature | Description |
|---|---|
| Sepal Length | Length of the flower's sepal |
| Sepal Width | Width of the flower's sepal |
| Petal Length | Length of the flower's petal |
| Petal Width | Width of the flower's petal |
| Species | Target class of the flower |

### Target Classes

- Iris-setosa
- Iris-versicolor
- Iris-virginica

**Dataset Source:** [Iris Flower Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

1. Import the required libraries.
2. Load the Iris dataset.
3. Explore the dataset using statistical summaries.
4. Clean missing values and duplicate records.
5. Visualize species distributions and feature relationships.
6. Separate input features and target labels.
7. Split the dataset into training and testing sets.
8. Train a Random Forest Classifier.
9. Evaluate the model using accuracy and classification metrics.
10. Predict the species of a new flower.

## 🤖 Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions. It is suitable for multiclass classification and can learn relationships between flower measurements and species.

## 📈 Model Evaluation

The model is evaluated using:

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures the correctness of positive predictions for each class.
- **Recall:** Measures how many actual examples of each class are correctly identified.
- **F1-score:** Combines precision and recall.
- **Confusion Matrix:** Shows correct and incorrect classifications.

The actual performance metrics are obtained by running the model on the test dataset.

## 📁 Project Structure

```text
iris-classification/
│
├── Iris.csv
├── iris_flower.ipynb
└── README.md
```

- `Iris.csv`: Dataset file.
- `iris-flower.ipynb`: Notebook containing preprocessing, visualization, training, and evaluation code.
- `README.md`: Project documentation.

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Iris-Flower-Classification.git
```

### 2. Navigate to the project folder

```bash
cd iris-Classification
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `iris-flower.ipynb` and run the cells in order.

Ensure that `Iris.csv` is in the correct project directory.

## 🔮 Example Prediction

The model accepts four measurements as input:

```python
new_flower = [[5.1, 3.5, 1.4, 0.2]]
prediction = model.predict(new_flower)

print("Predicted Species:", prediction[0])
```

The example measurements typically correspond to Iris-setosa.

## ✅ Expected Outcome

The trained model predicts one of the three iris species based on the flower's measurements. Its performance is assessed using the test dataset and classification metrics.

## 📚 Learning Outcomes

By completing this project, you will gain practical knowledge of:

- Data cleaning and preprocessing.
- Exploratory data analysis.
- Data visualization.
- Supervised machine learning.
- Multiclass classification.
- Model evaluation and prediction.

## 👨‍💻 Author

**Zarfshan Attiq Khan**

