# Student Performance Indicator

## 📌 Understanding the Problem Statement

The **Student Performance Indicator** project aims to understand and predict student academic performance based on various demographic, social, and educational factors.

The project analyzes how a student's test scores are influenced by variables such as:

* Gender
* Ethnicity
* Parental level of education
* Lunch type
* Test preparation course

The project follows a complete machine learning workflow, starting from data collection and preprocessing to model training, evaluation, and selection of the best-performing model.

---

## 🎯 Problem Statement

The objective of this project is to understand the factors that affect students' performance in examinations and build a machine learning model capable of predicting student performance based on the available input features.

The target variables are the students' examination scores:

* **Math Score**
* **Reading Score**
* **Writing Score**

The analysis can help identify relationships between students' backgrounds, preparation, and their academic performance.

---

## 📊 Data Collection

### Dataset Source

The dataset is available on Kaggle:

[Student Performance in Exams – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)

### Dataset Information

The dataset contains:

* **1000 rows**
* **8 columns**

The original dataset includes the following features:

| Feature                       | Description                                               |
| ----------------------------- | --------------------------------------------------------- |
| `gender`                      | Gender of the student                                     |
| `race/ethnicity`              | Student's ethnic group                                    |
| `parental level of education` | Highest education level attained by the student's parents |
| `lunch`                       | Type of lunch received by the student                     |
| `test preparation course`     | Whether the student completed a test preparation course   |
| `math score`                  | Student's mathematics score                               |
| `reading score`               | Student's reading score                                   |
| `writing score`               | Student's writing score                                   |

---

## 🔍 Project Workflow

The project follows these major steps:

1. Understanding the Problem Statement
2. Data Collection
3. Data Checks
4. Exploratory Data Analysis
5. Data Pre-Processing
6. Model Training
7. Model Evaluation
8. Choosing the Best Model

---

## 1. Understanding the Problem Statement

The primary goal is to analyze the relationship between student characteristics and examination performance.

The project investigates questions such as:

* Does gender have an impact on test scores?
* Does parental education influence student performance?
* Does completing a test preparation course improve scores?
* Is there a relationship between lunch type and academic performance?
* Which factors are most strongly associated with student scores?

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Student-Performance-Indicator
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Project

```bash
python app.py
```

If the project is notebook-based, open the Jupyter Notebook and execute the cells sequentially.

---

## 📈 Results

The project analyzes student performance and identifies relationships between demographic/educational factors and examination scores.

---

## 🔮 Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* More advanced regression models
* Model explainability
* Deployment using Flask or FastAPI
* Building an interactive prediction interface
* Adding additional student-related features

---

