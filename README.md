# FUTURE_DS_01
 **Data Cleaning and Exploratory Data Analysis of the Titanic Dataset 🚢**
I recently undertook a project to analyze the Titanic dataset, a classic dataset used in data science and machine learning. Here’s a brief overview of the tasks I completed and the insights I gained:

1. **Data Loading and Initial Inspection**:
I started by loading the dataset using Pandas and performed an initial inspection to understand its structure. I checked for missing values, particularly in the 'Age', 'Cabin', and 'Embarked' columns.

2. **Data Cleaning**:
- **Missing Values**: I filled missing 'Age' values with the median age, as it provides a better estimate without skewing the data. The 'Cabin' column had too many missing values, so I decided to drop it entirely. For 'Embarked', I removed rows with missing values to ensure the integrity of my analysis.
  
3. **Descriptive Statistics**:
Using `df.describe()`, I generated summary statistics that provided insights into the distribution of key variables such as age, fare, and survival rates. This helped me understand the central tendencies and variations in the dataset.

4. **Visualizations**:
I created several visualizations using Seaborn to explore relationships between variables:
- **Survival Rates by Gender**: Visualizing the survival rates revealed that women had a significantly higher survival rate compared to men.
- **Survival Rates by Passenger Class**: The analysis showed that first-class passengers had a higher survival rate than those in second and third class.

📈 **Knowledge Gained**:
Through this project, I deepened my understanding of data cleaning techniques, the importance of handling missing values, and the power of visualizations in uncovering trends and patterns in data. I also enhanced my skills in using Python libraries like Pandas and Seaborn for data analysis.

__Conclusion:_
This project was not only a great learning experience but also a reminder of the importance of data integrity in analysis._
