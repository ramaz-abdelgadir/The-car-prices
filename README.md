# The car Prices

**Project The Car price** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The Car dataset contains details about cars and their attributes that can be used for price prediction.

.


## Business Requirements
* The goal of this project is to analyze and predict car prices based on various car attributes using the CarPrice_Assignment dataset.

Key objectives:

Understand the dataset — explore and clean the data to ensure quality and accuracy for modeling.

Visualize trends — create clear and meaningful charts showing relationships between features and price, such as horsepower distribution, price vs. engine size, and fuel type comparisons.

Develop predictive models — build and evaluate machine learning models to predict car prices based on the given features.

Support decision-making — provide insights that can assist dealerships, manufacturers, and buyers in understanding car value trends and making informed pricing decisions.


## Hypothesis 
* Hypothesis 1: Cars with higher horsepower tend to have higher prices.
* Hypothesis 2: Engine size is a stronger predictor of price than fuel type.
* Hypothesis 3: Cars from certain brands (e.g., luxury brands) have higher average prices regardless of technical specifications.
* Hypothesis 4: Automatic transmission cars are generally priced higher than manual transmission cars.

# Project Plan
### Data Collection

Obtained CarPrice_Assignment.csv dataset from Kaggle.

Downloaded and stored the raw dataset in a dedicated Dataset/raw folder.

### Data Understanding

Inspected dataset structure using Pandas (.head(), .info(), .describe()).

Identified numerical, categorical, and datetime fields relevant for analysis.

### Data Cleaning & Processing

Handled missing values (if any) and removed duplicates.

Converted data types (e.g., ensuring numerical columns are floats/integers).

Standardised column names for consistency.

Saved cleaned dataset in Dataset/clean folder for version control.

Exploratory Data Analysis (EDA)

Visualised key variables using Plotly, Matplotlib and Seaborn (histograms, scatter plots, boxplots).
If I have time before deadline I would also do:

### Advanced Visualisations & Insights

Created pairplots, heatmaps, and categorical comparisons to understand trends.

Segmented analysis by brand, body style, and fuel type.

### Interpretation & Reporting

Summarised findings in a Jupyter Notebook with Markdown explanations.

Documented visual insights and statistical results to validate hypotheses.



## The rationale to map the business requirements to the Data Visualisations
* Understand how key car features (e.g., horsepower, engine size, fuel type) influence car price.

Rationale: This helps stakeholders identify which specifications drive higher prices and can guide pricing strategies or marketing focus.

Mapped Visualisations:

Scatter plots of horsepower vs price and engine-size vs price to reveal relationships.

Regression plots to visualise trend lines and correlations.

Heatmap showing correlations between numerical variables, including price.

* Identify the distribution of prices across different brands and body styles.

Rationale: Allows the business to segment the market and understand positioning of different brands and categories.

Mapped Visualisations:

Boxplots of price grouped by make (brand) to highlight spread and outliers.

Bar charts showing average prices for each body-style.



## Analysis techniques used
### Data Analysis Methods Applied
Descriptive Statistics – Used pandas.describe() to summarise measures like mean, median, min, max, and standard deviation for numerical features.

Correlation Analysis – Used Pearson correlation (df.corr()) and heatmaps to understand relationships between numerical variables such as horsepower and price.

Visual Exploratory Data Analysis (EDA) – Leveraged Matplotlib and Seaborn to create histograms, scatter plots, box plots, and regression plots to detect patterns and outliers.

Categorical Analysis – Grouped data by categories such as make, body-style, and fuel-type to compare average prices.

Feature Distribution Analysis – Used KDE plots and histograms to inspect the spread of key features like horsepower and engine-size.

## Ethical considerations
*The dataset used (CarPrice_Assignment.csv) contains no personally identifiable information (PII) such as names, addresses, or contact details.

All data is publicly available from open sources (e.g., Kaggle), so there are no GDPR or data protection compliance issues.

No sensitive customer data was collected or processed.




## Unfixed Bugs
*Occasionally, histograms and scatter plots display overlapping labels when plotting many categories (e.g., car make). the heat map I created was too busy showing too many variables and it was not readable, so I had to remove non-useful columns like car_id, curbwight and highwaymgp.  

## Development Roadmap
### Challenge:
Encountered difficulties with debugging and fixing non-functional code, including syntax errors, logical mistakes, and incorrect method usage.
Strategy: Adopted a structured troubleshooting approach by breaking down code into smaller testable components, using error messages to guide fixes, consulting official documentation, and iteratively refining the code until the desired output was achieved. Additionally, leveraged AI tools such as GitHub Copilot and ChatGPT to generate alternative code suggestions, clarify concepts, and optimise solutions.


## Main Data Analysis Libraries
Pandas
NumPy
Matplotlib
Seaborn
Pathlib


## Credits 

### Content
Kaggle – The CarPrice_Assignment.csv dataset was sourced from Kaggle Datasets for the purpose of performing exploratory data analysis and visualisation.

Pandas Documentation – For guidance on DataFrame manipulation and method usage: https://pandas.pydata.org/docs

NumPy Documentation – For numerical computations and random data generation: https://numpy.org/doc

Matplotlib Documentation – For creating static visualisations: https://matplotlib.org/stable/contents.html

Seaborn Documentation – For enhanced and statistical visualisations: https://seaborn.pydata.org/

GitHub Copilot – Assisted in writing, optimising, and debugging Python code.

ChatGPT – Provided guidance, explanations, and example code snippets for data cleaning, exploratory data analysis, and visualisation tasks.

### Media
All visualisations and plots were created by me using Matplotlib and Seaborn within the Jupyter Notebook environment in VS Code.

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site


## Acknowledgements (optional)
*I would like to express my sincere gratitude to Vasi for their continuous support, guidance, and availability throughout the course of this project. Their expertise and willingness to assist at every stage greatly contributed to the successful completion of this work.


