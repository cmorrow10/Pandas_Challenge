### PyCitySchools Analysis
---
![PyCitySchools](https://github.com/kmorrow439/pandas_challenge/assets/114371722/895a4594-7183-4ce6-b0a0-db75152f86e6)
#### Background
##### You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
##### As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.
---
#### District Summary
##### Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.
##### Included the following:
##### - Total number of unique schools.
##### - Total students.
##### - Total budget.
##### - Average math score.
##### - Average reading score.
##### - % passing math (the percentage of students who passed math).
##### - % passing reading (the percentage of students who passed reading).
##### - % overall passing (the percentage of students who passed math AND reading).
---
#### School Summary
##### Performed the necessary calculations and then created a DataFrame that summarized key metrics about each school.
##### Included the following:
##### - School name.
##### - School type.
##### - Total students.
##### - Total school budget.
##### - Per student budget.
##### - Average math score.
##### - Average reading score.
##### - % passing math (the percentage of students who passed math).
##### - % passing reading (the percentage of students who passed reading).
##### - % overall passing (the percentage of students who passed math AND reading).
---
#### Highest-Performing Schools (by % Overall Passing)
##### Sorted the schools by "% Overall Passing" in descending order and displayed the top 5 rows.
##### Saved the results in a DataFrame called "top_schools".
---
#### Lowest-Performing Schools (by % Overall Passing)
##### Sorted the schools by "% Overall Passing" in ascending order and display the top 5 rows.
##### Saved the results in a DataFrame called "bottom_schools".
---
#### Math Scores by Grade
##### Performed the necessary calculations and created a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
---
#### Reading Scores by Grade
##### Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
---
#### Scores by School Spending
##### Created a table that breaks down school performance based on average spending ranges (per student).
##### Created four bins with reasonable cutoff values to group school spending.
![PyCitySchools1](https://github.com/kmorrow439/pandas_challenge/assets/114371722/f299455f-2289-4321-baef-9545e52e53c4)
##### Used "pd.cut" to categorize spending based on the bins.
##### Calculated the mean scores per spending range.
![PyCitySchools3](https://github.com/kmorrow439/pandas_challenge/assets/114371722/f8ce4dbc-ad57-4331-b0a8-e09584cb7a9a)
##### Used the scores above to create a DataFrame called "spending_summary".
##### Included the following metrics in the table:
##### - Average math score.
##### - Average reading score.
##### - % passing math (the percentage of students who passed math).
##### - % passing reading (the percentage of students who passed reading).
##### - % overall passing (the percentage of students who passed math AND reading).
#### Scores by School Size
##### Used the following code to bin the "per_school_summary".
![PyCitySchools2](https://github.com/kmorrow439/pandas_challenge/assets/114371722/9011d79f-9b21-4b0b-bd22-64075cfaa405)
##### Used "pd.cut" on the "Total Students" column of the "per_school_summary" DataFrame.
##### Created a DataFrame called "size_summary" that breaks down school performance based on school size (small, medium, or large).
#### Scores by School Type
##### Used the "per_school_summary" DataFrame to create a new DataFrame called "type_summary".
##### The new DataFrame shows school performance based on the "School Type".
