# Project Discussion & Planning Document

## 1. Project Question
**What variables best predict a successful workout (defined as higher calories burned)?**

## 2. The Data
* Dataset source: Kaggle (contains workout metrics, demographics, fitness stats).
* Variables include: calories burned, heart rate, workout duration, age, gender, BMI, frequency, water intake, fat percentage, etc.
* Data cleaning steps performed:
  * Filtered dataset to include only HIIT and Cardio workouts.
  * Removed irrelevant workout types (Yoga, Strength training).
  * Processed feature variables.

## 3. Preprocessing
* Handled missing values.
* Encoded categorical variables.
* Normalized numerical features.
* Removed workout types unrelated to calorie-burning prediction.

## 4. Computational Tools
* **pandas** — data cleaning and manipulation.
* **numpy** — numerical operations.
* **scikit-learn** — logistic regression model.
* **matplotlib / seaborn** — visualizations.

### Limitations
* Logistic Regression assumes linear separability.
* Dataset does not include muscle mass, stress, or non-calorie workout success indicators.

## 5. Modeling & Analysis Plan
* Use multivariable logistic regression.
* Evaluate model with:
  * Accuracy
  * Feature importance / coefficients
* Compare predictors and interpret coefficients.

## 6. Code Organization Plan
* `/notebooks/` for modeling & analysis.
* `/csv/` for raw dataset.
* `/pdf/` for report.
* `/md/` for planning files.


## 7. README Content Planning
* How to run the code.
* Dataset description.
* Project overview.
* Group member contributions.
* Repository structure.

## 8. Presentation Planning
* under 10 minutes
* Include:
  * Research question
  * Dataset summary
  * Model approach
  * Key findings (session duration + BPM as strongest predictors)
  * Limitations