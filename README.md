# Student Performance Prediction 🎓📊

This project aims to develop a machine learning model to predict students' academic performance based on various factors such as attendance, study habits, and socio-economic background. The dataset contains information about student demographics, parental education, and test scores.

---

## Dataset Overview
The dataset contains 1000 rows and the following features:
- **gender**: Gender of the student (male/female).
- **race/ethnicity**: Group of the student.
- **parental level of education**: The highest education level of the parent.
- **lunch**: Type of lunch (standard or free/reduced).
- **test preparation course**: Completion status of a test preparation course.
- **math score**: Student's math score.
- **reading score**: Student's reading score.
- **writing score**: Student's writing score.

**Target Variable**: 
- `performance_category`: Categorized as **Excellent**, **Good**, **Average**, and **Poor** based on the average score of math, reading, and writing.

---

## Project Objective
The objective of this project is to:
1. Analyze the data for meaningful insights.
2. Categorize student performance into four levels:
   - **Excellent**: Scores between 90-100.
   - **Good**: Scores between 75-89.
   - **Average**: Scores between 50-74.
   - **Poor**: Scores below 50.
3. Build a machine learning model to predict student performance categories.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - sklearn

---

## Steps Followed
### 1. Data Preprocessing
- Calculated the `average_score` as the mean of math, reading, and writing scores.
- Created a new column, `performance_category`, based on the average score.
- Encoded categorical variables using `LabelEncoder`.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of performance categories.
- Analyzed the correlation between features using a heatmap.
- Examined relationships between gender and average scores.

### 3. Model Development
- Selected a **Random Forest Classifier** to predict student performance.
- Split the data into training and testing sets (80%-20% split).
- Evaluated the model using metrics like:
  - Classification Report
  - Confusion Matrix
  - Accuracy Score

---

## Visualizations
This project includes several visualizations to better understand the dataset:
- **Distribution of Performance Categories**: Bar plot showing the count of students in each performance category.
- **Average Score by Gender**: Bar chart comparing average scores between male and female students.
- **Correlation Heatmap**: Highlights relationships between numerical features.

