# Corizo Data Science Apprenticeship

## Day 1
1. **Data Science Introduction:** It outlines data collection, cleaning, analysis, and deployment of models to extract insights.
2. **Python Basics:** Covers variables, arithmetic operations, strings, data types (integers, floats, strings, lists, tuples, dictionaries, boolean), and basic operations with these types.
3. **Lists and Dictionary Operations:** Details operations like indexing, slicing, appending, inserting, removing, and other manipulations with lists and dictionaries.
4. **Conditional Statements, Loops, and Functions:** Introduces conditional statements (if, Elif, else), loops (for, while), and functions, demonstrating their use in decision-making, iteration, and creating reusable code blocks.

## Day 2
1. **NumPy Arrays:** NumPy provides support for creating and manipulating multidimensional arrays, which are more efficient for numerical computations than Python lists.
2. **Array Operations:** With NumPy, you can perform element-wise operations, broadcasting, and matrix multiplication, which streamline mathematical calculations.
3. **Pandas DataFrames:** Pandas introduces DataFrames, a tabular data structure with labeled axes, which simplifies data manipulation and analysis.
4. **Data Handling in Pandas:** Pandas offers powerful tools for data cleaning, filtering, and aggregation, making it ideal for working with structured data.

## Day 3
1. **Data Loading and Cleaning:** The script starts by mounting Google Drive to access the dataset. It loads the Forbes Billionaire data into a Pandas DataFrame, checks the dataset's structure by viewing its shape, and performs initial exploration to ensure the data is ready for further analysis.
2. **Data Manipulation:** The script utilizes Pandas functions such as `groupby()` to aggregate data, `value_counts()` to count occurrences of industries, and `mean()` to calculate average values like net worth and age. These operations help summarize and extract key insights from the dataset.
3. **Filtering and Sorting:** The script selects specific subsets of data by applying conditions, such as filtering billionaires by industry or country. It then sorts these subsets based on criteria like net worth or age, enabling the identification of top industries, countries, and individuals within the dataset.
4. **Statistical Analysis:** The script computes descriptive statistics, including the mean net worth and age of billionaires, to analyze trends across different categories. It compares these statistics across industries and countries, providing insights into the wealth distribution and demographic profiles of billionaires.

## Day 4
Data visualization is the graphical representation of data using charts, graphs, and plots. It simplifies complex data, making it easier to identify patterns, trends, and outliers. Visualizations enhance data understanding and communication, aiding in better decision-making and storytelling with data.
1. **Histogram**: Visualizes the distribution of a continuous numerical variable by breaking it into equal intervals and counting observations in each.
2. **Kernel Density Estimation (KDE)**: Visualizes the distribution of data over a continuous interval, often overlaid on a histogram.
3. **Boxplot**: Shows distribution, skewness, and outliers in numerical data using a five-number summary (min, Q1, median, Q3, max).
4. **Bar Graph**: Displays counts of categorical variable groups using bars.
5. **Lineplot**: Connects data points with lines to display trends or patterns, often over time.
6. **Scatterplot**: Plots individual data points to visualize the relationship between two variables.
7. **Correlation**: Measures the association between two variables; positive, negative, or none.
8. **Lmplot**: Combines scatterplot with a linear regression model and confidence interval.
9. **Jointplot**: Visualizes the relationship between two variables and their individual distributions in a single plot.
10. **Violin Plot**: Combines boxplot with KDE, showing the distribution of a numeric variable for different groups.
11. **Strip Plot**: Displays individual data points differentiated by categories, useful for small datasets.
12. **Swarm Plot**: Similar to a strip plot but avoids overlapping points, showing data distribution more clearly.
13. **Catplot**: Flexible framework for plotting categorical data, supporting multiple plot types like strip, swarm, and boxplots.
14. **Pair Plot**: Displays pairwise relationships between multiple numeric variables in a grid of plots.
