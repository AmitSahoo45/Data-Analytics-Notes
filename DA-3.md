# Data Analytics 3

#### P.S - This contains only the part which is difficult to memorize and not in ppt.

### 1. Data Exploration - 
- Data exploration refers to the initial step in data analysis in which data analysts use data visualization and statistical techniques to describe dataset characterizations, such as size, quantity, and accuracy, in order to better understand the nature of the data.
- Raw data is typically reviewed with a combination of manual workflows and automated data-exploration techniques to visually explore data sets, look for similarities, patterns and outliers and to identify the relationships between different variables.
- This is also sometimes referred to as exploratory data analysis, which is a statistical technique employed to analyze raw data sets in search of their broad characteristics.

- Data exploration is the process of **examining and analyzing** *large datasets* to **identify patterns, trends, and relationships between variables**. It *involves using statistical and visual techniques* to <u>understand the structure and content of the data, and to uncover insights and key features that may be hidden in the data.</u>     

- Data exploration is an important step in data analysis because it helps to identify potential problems and limitations in the data, as well as opportunities for further analysis. It allows analysts to develop a deeper understanding of the data and to form hypotheses about the relationships between variables.

- Some common techniques used in data exploration include visualizations such as scatter plots, histograms, and box plots, as well as statistical measures such as correlation coefficients and summary statistics. By using these techniques, analysts can identify outliers, missing values, and other anomalies in the data, and can make informed decisions about how to proceed with further analysis

- [unread]

### 2. Why is Data Exploration Important?
- Starting with data exploration helps users to make better decisions on where to dig deeper into the data and to take a broad understanding of the business when asking more detailed questions later.
- Performing the initial step of data exploration enables data analysts to better understand and visually identify anomalies and relationships that might otherwise go undetected.
- Data exploration tools include data visualization software and business intelligence platforms, such as Microsoft Power BI, Qlik and Tableau
- [unread]

### 3. Population and sampling
- **all instances of a random variable** is called as observation of that variable.
- **population** is the set of all observations of a random variable.
- **sample** is a subset of the population.
- **sampling distribution** is the distribution of the sample mean.
- **sampling error** is the difference between the sample mean and the population mean.
- **sampling bias** is the difference between the sample mean and the population mean.
- <font color="red"><u>**Population :**</u></font>
    - In data analytics, a population refers to the entire group of **individuals, objects, or events** that share a common characteristic or property of interest. This characteristic could be anything from age, gender, income, education level, or any other variable that is relevant to the analysis being conducted.
- <font color="red"><u>**Sampling :**</u></font>
    - The sample so selected should be such that it represent the population in all its characteristics, and it should be free from bias, so as to produce miniature cross-section, as the sample observations are used to make generalisations about the population.

### 4. Sampling Methods
- **Simple Random Sampling (SRS)**
    - In simple random sampling, each member of the population has an equal chance of being selected.
    - The sample is selected randomly from the population.
    - The sample is representative of the population.
    - The sample is unbiased.
    - The sample is independent.
    - The sample is random.
    - The sample is large.
    - The sample is homogeneous.
    - The sample is simple.
    - In this method, each member of the population has an equal chance of being selected. A random number generator is often used to select the sample. For example, a researcher may use simple random sampling to select 100 students from a population of 1000 students at a university.
    - Easy to implement and understand
    - Free from bias
    - Representative of the population
    - Enables statistical inferences

- **Stratified Random Sampling**
    - Stratified Sampling: In this method, the population is divided into subgroups or strata based on a specific characteristic such as age, gender, or income level. A sample is then randomly selected from each stratum in proportion to its size in the population. For example, a researcher may use stratified sampling to select 100 students from a population of 1000 students at a university, with 50 students from each of two strata (undergraduate and graduate).
    - Ensures representation of all subgroups in the population
    - Enables comparisons between subgroups
    - Reduces sampling variability within strata
    - More efficient than simple random sampling for large populations with clear subgroups

- **Cluster Sampling**
    - In this method, the population is divided into clusters or groups, and a random sample of clusters is selected. All members within each selected cluster are then included in the sample. For example, a researcher may use cluster sampling to select a sample of 100 households from a city by randomly selecting 10 city blocks, and then selecting all households within those blocks.
    - More efficient than simple random sampling for large and widely dispersed populations
    - Enables geographical comparisons
    - Reduces sampling variability within clusters
    - Cost-effective for large and diverse populations

- **Convience Sampling**
    -  In this method, the sample is selected based on convenience or accessibility, rather than randomization or representativeness. For example, a researcher may use convenience sampling to survey people in a shopping mall about their shopping habits.
    - Quick and easy to implement
    - Cost-effective for small sample sizes
    - Useful for exploratory studies or preliminary data collection
    - May be appropriate for certain research questions

- [All 4 Unread So Far]

### 5. Data sets - 
- A **data set** is usually a representation of the population in the form of a rectangular array of data, with *variables in columns* and *observations in rows*.

## P.S - For variables, we can also use <font color='red'>**(or attributes, dimensions, features)**</font>

### 7. Types of Variables - 
- **Categorical** -
    - Offers _qualitative **information**_ about the data.
    - refers to a characteristic that can't be quantifiable
    - **Nominal** - 
        - nominal means "relating to names."
        - The values of a nominal attribute are *symbols or names of things*
    - **Ordinal** - 
        - Values have *a meaningful order (ranking) but magnitude between successive values is not known*.
    - **Binary** - 
        - Nominal attribute with only **2 states** (0 and 1), where 0 typically means that the attribute is absent, and 1 means that it is present. Binary attributes are referred to as Boolean if the two states correspond to true and false. 
        - Symmetric binary: both outcomes equally important, e.g., gender
        - Asymmetric binary: outcomes not equally important, e.g., medical test (positive vs. negative) Convention: assign 1 to most important outcome (e.g., HIV positive)
- **Numeric** -
    - Offers _quantitative **information**_ about the data.
    - meaningful arithmetic can be performed. 

### 6. Some important terms -
- **dummy variable** - This 0−1 coding for a categorical variable is very common. Such a variable is called a dummy variable, it often simplies the analysis. A dummy variable is a 0−1 coded variable for a specific category. It is coded as 1 for all observations in that category and 0 for all observations not in that category.
- **Binned Variable** - A binned (or discretized) variable corresponds to a numerical variable that has been categorized into discrete categories. These categories are usually called bins. The Age variable has been categorized as “young” (34 years or younger),  “middle-aged” (from 35 to 59 years), and “elderly” (60 years or older).

- Continuous variables: Continuous variables are variables that can take on any value within a certain range or interval. They are often measured on a scale, such as weight or height, and can have decimal or fractional values. Examples of continuous variables include:
Age
Height
Temperature
Blood pressure
Weight
Time
- Discrete variables: Discrete variables are variables that can only take on specific values, usually whole numbers. They are often counts or frequencies, such as the number of people in a household or the number of cars sold in a month. Examples of discrete variables include:
Number of children in a family,
Number of pets,
Number of employees in a company, 
Number of students in a class, 
Number of defects in a product, 

- A trimmed mean (sometimes called a truncated mean) is similar to a mean, but it trims any outliers. Outliers can affect the mean (especially if there are just one or two very large values), so a trimmed mean can often be a better fit for data sets with erratic high or low values or for extremely skewed distributions. Even a small number of extreme values can corrupt the mean. For example, the mean salary at a company may be substantially pushed up by that of a few highly paid managers. Similarly, the mean score of a class in an exam could be pulled down quite a bit by a few very low scores.

- The advantage of using frequency distributions is that they present raw data in an organized, easy-to-read format. The most frequently occurring scores are easily identified, as are score ranges, lower and upper limits, cases that are not common, outliers, and total number of observations between any given scores.

- Advantage of relative frequency: Within the overall number of observations, a relative frequency reflects how frequently a given type of event occurs within that total number of observations.

- Cumulative frequency represents the sum of the relative frequencies. Cumulative frequency is used to determine the number of observations that lie above (or below) a particular value in a data set.

- Measurement of central tendency is a statistical concept that refers to the way in which a set of data tends to cluster around a central or typical value. It provides a way to summarize the distribution of a set of data by identifying the most representative value.

- Measures of variability, also known as measures of dispersion, are statistical concepts that describe how spread out or dispersed a set of data is. They provide a way to summarize the degree of variation or diversity within a set of data. 

- An outlier is an extreme value or an entire observation (row) that lies well outside of the norm. Even if values are not unusual by themselves, there still might be unusual combinations of values.

- There are three types of outliers
    * Global Outliers: The data point or points **whose values are <font color='yellow'>far outside everything else in the dataset</font>** are global outliers. Eg. Suppose we look at a taxi service company’s number of rides every day. The rides suddenly dropped to zero due to the pandemic-induced lockdown. This sudden decrease in the number is a global outlier for the taxi company.
    * Contextual Outliers: Contextual outliers are those values of data points **<u color='red'>that deviate quite a lot from the rest
of the data points</u> that are in the same context, however, in a different context, it may not be an outlier at all.** For
example, a sudden surge in orders for an e-commerce site at night can be a contextual outlier.
    * Collective Outliers: **Some data points <font color='pink'>collectively as a whole deviates from the dataset. These data points
individually may not be a global or contextual outlier, <u>but they behave as outliers when aggregated together.</u></font>** For
example, closing all shops in a neighborhood is a collective outlier as individual shops keep on opening and closing,
but all shops together never close down; hence, this scenario will be considered a collective outlier.

- Boxplot Analysis - visualizing data through quantiles and detecting outliers. A boxplot consist of 5 number summary and a box. The 5 number summary consists of the minimum, first quartile, median, third quartile, and maximum. The box is drawn between the first and third quartile. The whiskers are drawn from the box to the minimum and maximum. The outliers are drawn as points outside the whiskers.
    * Data is represented with a box
    * The ends of the box are at the first and third quartiles, i.e., the height of the box is IQR. IQR(Interquartile Range) is the basic mathematics behind boxplots.
    * The median is marked by a line within the box
    * Two lines (called whiskers) outside the box extend to the smallest (Minimum) and largest (Maximum) observations. The top and bottom whiskers can be understood as the boundaries of data, and any data lying outside it will be an outlier.
    * **Outliers**: points beyond a specified outlier threshold, plotted individually 

- Skewness 
    - Skewness refers to the degree of symmetry, or more precisely, **the degree of lack of symmetry**.
    - Skewness is used to **measure the level of asymmetry in our graph**.
    - It is the **measure of asymmetry that occurs when our data deviates from the norm**.
    - Positive Skewness: When the tail on the right side of the distribution is longer or fatter, the distribution is said to be positively skewed. It is also called **right-skewed or right-tailed distribution**. The values are more concentrated towards the right side and *the left tail is spread out*. The value of mean, median and mode is always positive.
    - Negative Skewness: When the tail on the left side of the distribution is longer or fatter, the distribution is said to be negatively skewed. It is also called **left-skewed or left-tailed distribution**. The values are more concentrated towards the left side and *the right tail is spread out*. The value of mean, median and mode is always negative.
    - [reread it once again]

- Kurtosis
    - Kurtosis gives a measure of flatness of distribution
    - Kurtosis is the measure of **whether the data are heavy-tailed or light-tailed relative to a normal distribution**.
    - Kurtosis is associated with the "*movement of probability mass from the shoulders of a distribution into its center and tails.*"
    - The normal curve is called *“Mesokurtic*.”
    - The curves with greater peakedness than the normal curve are called *“Leptokurtic”*.
    - The curves which are more flat than the normal curve are called *“Platykurtic”*.
    - used to find the presence of outliers in data. It gives us the total degree of outliers present.

Theory left - 
- crosstabs and contingency table
- Chi Square Test

- Finding Relationships among variables
    - Scatterplot
    - Correlation
    - Covariance
    - Pearson's Correlation Coefficient
    - Spearman's Rank Correlation Coefficient
    - Kendall's Rank Correlation Coefficient


- Numericals -
1. Trimmed mean, Mean, Median, Mode
2. Ouliers - Tukey's method, IQR, Z-score
3. Pearsons Coefficient of Skewness
4. Kurtosis
5. Chi Square Test


Midnight - After 1 AM
1. Kurtosis.
2. Measures of Variability
3. Descriptive measures for categorical variables
4. EDA.
5. Sampling
