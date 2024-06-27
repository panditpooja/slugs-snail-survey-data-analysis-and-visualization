# Tracing Nature's Trail: Exploring Slugs and Snails Through Data Analysis and Visualization
## Description
This repository contains Python code and outputs in PDF format specifically focusing on the seasonal trends of slugs and snails populations, based on surveys conducted for different years. Slugs and snails, being sensitive to temperature and moisture, exhibit variations in their activity levels across different seasons.

## Scenario Questions
Used the dataset to answer the following questions:
1. How do the number of slugs and snails found by biologists change over time in this data set?
2. How do the number of slug and snail species found by biologists change over time in this data set? 

## Additional Considerations: 
- The dataset contains unnecessary information, so filtering and selection of relevant data points are crucial so I have provided thorough explanations and summaries in my python code and detailed PDF report.
  
## Project Steps:
1. **Subset Relevant Columns:**
   - Subset the data by columns to choose only those columns which will help in answering the dataset associated questions.
2. **Data Cleaning:**
   - Understand the total number of rows and columns of the dataset along with the datatypes of each column. Additionally, figure out how many missing values are present so that I can handle them in the filtered dataset.
   - Convert Date Column: Change the datatype of "Date" from "Object" to "DateTime" format for proper date handling.
   - Drop the "Date" column as it does not contribute for further analysis.
3. **Data Transformation:**
   - Adding a new column "Year" by extracting the "year" value and another column "Month" by extracting "month" from "Date".
   - Adding the "Season" column based on the month of the year.
4. **Perform Grouping and Aggregation:**
   - Use pandas to group and aggregate data to answer the specific two questions related to the dataset.
5. **Data visualization:**
   - Perform data visualization for each question to understand the trend over time effectively.
6. **Develop pretty and illusion plots**
   - Create pretty and illusion plots that present the findings related to the two specific questions posed by the dataset.
## Expected Output:
1. Generate one pretty and one illusion plot for each question.
2. Prepare final pdf report with relevant visual plots and python code snippet.

## Tools Used:
- Python for data manipulation and analysis.
- Pandas, Matplotlib, and Seaborn for data visualization.
- Google colabs, an online platform for Jupyter notebooks that offers free GPU and TPU resources, making it ideal for data-intensive tasks and machine learning experiments.
