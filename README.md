Analysis of US Births Data

This code analyzes US births data from two sources: CDC and SSA. The following questions are answered:

    What is the average number of births per day of the week across all years?
    Which day of the week has the highest number of births on average?
    How does the number of births vary by month of the year?
    Are there any months where the number of births is consistently higher or lower than average?
    How do the trends in births differ between weekdays and weekends?
    How many births occur on Friday the 13th compared to other days of the month?

Data Sources

The data was obtained from the following sources:

    CDC: https://github.com/fivethirtyeight/data/blob/master/births/US_births_1994-2003_CDC_NCHS.csv
    SSA: https://github.com/fivethirtyeight/data/blob/master/births/US_births_2000-2014_SSA.csv

Data Manipulation

The data was loaded into two tables (cdc_births and ssa_births) in a MySQL database. The code then performs SQL queries to answer the questions listed above. The SQL code is included in this repository.
Results

The results of the analysis are presented in the SQL code comments. The code provides the answers to each question, as well as any additional information that was relevant to the analysis.
Requirements

    MySQL database
    Access to the CDC and SSA birth data files (included in this repository)

How to Use

To run the code, load the data files into a MySQL database and run the SQL queries included in the code. The code assumes that the data files are located in the 'data-master/births/' directory. The code can be modified to reflect the location of the data files if necessary.
Acknowledgments

The data used in this analysis was obtained from FiveThirtyEight, a website that covers politics, sports, and culture through data journalism. The authors of the data are not affiliated with this code or its author.
