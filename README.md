# Corizo Data Science Apprenticeship

## Day 1
### **Fundamentals of Data Science and Python Programming**
1. **Data Science Introduction:** It outlines data collection, cleaning, analysis, and deployment of models to extract insights.
2. **Python Basics:** Covers variables, arithmetic operations, strings, data types (integers, floats, strings, lists, tuples, dictionaries, boolean), and basic operations with these types.
3. **Lists and Dictionary Operations:** Details operations like indexing, slicing, appending, inserting, removing, and other manipulations with lists and dictionaries.
4. **Conditional Statements, Loops, and Functions:** Introduces conditional statements (if, Elif, else), loops (for, while), and functions, demonstrating their use in decision-making, iteration, and creating reusable code blocks.

## Day 2
### Efficient Data Handling with NumPy and Pandas
1. **NumPy Arrays:** NumPy provides support for creating and manipulating multidimensional arrays, which are more efficient for numerical computations than Python lists.
2. **Array Operations:** With NumPy, you can perform element-wise operations, broadcasting, and matrix multiplication, which streamline mathematical calculations.
3. **Pandas DataFrames:** Pandas introduces DataFrames, a tabular data structure with labeled axes, which simplifies data manipulation and analysis.
4. **Data Handling in Pandas:** Pandas offers powerful tools for data cleaning, filtering, and aggregation, making it ideal for working with structured data.

## Day 3
### **Forbes Billionaires Dataset Analysis Workflow**
1. **Data Loading and Cleaning:** The script starts by mounting Google Drive to access the dataset. It loads the Forbes Billionaire data into a Pandas DataFrame, checks the dataset's structure by viewing its shape, and performs initial exploration to ensure the data is ready for further analysis.
2. **Data Manipulation:** The script utilizes Pandas functions such as `groupby()` to aggregate data, `value_counts()` to count occurrences of industries, and `mean()` to calculate average values like net worth and age. These operations help summarize and extract key insights from the dataset.
3. **Filtering and Sorting:** The script selects specific subsets of data by applying conditions, such as filtering billionaires by industry or country. It then sorts these subsets based on criteria like net worth or age, enabling the identification of top industries, countries, and individuals within the dataset.
4. **Statistical Analysis:** The script computes descriptive statistics, including the mean net worth and age of billionaires, to analyze trends across different categories. It compares these statistics across industries and countries, providing insights into the wealth distribution and demographic profiles of billionaires.

## Day 4
### **Types of Data Visualizations and Their Uses**
Data visualization is the graphical representation of data using charts, graphs, and plots. It simplifies complex data, making it easier to identify patterns, trends, and outliers. Visualizations enhance data understanding and communication, aiding in better decision-making and storytelling with data.
1. **Histogram**: Visualizes the distribution of a continuous numerical variable by breaking it into equal intervals and counting observations in each.
2. **Kernel Density Estimation (KDE)**: Visualizes the distribution of data over a continuous interval, often overlaid on a histogram.
3. **Boxplot**: Shows distribution, skewness, and outliers in numerical data using a five-number summary (min, Q1, median, Q3, max).
4. **Bar Graph**: Displays counts of categorical variable groups using bars.
5. **Lineplot**: Connects data points with lines to display trends or patterns, often over time.
6. **Scatterplot**: Plots individual data points to visualize the relationship between two variables.
7. **Correlation**: Measures the association between two variables; positive, negative, or none.
8. **Lmplot**: Combines scatterplot with a linear regression model and confidence interval.
9. **Jointplot**: Visualizes the relationship between two variables and their distributions in a single plot.
10. **Violin Plot**: Combines boxplot with KDE, showing the distribution of a numeric variable for different groups.
11. **Strip Plot**: Displays individual data points differentiated by categories, useful for small datasets.
12. **Swarm Plot**: Similar to a strip plot but avoids overlapping points, showing data distribution more clearly.
13. **Catplot**: Flexible framework for plotting categorical data, supporting multiple plot types like strip, swarm, and boxplots.
14. **Pair Plot**: Displays pairwise relationships between multiple numeric variables in a grid of plots.

## Day 5
### Healthcare and Banking Integrated Data Analysis
1. **Data Import and Merging**: Imported and merged three healthcare datasets based on patient biomechanics and two banking datasets using the 'ID' attribute.
2. **Data Cleaning**: Identified and corrected inconsistent class labels, ensured correct data types, and addressed missing values by filling them with the mode.
3. **Outlier Detection**: Analyzed outliers in the healthcare dataset using IQR, removing significant outliers to create a refined dataset.
4. **Univariate Analysis**: Conducted distribution and box plot analyses for each numeric attribute, identifying normal and skewed distributions.
5. **Bivariate Analysis**: Generated correlation maps and pair plots to explore relationships between variables, noting key correlations among attributes.
6. **Class Imbalance**: Detected class imbalance in both original and outlier-removed healthcare datasets, impacting model training considerations.

## Day 6
### Telecom Customer Churn Data Analysis: Steps and Insights
1. **Data Import and Merging**: Loaded two telecom customer churn datasets, combined them horizontally and examined the dataset's structure.
2. **Data Cleansing**: Replaced empty values with NaN, identified and handled missing values, and dropped irrelevant columns (e.g., `customerID`).
3. **Statistical Analysis**: Conducted statistical analysis, focusing on the continuous variables (`tenure`, `MonthlyCharges`, `TotalCharges`) and observed their distributions.
4. **Categorical Analysis**: Analyzed categorical variables and their impact on customer churn, converting categorical data to continuous via encoding techniques.
5. **Correlation Analysis**: Created a heatmap to visualize correlations between variables, identifying strong relationships like between `tenure` and `TotalCharges`.
6. **Visualization**: Used pie charts, stacked bar charts, and box plots to illustrate data distributions and relationships, particularly between contract types and churn rates.

## Day 7
### Basic Probability Theory
1. **Experiment and Sample Space**: Probability theory involves experiments with a set of potential outcomes, known as the sample space.
2. **Event Definition**: An event is a subset of the sample space, representing specific outcomes we're interested in.
3. **Probability as Relative Frequency**: Probability can be estimated by the ratio of the number of times an event occurs to the total number of trials.
4. **Theoretical Probability**: If all outcomes are equally likely, the probability of an event is the number of favorable outcomes divided by the total number of outcomes.
5. **Axioms of Probability**: These include non-negativity, the total probability of the sample space being 1, and the additivity of mutually exclusive events.
6. **Joint and Conditional Probability**: Joint probability considers the likelihood of two events occurring together, while conditional probability focuses on the probability of one event given that another has occurred.
7. **Independence**: Two events are independent if the occurrence of one does not affect the probability of the other.
8. **Bayes Theorem**: This theorem allows the computation of conditional probabilities by relating the probability of events and their conditional probabilities.

## Day 8
### Statistical Analysis and Visualization of Probabilistic Distributions
1. **Binomial Distribution Analysis**: Using the `scipy.stats` library, we analyze the probability of picking a certain number of 'setosa' flowers from a sample of the Iris dataset, evaluating exact and cumulative probabilities.
2. **Probability Calculations**: We calculate probabilities such as picking exactly 2 setosa flowers out of 8, picking 2 or fewer, and more than 4, and visualize these probabilities using PMF and CDF plots.
3. **Poisson Distribution Analysis**: We analyze the number of tips received per day from the tips dataset, calculating probabilities like observing exactly 50 tips in a day and more than 15 tips using the Poisson distribution.
4. **Probability Calculations**: We calculate and visualize the probability of observing a specific range of tips using PMF and CDF plots, showing how tips are distributed over days.
5. **Normal Distribution Analysis**: We examine the 'total_bill' from the tips dataset, calculate probabilities related to specific bill amounts, and create PDF and CDF plots to visualize the distribution.
6. **Probability Calculations**: We compute the likelihood of a bill being within certain ranges, such as exactly $20 or between $15 and $25, and display these probabilities along with visual representations of the normal distribution.
7. **Summary of Findings**: The results provide insights into various probabilistic scenarios using binomial, Poisson, and normal distributions, offering a comprehensive view of how different datasets behave statistically.

## Day 9
### Central Limit Theorem Applied to Simulated Math Exam Scores
1. **Data Generation:** We simulate math exam scores using a truncated normal distribution to represent two groups: lazy students with a mean score of 30 and hardworking students with a mean score of 75, generating a combined dataset.
2. **Population Distribution:** A histogram of the combined dataset shows the distribution of grades, reflecting the two distinct groups with means of 30 and 75, resulting in an overall mean of approximately 57.24 and a standard deviation of 24.55.
3. **Sample Selection:** A sample of 100 students is taken from the dataset, and its mean score is calculated. This sample mean provides an estimate of the population mean.
4. **Multiple Samples:** Five additional samples of 100 students each are taken to observe variability in sample means, illustrating how different samples can yield different means.
5. **Central Limit Theorem:** With a large enough sample size, the distribution of sample means it approximates a normal distribution, regardless of the original population distribution. The mean of these sample means should be close to the population mean, and the standard deviation should be the population standard deviation divided by the square root of the sample size.
6. **Large Sample Simulation:** We draw 10,000 samples of size 100 each and compute their means. The distribution of these sample means is visualized and shows a normal distribution.
7. **Mean and Standard Deviation of Sample Means:** The mean of the sample means is close to the population mean, and the standard deviation of the sample means matches the expected standard deviation (population standard deviation divided by the square root of the sample size), validating the Central Limit Theorem.

## Day 10
### Medical Cost Prediction
1. **Data Exploration:** Analyzed a medical cost dataset with 1338 entries, detailing attributes like age, gender, BMI, children, smoking status, region, and insurance charges.
2. **Data Preparation:** Dropped irrelevant columns, encoded categorical data, and normalized numerical data for better model performance.
3. **Building Models:** Implemented Multiple Linear Regression and Polynomial Regression models using Scikit-Learn.
4. **Model Evaluation:** Used R Squared Score and RMSE to evaluate model performance on both training and testing datasets.
5. **Results:** Compare the accuracy and errors of both models to determine which was more effective in predicting insurance charges.
6. **Visualization:** Utilized heatmaps, histograms, and scatter plots to visualize data correlations and distributions.

## Day 11
### Medical Cost Prediction (cont)
1. **Data Loading and Exploration**: The dataset is loaded into a DataFrame, and its structure, including data types and summary statistics, is explored to understand its composition.
2. **Data Cleaning**: Missing values are identified and handled appropriately. Columns with a high percentage of missing data are dropped, and the remaining missing values are imputed using mean or mode values, depending on the nature of the data.
3. **Data Distribution and Outlier Analysis**: The distribution of features is visualized using histograms, and outliers are analyzed using box plots to identify any extreme values that might affect model performance.
4. **Multicollinearity Check**: Correlation analysis is conducted to identify multicollinearity between features, ensuring that highly correlated features do not negatively impact the model.
5. **Data Splitting**: The dataset is split into training and testing sets, with 80% used for training and 20% for testing, to evaluate model performance on unseen data.
6. **Model Building and Training**: A Logistic Regression model is built and trained on the scaled training data, utilizing MinMaxScaler for feature scaling to improve model accuracy.
7. **Model Evaluation**: The model's performance is evaluated using accuracy scores, confusion matrices, and classification reports, highlighting the effectiveness of the model on both training and testing datasets.


## Day 12
### Breast Cancer Prediction
1. **Import Libraries**: Imported essential libraries like numpy, pandas, matplotlib.pyplot, and seaborn for data processing and visualization.
2. **Suppress Warnings**: Used warnings.filterwarnings('ignore') to suppress warnings for a cleaner output.
3. **Mount Google Drive**: Mounted Google Drive to access the dataset stored in it.
4. **Load Dataset**: Loaded the dataset using pd.read_csv and displayed the first few rows with df.head().
5. **Dataset Dimensions**: Checked the dimensions of the dataset using df.shape, revealing 699 instances and 11 attributes.
6. **Column Renaming**: Renamed columns for better readability and understanding.
7. **Drop Redundant Columns**: Dropped the ‘Id’ column as it was redundant and did not contribute to predictive power.
8. **Dataset Summary**: Used df.info() to get a summary of the dataset, confirming the removal of the ‘Id’ column.
9. **Data Type Conversion**: Converted the ‘Bare_Nuclei’ column from object to integer type using pd.to_numeric.
10. **Missing Values**: Checked for missing values in the dataset using df.isnull().sum() and df.isna().sum(), identifying 16 missing values in the ‘Bare_Nuclei’ column.
11. **Frequency Distribution**: Analyzed the frequency distribution of values in the ‘Bare_Nuclei’ column to understand its data better.


## Capstone Project I
### Comprehensive Analysis of Anthropometric Data: Statistical Insights and Correlation Study
1. **Import Libraries**: Essential libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`) are imported.
2. **Load Data**: Male and female datasets are loaded from Excel files (simulated here with random data).
3. **Histograms**: Histograms are plotted for male and female weights to visualize their distributions.
4. **Box-and-Whisker Plot**: A box plot is created to compare the weight distributions of males and females.
5. **Statistical Aggregates**: Basic statistics (mean, median, standard deviation, variance, skewness, kurtosis) are calculated for male and female weights.
6. **Add BMI Column**: BMI is computed for females using their weights and heights and added as a new column to the dataset.
7. **Standardization**: Female data is standardized (z-scores) for uniform scaling.
8. **Scatterplot Matrix**: To explore pairwise relationships, a scatterplot matrix is generated for selected standardized female attributes.
9. **Correlation Analysis**: Pearson's and Spearman's correlation coefficients are calculated for standardized female data to evaluate relationships between variables.
10. **Waist-to-Ratio Calculations**: Waist-to-height and waist-to-hip ratios are computed for males and females.
11. **Ratio Boxplots**: Boxplots for the computed ratios are drawn to compare distributions across groups.
12. **Advantages and Disadvantages of Ratios**: Strengths and weaknesses of BMI, waist-to-height ratio, and waist-to-hip ratio are outlined.
13. **Standardized BMI Extremes**: Standardized measurements for the 5 individuals with the lowest and highest BMIs in the female dataset are identified and printed.



