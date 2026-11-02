# Student Marks Predictor 📊

A beginner-friendly Machine Learning project that predicts a student's marks based on academic factors using **Linear Regression**.

## 📌 Project Overview

The Student Marks Predictor uses supervised machine learning to estimate a student's expected marks based on input features such as study hours and attendance.

The project demonstrates the complete basic ML workflow, from preparing data and training a model to making predictions and saving the trained model.

## 🚀 Features

- Predict student marks using academic input features.
- Train a Linear Regression model.
- Split data into training and testing sets.
- Evaluate model performance using MAE and R² score.
- Visualize data and regression results.
- Save and load the trained model using Joblib.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

## 📂 Project Structure

```text
Student-Price-Predictor/
│
├── Student marks predictor.ipynb
├── student_marks_model.pkl
├── .gitignore
└── README.md
```

## ⚙️ Machine Learning Workflow

1. **Data Collection:** Prepare a dataset containing student academic information.
2. **Data Preprocessing:** Organize the dataset using Pandas.
3. **Feature Selection:** Select input features and the target variable.
4. **Train-Test Split:** Divide the dataset into training and testing sets.
5. **Model Training:** Train a Linear Regression model.
6. **Model Evaluation:** Evaluate predictions using Mean Absolute Error (MAE) and R² score.
7. **Model Persistence:** Save the trained model using Joblib for future predictions.

## 📈 Algorithm

**Linear Regression**

Linear Regression learns the relationship between input features and the target variable.

For multiple input features, the model follows:

`y = b0 + b1*x1 + b2*x2 + ... + bn*xn`

Where:
- `y` = Predicted marks
- `x` = Input features
- `b0` = Intercept
- `b1, b2, ...` = Model coefficients

## 💻 Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/Govind-ji/Student-Price-Predictor.git
```

### 2. Navigate to the project directory

```bash
cd Student-Price-Predictor
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn joblib jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Student marks predictor.ipynb` and execute the cells.

## 💾 Loading the Saved Model

The trained model is stored in `student_marks_model.pkl`.

```python
import joblib

model = joblib.load("student_marks_model.pkl")
```

Use the loaded model to make predictions with input features in the same format used during training.

## 🎯 Learning Outcomes

Through this project, I learned:

- Fundamentals of supervised machine learning.
- Data manipulation using Pandas and NumPy.
- Linear Regression and model training.
- Training and testing data separation.
- Model evaluation using MAE and R².
- Saving and loading trained ML models.

## 👨‍💻 Author

**Devesh Gupta**

B.Tech – Computer Science and Engineering

GitHub: [Govind-ji](https://github.com/Govind-ji)

---

*This project was developed as part of my journey into Machine Learning and practical AI development.*