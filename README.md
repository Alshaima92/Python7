## Summary: Data Analysis

Python is versatile and arguably the most full-featured language in use for data analysis. This lecture covers using Python for data analysis with a focus on the pandas library.

### Introduction to pandas

pandas is an open-source library based on the Python programming language, developed for data analysis and manipulation. It's known for being fast, powerful, and user-friendly, with flexible data structures.

### pandas Data Structures

- **Series**: A one-dimensional, labeled array capable of holding any data type.
- **DataFrame**: A two-dimensional labeled data structure with columns of potentially mixed types.

### Creating Series and DataFrames

You can have Series and DataFrames created from some major data structures in Python like lists, dictionaries, NumPy arrays, and lists. For instance, DataFrames can be constructed by using dictionaries, lists of dictionaries, lists of lists, or strings in JSON format.

### Accessing and Editing Data

• Series and DataFrame both allow label-based access.
• The .loc indexer [] and the .iloc indexer [] are used respectively for label-based and integer-based methodologies for getting or setting values and arrays of values in Series and DataFrame objects.

### Scalar Operations
These are operations involving only one value. pandas is able to do a number of operations directly on its Series and DataFrame objects, such as addition, subtraction, multiplication, division, modulus, exponentiation, root, etc.

### Loading and Saving Data

It reads data from a number of file formats like CSV, Excel, JSON, etc. into DataFrames. In turn, it also supports writing DataFrames again as files in these formats.

### Exploring Data

 **`head()`**: Provides the first few rows of your data.
 **`info()`**: Specifies information on intersection of columns possibly containing mixed type, and non-null values counts of columns in DataFrame.
 **`describe()`**: It generates summary statistics of various dimensions and data type of variables in specified columns of your data.

### Cleaning Data

Panda provides data cleaning features such as handling missing data, removing duplicates, and renaming columns for integrity. It also enables the following:

- Selection of certain columns from a DataFrame
- Filtering rows based on specified conditions or logical operators.

### Grouping and Aggregation

pandas allows to group data by one or more columns and then apply aggregation operation like sum, mean etc on the grouped data.

### Working with Categorical Data

- Mapping of object data types to categorical
- Encoding of categorical data into numeric codes

### Calculating Correlations

pandas is capable of computing correlations between columns in a DataFrame. This is done with the intention of showing relationships between variables.

### Visualization with Seaborn

While having built-in simple plotting capabilities, pandas can work very seamlessly with Matplotlib and Seaborn for higher-end visualizations. Seaborn is based on Matplotlib and makes easy, in a Python way, really nice and informative statistical graphics: scatter plots, heatmaps, and a lot of other associated plots.



https://www.geeksforgeeks.org/data-analysis-with-python/

https://realpython.com/python-for-data-analysis/

https://learnpython.com/blog/python-data-analysis-example-guide-for-beginners/

https://www.simplilearn.com/tutorials/data-analytics-tutorial/data-analytics-with-python
