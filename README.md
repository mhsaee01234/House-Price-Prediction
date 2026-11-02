# 🏠 House Price Prediction using Linear Regression

An end-to-end Machine Learning project that predicts median house prices in California districts using **Multiple Linear Regression** and the **California Housing Dataset**.

---

## 📋 Project Overview

This project focuses on predicting median house prices in California using a supervised Machine Learning algorithm called Multiple Linear Regression.

The model analyzes different housing-related features, such as median income, house age, average rooms, population, and geographical location, to understand their relationship with house prices.

The main objective is to build a regression model, train it using the available housing data, make predictions, visualize the results, and evaluate the model's performance using different evaluation metrics.

---

## 🎯 Project Objectives

- Understand and explore the California Housing Dataset.
- Perform data analysis and visualization.
- Identify the relationship between housing features and house prices.
- Implement Multiple Linear Regression.
- Train and test the Machine Learning model.
- Predict median house prices.
- Evaluate model performance using regression metrics.

---

## 📊 Dataset Description

The project uses the **California Housing Dataset**, available through the Scikit-Learn library.

The dataset contains:

- **Total Records:** 20,640
- **Input Features:** 8
- **Target Variable:** 1

### Input Features

| Feature | Description |
| :--- | :--- |
| `MedInc` | Median income in a block group |
| `HouseAge` | Median house age in years |
| `AveRooms` | Average number of rooms per household |
| `AveBedrms` | Average number of bedrooms per household |
| `Population` | Block group population |
| `AveOccup` | Average number of household members |
| `Latitude` | Latitude coordinate |
| `Longitude` | Longitude coordinate |

### Target Variable

**`MedHouseVal`** – Median house value for California districts, expressed in hundreds of thousands of dollars ($100,000s).

---

## 🧠 Machine Learning Algorithm: Multiple Linear Regression

Multiple Linear Regression is a supervised Machine Learning algorithm used to predict a continuous numerical value based on two or more independent variables.

### Mathematical Equation

\[
y = \beta_0 + \beta_1X_1 + \beta_2X_2 + \dots + \beta_nX_n + \epsilon
\]

Where:

- \(y\) = Predicted house value
- \(\beta_0\) = Intercept
- \(\beta_1,\beta_2,\dots,\beta_n\) = Model coefficients
- \(X_1,X_2,\dots,X_n\) = Input features
- \(\epsilon\) = Error term

The model uses the Ordinary Least Squares (OLS) method to find the best-fitting linear relationship between the input features and the target variable.

---

## ⚙️ Project Workflow

The complete implementation is available in the [`House_Price_Prediction.ipynb`](./House_Price_Prediction.ipynb) notebook.

The project follows these steps:

1. **Importing Libraries:** Import the required Python libraries.
2. **Dataset Loading:** Load the California Housing Dataset.
3. **Data Exploration:** Examine the dataset and understand its features.
4. **Feature and Target Selection:** Separate independent variables (X) and the dependent variable (y).
5. **Train-Test Split:** Divide the dataset into training and testing sets.
6. **Model Building:** Create a Multiple Linear Regression model.
7. **Model Training:** Train the model using the training dataset.
8. **Prediction:** Predict house prices using the testing dataset.
9. **Model Evaluation:** Calculate MSE, MAE, RMSE, and R² Score.
10. **Data Visualization:** Visualize the relationship between median income and house prices and compare actual and predicted values.

### Train-Test Split

The dataset is divided into 80% training data and 20% testing data.

| Dataset | Percentage | Number of Records |
| :--- | :---: | :---: |
| Training Data | 80% | 16,512 |
| Testing Data | 20% | 4,128 |
| **Total** | **100%** | **20,640** |

The split is performed using `train_test_split()` with `test_size=0.2` and `random_state=42`.

---

## 📈 Model Evaluation and Results

The trained Linear Regression model is evaluated using the testing dataset.

The following evaluation metrics are used:

| Evaluation Metric | Result | Description |
| :--- | :---: | :--- |
| **Mean Squared Error (MSE)** | `0.5559` | Measures the average squared difference between actual and predicted values. |
| **Mean Absolute Error (MAE)** | `0.5332` | Measures the average absolute prediction error. |
| **Root Mean Squared Error (RMSE)** | `0.7456` | Represents the square root of the Mean Squared Error. |
| **R² Score** | `0.5758` | Indicates that the model explains approximately 57.58% of the variance in house prices. |

### Result Interpretation

The model achieved an R² Score of approximately 0.5758, indicating that it explains around 57.58% of the variation in median house prices in the testing dataset.

The evaluation metrics help measure the difference between actual and predicted values and understand the overall performance of the model.

---

## 📊 Data Visualization

The project includes the following visualizations:

### 1. Median Income vs House Price

A scatter plot showing the relationship between median income and median house prices.

### 2. Actual vs Predicted House Prices

A visualization comparing actual house prices with the values predicted by the Linear Regression model.

These visualizations help understand the relationship between the dataset features and the model's prediction performance.

---

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Python 3.x** | Programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Data visualization |
| **Scikit-Learn** | Machine Learning model and evaluation |
| **Google Colab / Jupyter Notebook** | Development environment |

---

## ▶️ How to Run the Project

### Step 1: Open the Notebook

Open the `House_Price_Prediction.ipynb` file in Google Colab or Jupyter Notebook.

### Step 2: Install Required Libraries

Install the required Python libraries if they are not already installed.

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Step 3: Execute the Notebook

Run all notebook cells in sequence.

### Step 4: View Results

Observe the model training, house price predictions, visualizations, and evaluation metrics.

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Working with a real-world dataset.
- Data exploration and analysis.
- Understanding independent and dependent variables.
- Preparing training and testing datasets.
- Implementing Multiple Linear Regression.
- Training a Machine Learning model.
- Making predictions using a trained model.
- Evaluating regression models using different metrics.
- Visualizing actual and predicted values.

---

## 🔮 Future Scope

- Experiment with other regression algorithms.
- Improve prediction performance through feature engineering.
- Compare different Machine Learning models.
- Develop an interactive web application for house price prediction.

---

## 📄 License

This project is licensed under the Apache License 2.0. See the [LICENSE](./LICENSE) file for details.

---

## 👩‍💻 Author

**Saee Mahangare**

B.Tech – Artificial Intelligence and Data Science

