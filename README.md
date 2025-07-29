📌 Titanic Survival Analysis
📝 Overview
This project analyzes the Titanic dataset to explore survival rates based on different factors such as gender, passenger class, age, and other variables.
It includes data visualization, statistical summaries, and insights about the survival patterns.

📂 Dataset
The analysis uses the train.csv dataset from the Titanic Kaggle competition.
Key columns include:

Survived: Survival (0 = No, 1 = Yes)

Pclass: Ticket class

Sex: Gender

Age: Age of passenger

SibSp / Parch: Number of siblings/spouses and parents/children aboard

Fare: Passenger fare

⚙️ Installation & Requirements
To run the notebook, make sure you have Python 3.x installed with the following libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
🔎 Steps in the Notebook
Load libraries and dataset

Data Exploration: Missing values, distributions, and unique values

Survival Analysis:

Survival counts (overall)

Survival rate by gender

Survival rate by passenger class (Pclass)

Survival rate by embarked port and other features

Visualization: Countplots, barplots, and boxplots using seaborn & matplotlib

📊 Example Visualizations
Distribution of survivors vs. non-survivors

Gender vs. survival rate

Class vs. survival rate

🚀 How to Run
Clone the repository or download the notebook.

Open it in Jupyter Notebook or Google Colab.

Run all cells to reproduce the analysis and plots.

🏆 Key Insights (From the Notebook)
Females had a much higher survival rate than males.

Passengers in 1st class were more likely to survive than those in 2nd or 3rd class.

Other demographic and ticket-related features also affected survival.
