# Course Syllabus and Learning Outcome 

## Course Learning Outcomes 

1. Define tidy data and explain why it is an optimal format for data analysis.
1. Transform data into the tidy data format using pandas.
1. Demonstrate fundamental programming concepts such as loops and conditionals.
1. Understand the key data structures in Python.
1. Read data into Python data from vanilla (e.g., .csv) and non-standard plain text files, as well as common spreadsheet file types (e.g., .xls).
1. Construct simple plots using pandas.
1. Manipulate a single data table by:   
    7.1 Filtering rows based on a criterion or combination of criteria.   
    7.2 Selecting variables.   
    7.3 Creating new variables and modifying pre-existing ones.   
    7.4 Rearranging the observations or variables by sorting.   
1. Manage and manipulate data with dates and times, missing values and categorical variables as well as renaming dataframe columns.
1. Use the split-apply-combine approach to iterate over and summarize data by groups.
1. Produce human-readable code that incorporates best practices of programming and coding style.


## Modules 

### Module 1: Python & Pandas - an unexpected friendship!

#### Topics 

- Understanding Dataframes 
- Reading in packages, libraries/modules
- Simple table manipulations (selecting) using Pandas
- Saving Dataframes as variables
- Indexing a dataframe using `.iloc[]` and `.loc[]`
- pandas plotting to make a scatter plot
- Obtain simple summary statistics of a dataframe 
- Writing data and saving plots 
- _(In the assignment introduce Jupyter notebooks)_

#### Learning Outcomes 
By the end of the module, students are expected to:
- Describe the components of a Dataframe.
- Read a standard `.csv` file using Pandas `pd.read_csv()`.
- Explain modules and import libraries.
- Demonstrate indexing and slicing with `df.loc[]` and `df.iloc[]`.
- Demonstrate Selecting columns of a dataframe using `df[]` notation.
- Create simple summary statistics using `pd.describe()`.
- construct simple visualizations using pandas.
- create a `.csv` file from a dataframe using `df.to_csv()`.



### Module 2: Not So Scary Wrangling (Table Manipulation and Chaining)

#### Topics 

- Read different  files using Pandas `pd.read_csv()` and other functions
- Simple dataframe manipulations and operations
- filtering using `df[]`
- Chaining 
- `df.grouby()` and `df.agg()` 
- Modify values in a dataframe using `df.apply()` and `df.applymap()`



#### Learning Outcomes 

By the end of the module, students are expected to:

- Demonstrate how to rename columns of a dataframe using [`df.rename()`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rename.html).
- Create new or columns in a dataframe using [`df.assign`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.assign.html) notation.
- Drop columns in a dataframe using [`df.drop`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop.html)
- Use `df[]` notation to filter rows of a dataframe.
- Perform aggregating methods on grouped objects using [`groupby`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html) and [`df.agg()`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.agg.html).
- Explain when chaining is appropriate.
- Compare and contrast functions and methods.
- Demonstrate chaining over multiple lines and methods.
- _Use pandas to modify values in a dataframe using `df.apply()` and `df.applymap()`._


### Module 3: It's Tidy up Time! (Tidy Data)

#### Topics 

- Tidy data - what is it?
- Manipulating data using `df.melt()` and `df.pivot()`
- Dataframe stacking and unstacking 
- Combining dataframes 


#### Learning Outcomes 
By the end of the module, students are expected to:

- Explain what tidy data is.
- Use `df.melt() `and `df.pivot() `to reshape dataframes, specifically to make tidy data.
- Use stacking and unstacking operations to reshape a dataframe.
- Combine dataframes using `df.merge()` and `pd.concat()` and know when to use these different methods.
- Understand the different joining methods. 


### Module 4: Python without the "eek": Basic Python 

#### Topics 

- Basic datatypes - within a dataframe? 
- Lists and tuples
- String methods
- Dictionaries how to convert them to a dataframe? 

#### Learning Outcomes 

By the end of the module, students are expected to:

- Compare and contrast python's key data types.
- Compare and contrast python's key data structures. 
- Use python to determine the type and structure of an object.
- Demonstrate how to create data structures and convert them to another.
- Describe what python packages/libraries are, as well as explain when and why they are useful.


### Module 5: Loops and Conditions 

#### Topics 

- Dry
- Loops 
- Loops to read in data 
- Nested loops 
- Conditions in loops 
- Intro to functions 


#### Learning Outcomes 

By the end of the module, students are expected to:
- Explain the DRY principle and how it can be useful.
- Write conditional statements with if, elif and else to run different code, depending on the input.
- Write for loops to repeatedly run code.
- Describe the expected outcome of code with nested loops .
- Define and use a named function that accepts parameters and returns values.

### Module 6:  Functions

#### Topics

- Functions example in plotting, add data to a dataframe?
- Keyword arguments (default)
- Docstrings 
- Unit testing 

#### Learning Outcomes 

- Evaluate the readability, complexity and performance of a function.
- Write Docstrings for functions following the NumPy/SciPy format.
- Write comments within a function to improve readability.
- Write and design functions with default arguments.
- Explain the importance of scoping and environments in Python as they relate to functions.
- Formulate test cases to prove a function design specification.
- Use `assert` statements to formulate a test case to prove a function design specification.
- Use test-driven development principles to define a function that accepts parameters, returns values and passes all tests.
- Handle errors gracefully via exception handling.


### Module 7: Importing Files and the Coding Style Guide

#### Topics 
- Importing your created functions from a different file
- `pytest`
- Style guides and coding style - black
- Python debugger (PDB) (video in notebook instead with MC question) 

#### Learning Outcomes 

By the end of the module, students are expected to:

- Describe what python libraries are, as well as explain when and why they are useful.
- Identify where code can be improved concerning variable names, magic numbers, comments and whitespace.
- Write code that is human readable and follows the black style guide.
- Import files from other directories.
- Use `pytest` to check a function's tests.
- When running `pytest`, explain how pytest find the associated test functions.
- Explain how the python debugger can help rectify your code.


### Module 8: Numpy, and Advanced Data Wrangling 

#### Topics 

- (Perhaps - - NumPy arrays, pandas relationship explained from old Module 6) 
- Working with DateTime format 
- Working with strings in dataframes?
- Identifying and handling missing/erroneous values 
- Pandas profiling 


#### Learning Outcomes 

By the end of the module, students are expected to:

- Manipulate non-standard date/time formats into standard Pandas datetime using `pd.to_datetime()`.
- Find, replace and extract text from a dataframe using verbs such as `.replace()`. 
- Identify missing and erroneous values in a dataframe and manage them by removing them using `.dropna()` or replacing them using `.fillna()`.
- Use NumPy to create ndarrays with `np.array()` and from functions such as `np.arrange()`, `np.linspace()` and `np.full()`
- Describe resulting array shapes from operations 
- Convert between a NumPy ndarray to a Pandas Dataframe.
- Extract information from the Pandas profiling package. 

## APPENDIX: 

### OLD MODULE 6: A Slice of NumPy (NumPy Arrays)

#### Topics 

- NumPy arrays
- NumPy array dimensions
- NumPy indexing and slicing
- Explain broadcasting
- Compare arrays with Pandas series and dataframes
- Compare arrays with Pandas series and dataframes

#### Learning Outcomes 

By the end of the module, students are expected to:

- Explain what broadcasting is and how to use it  (Mikes L3+ Tom's L1 _Mike asks do we need it?_)
- Use NumPy to create ndarrays from existing data with `np.array()` and from functions such as `np.arrange()`, `np.linspace()` and `np.full()`
- Describe resulting array shapes from operations  
- Access values from a NumPy ndarray by indexing and slicing.
- Compare and contrast np.ndarray, pd.Series and pd.DataFrame objects in Python.
- Convert between a NumPy ndarray, Pandas Series, & Pandas Dataframe.
