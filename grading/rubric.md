
[GitHub Repo](https://github.com/coding-boot-camp/DataViz-Lesson-Plans/tree/v1.2/04-Canvas)
### Module 1 - KS Excel
#### Conditional Formatting (10 points)
- [ ] Conditional formatting is applied appropriately to the outcome column (5 points)
- [ ] Conditional formatting is applied appropriately to the percent funded column (5 points)
#### Column Creation (10 points)
- Six new columns were correctly created for:
    - percent funded
    - average donation
    - category
    - sub-category
    - Date Created Conversion
    - Date Ended Conversion
#### Pivot Tables and Stacked Column Charts (15 points)
- [ ] Correctly created a pivot table that counts how many campaigns were "successful," "failed," "canceled," or are currently "live" per category (7.5 points)
- [x] Correctly created a stacked column pivot chart that can be filtered by country (7.5 points)
#### Pivot Tables and Line Graphs (15 points)
- [ ] Correctly created a pivot table with a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years (7.5 points)
- [ ] Correctly created a pivot chart line graph (7.5 points)
#### Written Report (20 points)
- Presents a cohesive written analysis that:
    - [ ] Draws three conclusions from the data (10 points)
    - [ ] States limitations of the dataset and suggestions for additional tables of graph (10 points)
#### Crowdfunding Goal Analysis (10 points)
- [ ] Computed calculations of percentages for projects that were successful, failed, or were canceled per goal range (5 points)
- [ ] Created a line chart showing the relationship between the goal’s amount and its chances at success, failure, or cancellation (5 points)
#### Statistical Analysis (20 points)
- [ ] Computed calculations of the mean, median, min, max, variance, and stdev using Excel formulas (15 points)
- [ ] A brief and compelling justification of whether the mean or median better summarizes the data (5 points)
### Module 2 - VBA Stocks
2018
![[Pasted image 20240205195325.png]]
2019
![[Pasted image 20240205195516.png]]
2020
![[Pasted image 20240205195534.png]]

#### Retrieval of Data (20 points)
- [ ] The script loops through one year of stock data and reads/ stores all of the following values from each row:
    - [ ] ticker symbol (5 points)
    - [ ] volume of stock (5 points)
    - [ ] open price (5 points)
    - [ ] close price (5 points)
#### Column Creation (10 points)
- [ ] On the same worksheet as the raw data, or on a new worksheet all columns were correctly created for:
    - [ ] ticker symbol (2.5 points)
    - [ ] total stock volume (2.5 points)
    - [ ] yearly change ($) (2.5 points)
    - [ ] percent change (2.5 points)
#### Conditional Formatting (20 points)
- [ ] Conditional formatting is applied correctly and appropriately to the yearly change column (10 points)
- [ ] Conditional formatting is applied correctly and appropriately to the percent change column (10 points)
#### Calculated Values (15 points)
- [ ] All three of the following values are calculated correctly and displayed in the output:
    - [ ] Greatest % Increase (5 points)
    - [ ] Greatest % Decrease (5 points)
    - [ ] Greatest Total Volume (5 points)
#### Looping Across Worksheet (20 points)
- [ ] The VBA script can run on all sheets successfully.
#### GitHub/GitLab Submission (15 points)
- [ ] All three of the following are uploaded to GitHub/GitLab:
    - [ ] Screenshots of the results (5 points)
    - [ ] Separate VBA script files (5 points)
    - [ ] README file (5 points)
- [ ] 
### Module 3 - PyBank/PyPoll

Correctly Reads in the CSV (10 points)
- [ ] Reads in the CSVs for both PyBank and PyPoll using Python (5 points)
- [ ] Successfully stores the header row (5 points)
#### Results Printed out to correctly to terminal (40 points)
- Results correctly display for PyBank:
    - [ ] Total Months (5 points)
    - [ ] Total (5 points)
    - [ ] Average Change (5 points)
    - [ ] Greatest Increase (5 points)
    - [ ] Greatest Decrease (5 points)
- Results correctly display for PyPoll:
    - [ ] Total Votes (5 points)
    - [ ] Each candidate’s total votes and percent of votes (5 points)
    - [ ] Winner (5 points)
#### Code Runs Error Free (10 points)
- [ ] Error Free (5 points)
- [ ] Producing consistent results (5 points)
#### Exports results to text file (30 points)
- The text file contains for PyBank:
    - [ ] Total Months (2.5 points)
    - [ ] Total (2.5 points)
    - [ ] Average Change (5 points)
    - [ ] Greatest Increase (5 points)
    - [ ] Greatest Decrease (5 points)
- The text file contains for PyPoll:
    - [ ] Total Votes (2.5 points)
    - [ ] Each candidate’s total votes and percent of votes (2.5 points)
    - [ ] Winner (5 points)
#### Code is cleaned and commented (10 points)
- [ ] Has additional tests and debugging removed (5 points)
- [ ] Commented (5 points)
### Module 4 - PyCitySchools
[Link](https://github.com/coding-boot-camp/DataViz-Lesson-Plans/blob/v1.2/04-Canvas/04-Data-Analysis-Pandas/02-Application/02-challenge.md)
#### District Summary (20 points)
- [ ] Calculate the total number of unique schools (2 points)
- [ ] Calculate the total number of students (2 points)
- [ ] Calculate the total budget (2 points)
- [ ] Calculate the average (mean) math score (2 points)
- [ ] Calculate the average (mean) reading score (2 points)
- [ ] Use the code provided to calculate the percentage of students who passed math (2 points)
- [ ] Calculate the percentage of students who passed reading (2 points)
- [ ] Use the code provided to calculate the percentage of students that passed both math and reading (2 points)
- [ ] Create a new DataFrame for the above calculations called `district_summary` (4 points)
#### School Summary (20 points)
- [ ] Use the code provided to select the school type (2 points)
- [ ] Calculate the total student count (2 points)
- [ ] Use the code provided to calculate the per capita spending (2 points)
- [ ] Calculate the average test scores (2 points)
- [ ] Calculate the number of schools with math scores of 70 or higher (2 points)
- [ ] Calculate the number of schools with reading scores of 70 or higher (2 points)
- [ ] Use the provided code to calculate the schools that passed both math and reading with scores of 70 or higher (2 points)
- [ ] Use the provided code to calculate the passing rates (2 points)
- [ ] Create a new DataFrame for the above calculations called `per_school_summary` (4 points)
#### Highest-Performing Schools by Percentage of Overall Passing (5 points)
- [ ] Sort the schools by `% Overall Passing` in descending order (2 points)
- [ ] Save the results to a DataFrame called `top_schools` (2 points)
- [ ] Display the first 5 rows (1 point)
#### Lowest-Performing Schools by Percentage of Overall Passing (5 points)
- [ ] Sort the schools by `% Overall Passing` in ascending order (2 points)
- [ ] Save the results to a DataFrame called `bottom_schools` (2 points)
- [ ] Display the first 5 rows (1 point)
#### Math Scores by Grade (10 points)
- [ ] Use the code provided to separate the data by grade (1 points)
- [ ] Group by "school_name" and take the mean of each (4 points)
- [ ] Use the code to select only the `math_score` (1 points)
- [ ] Combine each of the scores above into single DataFrame called `math_scores_by_grade` (4 points)
#### Reading Scores by Grade (10 points)
- [ ] Use the code provided to separate the data by grade (1 points)
- [ ] Group by "school_name" and take the mean of each (4 points)
- [ ] Use the code to select only the `reading_score` (1 points)
- [ ] Combine each of the scores above into single DataFrame called `reading_scores_by_grade` (4 points)
#### Scores by School Spending (5 points)
- [ ] Use `pd.cut` with the provided code to bin the data by the spending ranges (2 points)
- [ ] Use the code provided to calculate the averages (1 points)
- [ ] Create the `spending_summary` DataFrame using the binned and averaged spending data (2 points)
#### Scores by School Size (5 points)
- [ ] Use `pd.cut` with the provided code to bin the data by the school sizes (2 points)
- [ ] Use the code provided to calculate the averages (1 points)
- [ ] Create the `size_summary` DataFrame using the binned and averaged size data (2 points)
##### Scores by School Type (5 points)
- [ ] Group the per_school_summary DataFrame by "School Type" and average the results (2 points)
- [ ] Use the code provided to select the new column data (1 point)
- [ ] Create a new DataFrame called `type_summary` that uses the new column data (2 points)
#### Written Report (15 points)
To receive all points, the written report presents a cohesive written analysis that:
- [ ] Summarizes the analysis (5 points)
- [ ] Draws two correct conclusions or comparisons from the calculations (10 points)
### Module 5 - Pymaceuticals
[Link](https://github.com/coding-boot-camp/DataViz-Lesson-Plans/blob/v1.2/04-Canvas/05-Data-Visualization/02-application/02-challenge.md)
#### Prepare the Data (20 points)

- [ ] The datasets are merged into a single DataFrame. (6 points)
- [ ] The number of mice are shown from the merged DataFrame. (2 points)
- [ ] Each duplicate mice is found based on the Mouse ID and Timepoint. (6 points)
- [ ] A clean DataFrame is created with the dropped duplicate mice. (4 points)
- [ ] The number of mice are shown from the clean DataFrame. (2 points)

#### Generate Summary Statistics (15 points)

- [ ] The mean of the tumor volume for each regimen is calculated using `groupby`. (2 points)
- [ ] The median of the tumor volume for each regimen is calculated using `groupby`. (2 points)
- [ ] The variance of the tumor volume for each regimen is calculated using `groupby`. (2 points)
- [ ] The standard deviation of the tumor volume for each regimen is calculated using `groupby`. (2 points)
- [ ] The SEM of the tumor volume for each regimen is calculated using `groupby`. (2 points)
- [ ] A new DataFrame is created with using the summary statistics. (5 points)

#### Create Bar Charts and Pie Charts (15 points)

- [ ] A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated. (4.5 points)
- [ ] A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated. (4.5 points)
- [ ] A pie plot showing the distribution of female versus male mice using Pandas is generated. (3 points)
- [ ] A pie plot showing the distribution of female versus male mice using pyplot is generated. (3 points)

#### Calculate Quartiles, Find Outliers, and Create a Box Plot (30 points)

- [ ] A DataFrame that has the last timepoint for each mouse ID is created using `groupby`. (5 points)
- [ ] The index of the DataFrame is reset. (2 points)
- [ ] Retrieve the maximum timepoint for each mouse. (2 points)
- [ ] The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list. (3 points)
- [ ] An empty list is created to fill with tumor volume data. (3 points)
- [ ] A `for` loop is used to display the interquartile range (IQR) and the outliers for each treatment group (10 points)
- [ ] A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. (5 points)

#### Create a Line Plot and a Scatter Plot (10 points)

- [ ] A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin. (5 points)
- [ ] A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen. (5 points)

#### Calculate Correlation and Regression (10 points)

- [ ] The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen. (10 points)

### Module 6 - WeatherPy/VacationPy
#### The requirements for "Part 1: WeatherPy" are the following
##### Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points)
- [ ] Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)
- [ ] Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)
- [ ] Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)
- [ ] Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)
- [ ] Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)
##### Compute Linear Regression for Each Relationship (40 points)
- [ ] Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)
- [ ] Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)
#### The requirements for "Part 2: VacationPy" are the following (30 points)
- [ ] Create a map that displays a point for every city in the `city_data_df` DataFrame (5 points)
- [ ] Narrow down the `city_data_df` DataFrame to find your ideal weather condition (5 points)
- [ ] For each city in the `hotel_df` DataFrame, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates (10 points)
- [ ] Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)
### Module 9 - EmployeeSQL
#### Data Modeling (10 points)
- [ ] Entity Relationship Diagram is included or table schemas provided for all tables (10 points)
#### Data Engineering (70 points)
- [ ] All required columns are defined for each table (10 points)
- [ ] Columns are set to the correct data type (10 points)
- [ ] Primary Keys set for each table (10 points)
- [ ] Correctly references related tables (10 points)
- [ ] Tables are correctly related using Foreign Keys (10 points)
- [ ] Correctly uses NOT NULL condition on necessary columns (10 points)
- [ ] Accurately defines value length for columns (10 points)
#### Data Analysis (20 points)
- [ ] List the employee number, last name, first name, sex, and salary of each employee (2 points)
- [ ] List the first name, last name, and hire date for the employees who were hired in 1986 (2 points)
- [ ] List the manager of each department along with their department number, department name, employee number, last name, and first name (2 points)
- [ ] List the department number for each employee along with that employee’s employee number, last name, first name, and department name (2 points)
- [ ] List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B (2 points)
- [ ] List each employee in the Sales department, including their employee number, last name, and first name (2 points)
- [ ] List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name (4 points)
- [ ] List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name) (4 points)
### Module 10 - Surfs Up
[Link](https://github.com/coding-boot-camp/DataViz-Lesson-Plans/blob/v1.2/04-Canvas/10-Advanced-SQL/02-Application/02-challenge.md)
#### Jupyter Notebook Database Connection (10 points)
- [ ] Use the SQLAlchemy `create_engine()` function to connect to your SQLite database (1 point)
- [ ] Use the SQLAlchemy `automap_base()` function to reflect your tables into classes (3 points)
- [ ] Save references to the classes named `station` and `measurement` (4 points)
- [ ] Link Python to the database by creating a SQLAlchemy session (1 point)
- [ ] Close your session at the end of your notebook (1 point)
#### Precipitation Analysis (16 points)
- [ ] Create a query that finds the most recent date in the dataset (8/23/2017) (2 points)
- [ ] Create a query that collects only the `date` and `precipitation` for the last year of data without passing the date as a variable (4 points)
- [ ] Save the query results to a Pandas DataFrame to create `date` and `precipitation` columns (2 points)
- [ ] Sort the DataFrame by `date` (2 points)
- [ ] Plot the results by using the DataFrame `plot` method with `date` as the x and `precipitation` as the y variables (4 points)
- [ ] Use Pandas to print the summary statistics for the precipitation data (2 points)
#### Station Analysis (16 points)
- [ ] Design a query that correctly finds the number of stations in the dataset (9) (2 points)
- [ ] Design a query that correctly lists the stations and observation counts in descending order and finds the most active station (USC00519281) (2 points)
- [ ] Design a query that correctly finds the min, max, and average temperatures for the most active station (USC00519281) (3 points)
- [ ] Design a query to get the previous 12 months of temperature observation (TOBS) data that filters by the station that has the greatest number of observations (3 points)
- [ ] Save the query results to a Pandas DataFrame (2 points)
- [ ] Correctly plot a histogram with `bins=12` for the last year of data using `tobs` as the column to count. (4 points)
#### API SQLite Connection & Landing Page (10 points)
- [ ] Correctly generate the engine to the correct sqlite file (2 points)
- [ ] Use `automap_base()` and reflect the database schema (2 points)
- [ ] Correctly save references to the tables in the sqlite file (`measurement` and `station`) (2 points)
- [ ] Correctly create and binds the session between the python app and database (2 points)
- [ ] Display the available routes on the landing page (2 points)
#### API Static Routes (15 points)
##### A **precipitation route** that:
- [ ] Returns json with the date as the key and the value as the precipitation (3 points)
- [ ] Only returns the jsonified precipitation data for the last year in the database (3 points)
##### A **stations route** that:
- [ ] Returns jsonified data of all of the stations in the database (3 points)
##### A **tobs route** that:
- [ ] Returns jsonified data for the most active station (USC00519281) (3 points)
- [ ] Only returns the jsonified data for the last year of data (3 points)
#### API Dynamic Route (15 points)
##### A **start route** that:
- [ ] Accepts the start date as a parameter from the URL (2 points)
- [ ] Returns the min, max, and average temperatures calculated from the given start date to the end of the dataset (4 points)
##### A **start/end route** that:
- [ ] Accepts the start and end dates as parameters from the URL (3 points)
- [ ] Returns the min, max, and average temperatures calculated from the given start date to the given end date (6 points)
#### Coding Conventions and Formatting (8 points)
- [ ] Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (2 points)
- [ ] Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
- [ ] Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (2 points)
- [ ] Use concise logic and creative engineering where possible. (2 points)
#### Deployment and Submission (6 points)
- [ ] Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (2 points)
- [ ] Use the command line to add your files to the repository. (2 points)
- [ ] Include appropriate commit messages in your files. (2 points)
#### Comments (4 points)
- [ ] Be well commented with concise, relevant notes that other developers can understand. (4 points)

### Module 11 - Mars Scraping
#### Part 1: Scrape Titles and Preview Text from Mars News (40 points)
- [ ] Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
- [ ] The titles and preview text of the news articles were scraped and extracted. (20 points)
- [ ] The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)
#### Part 2: Scrape and Analyze Mars Weather Data (60 points)
- [ ] The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)
- [ ] The data was analyzed to answer the following questions: (10 points)
	- [ ] How many months exist on Mars? (5 points)
    - [ ] How many Martian days' worth of data are there? (5 points)
- [ ] The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)
    - [ ] Which month, on average, has the lowest temperature? The highest? (10 points)
    - [ ] Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
    - [ ] How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)
- [ ] The DataFrame was exported into a CSV file. (5 points)
### Module 14 - Belly Button Dashboard
[Link](https://github.com/coding-boot-camp/DataViz-Lesson-Plans/blob/v1.2/04-Canvas/14-Interactive-Visualizations/02-Application/02-challenge.md)
#### Bar Chart (30 points)
- [ ]  Chart initializes without error (10 points)
- [ ]  Chart updates when a new sample is selected (5 points)
- [ ]  Chart uses Top 10 sample values as values (5 points)
- [ ] Chart uses `otu_ids` as the labels (5 points)
- [ ]  Chart uses `otu_labels` as the tooltip (5 points)
#### Bubble Charts (40 points)
- [ ]  Chart initializes without error (10 points)
- [ ]  Chart updates when a new sample is selected (5 points)
- [ ] Chart uses `otu_ids` for the x values (5 points)
- [ ] Chart uses `otu_ids` for marker colors (5 points)
- [ ] Chart uses `sample_values` for the y values (5 points)
- [ ] Chart uses `sample_values` for the marker size (5 points)
- [ ] Chart uses `otu_labels for text values (5 points)
#### Metadata and Deployment (30 points)
- [ ] Metadata initializes without error (10 points)
- [ ] Metadata updates when a new sample is selected (10 points)
- [ ] App Successfully Deployed to GitHub Pages (10 points)