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
