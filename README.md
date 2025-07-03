# CODSOFT-TASK-2

COMPANY : CODSOFT

NAME : SHARIKAA.D

ROLE : DATA SCIENCE

DURATION : 4 WEEKS

INTERN ID : CS25RY81758

# Provide a Movie Rating Prediction with Python

This whole project belongs to my **CodSoft Internship - Task 2**. Basically, I created a machine learning model that is capable of predicting **movie ratings** based on the features such as **genre, duration, votes, year, director** and **actors**.

---

## 📂 Datasets

**Source:** [Kaggle's IMDb Indian Movies Dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)

The dataset contains attributes of Indian movies such as:
- Name, Year, Duration
- Genre, Rating, Votes
- Director, Actor 1–3

---

## 📊 Aim

To analyze history movie data and produce the good model that when given information on:
- Genre
- Runtime
- Number of Votes
- Year
- Number of Actors
- Director's average rating

The model accurately predicts the **IMDb rating** of a movie.

---

## 🛠️ Steps Followed

1. **Data Cleaning**
   - Contained commas in numeric columns such as `Votes`.
   - Extracted numeric fields from `Year` and `Duration`.
   - Combined Actor 1, 2, and 3 into one column.
   - Handle null.

2. **Feature Engineering**
   - Number of actors counted.
   - Calculated the average rating per director.

3. **Preprocessing**
   - Applied OneHotEncoding on Categorical features (`Genre`)
   - Scaled Numerical features using StandardScaler

4. **Modeling**
   - Implemented the RandomForestRegressor from scikit-learn
   - Built a pipeline to combine the preprocessor with the model
   - Trained on 80% and tested on 20%

5. **Evaluation**
   - Evaluated using RMSE and R²
   - Actual vs Predicted ratings visualized in a scatter plot

---

## 📈 Results

- ✅ **Root Mean Squared Error (RMSE):** ~<insert RMSE here>
- ✅ **R² Score:** ~<insert R² score here>

---

## 💡 Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 📁 How to Run

1. Upload the dataset (`imdb_india.csv`) in Colab or your working directory
2. Run all code cells from `Step 1` to `Step 8` as shown
3. Predict movie ratings or add a Streamlit app for interactive input

---

## 🙋‍♀️ About Me

I'm learning Python and Data Science at the moment; this project has contributed to my learning journey. This task has helped me learn about:
- Feature extraction
- Handling real-world messy data
- Building and evaluating regression models

  OUTPUT:
  ![Image](https://github.com/user-attachments/assets/1b533d0b-92d8-4ac0-94ea-52da97b9aa85)

![Image](https://github.com/user-attachments/assets/98cf0f7a-6e62-4aea-8dc3-9c927797a346)
  
