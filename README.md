# Netflix_Data_Cleaning Project
Data cleaning and preprocessing of the Netflix Movies &amp; TV Shows dataset using Python and Pandas.

## Project Overview
This project focuses on cleaning and preparing the Netflix Movies and TV Shows dataset for analysis. The dataset contains information about Netflix content, including movies and TV shows, along with details such as title, director, cast, country, rating, release year, and duration.

The primary goal of this project is to identify and resolve data quality issues, making the dataset suitable for analysis and visualization.

---

## Dataset Information

- Dataset: Netflix Movies and TV Shows
- Total Records: 8,807
- Features: 12+
- Source: Kaggle

---

## Data Cleaning Tasks Performed

### 1. Missing Value Treatment
Handled missing values in the following columns:
- Director
- Cast
- Country
- Date Added
- Rating
- Duration

### 2. Date Formatting
- Removed unnecessary spaces.
- Converted the "date_added" column to datetime format.

### 3. Duplicate Check
- Checked for duplicate records.
- No duplicate rows were found.

### 4. Duration Cleaning (Feature Engineering)
Split the "duration" column into:
- "duration_value"
- "duration_type"

Examples:
- 90 min → Value: 90, Type: min
- 3 Seasons → Value: 3, Type: Seasons

### 5. Text Processing
Prepared text-based columns for future analysis:

- Cast
- Country
- Genres (listed_in)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

1. Load Dataset
2. Explore Data
3. Handle Missing Values
4. Clean Date Columns
5. Process Duration Column
6. Prepare Text Features
7. Export Clean Dataset

---

## Key Learning Outcomes

Through this project, I learned:
- Handling missing values
- Data type conversion
- Date preprocessing
- Feature engineering
- Data quality assessment
- Preparing data for analysis

---

## Output
The final cleaned dataset was exported as:

[(./cleaned_netflix.csv)]

---

## Author

Awais Khatti
Aspiring Data Scientist | AI Enthusiast | Python & Data Analytics Learner

---

If you found this project useful, feel free to star the repository and connect with me on LinkedIn.
https://www.linkedin.com/in/awais-khatti-b34a243a1
