Telco_Project

Load the Telecom dataset:
   - Start by loading the dataset into a pandas DataFrame.
   - Check the structure of the dataset, including variable names and data types.

Task 1.1: Aggregate user behavior information:
   - Group the data by user and calculate the following metrics: number of xDR sessions, session duration, total download and upload data, and total data volume for each application.
   - Create a new DataFrame with the aggregated information.

Task 1.2: Exploratory data analysis:
   - Handle missing values:
     - Identify missing values in the dataset and replace them with the mean of the corresponding column using the `fillna()` function.
   - Analyze basic metrics:
     - Calculate descriptive statistics (mean, median, etc.) for relevant variables to understand the dataset's central tendencies and variations.
   - Non-Graphical Univariate Analysis:
     - Compute dispersion parameters (e.g., standard deviation, range) for each quantitative variable to understand the spread of the data.
     - Interpret the dispersion parameters to gain insights into the dataset's distribution and variability.
   - Graphical Univariate Analysis:
     - Choose appropriate plotting options (e.g., histograms, box plots) for each variable to visualize their distributions.
     - Interpret the graphical representations to understand the data's distribution, skewness, and presence of outliers.
   - Bivariate Analysis:
     - Explore the relationship between each application and the total download and upload data using scatter plots or correlation matrices.
     - Interpret the findings to understand the impact of different applications on data usage.
   - Variable Transformations:
     - Segment users into the top five decile classes based on the total duration for all sessions.
     - Compute the total data (DL+UL) per decile class and analyze the distribution of data usage across these segments.
   - Correlation Analysis:
     - Compute a correlation matrix for the variables: Social Media data, Google data, Email data, Youtube data, Netflix data, Gaming data, and Other data.
     - Interpret the correlation matrix to identify relationships and dependencies between variables.
   - Dimensionality Reduction:
     - Perform Principal Component Analysis (PCA) to reduce the dimensions of the data.
     - Interpret the results by identifying the most influential components and understanding their contribution to the overall variance.
