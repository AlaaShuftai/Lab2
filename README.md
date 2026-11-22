# 🌸 Iris Insight – Iris Flower Classification

## 📌 Project Overview
Iris Insight is a Machine Learning project that analyzes and classifies Iris flowers into three different species based on their physical measurements.

The project uses the famous Iris dataset and applies data analysis, visualization, and classification techniques to understand the dataset and predict flower species.

## 🎯 Project Objectives
- Explore and understand the Iris dataset.
- Analyze relationships between flower features.
- Visualize data distributions and correlations.
- Apply Linear Discriminant Analysis (LDA).
- Build a Logistic Regression classification model.
- Evaluate the model's performance.

## 📊 Dataset
The project uses the Iris dataset from the UCI Machine Learning Repository.

It contains four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable consists of three Iris species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🛠️ Technologies & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Methodology

### 1. Data Loading & Preprocessing
- Load the Iris dataset.
- Assign column names.
- Separate features and target variables.
- Encode categorical labels using LabelEncoder.

### 2. Exploratory Data Analysis (EDA)
- Pair Plot to explore relationships between features.
- Histograms to visualize feature distributions.
- Correlation Heatmap to identify relationships between numerical variables.

### 3. Dimensionality Reduction
Apply Linear Discriminant Analysis (LDA) to transform the dataset into two components for visualization.

### 4. Model Training
Use Logistic Regression to train a classification model on the Iris dataset.

### 5. Model Evaluation
Evaluate the model using:
- Accuracy Score
- Confusion Matrix

## 📈 Results

The model achieved an accuracy of **97%** in the reported experiment.

A Confusion Matrix was also generated to evaluate the classification performance across the three Iris species.

*Note: The reported accuracy may vary between runs because the train-test split does not specify a fixed random state.*

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/iris-insight.git
   ```

2. Navigate to the project directory:

   ```bash
   cd iris-insight
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

4. Open the notebook using Jupyter Notebook or Google Colab.

5. Run the cells to explore the dataset, train the model, and view the results.

## 📂 Project Structure

```text
Iris-Insight/
│
├── Iris_Classification.ipynb
└── README.md
```

## 👩‍💻 Author
**Alaa Shuftai**

Data Science Student

---

⭐ If you find this project interesting, feel free to explore the repository!
