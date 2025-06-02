here I have done a simple data cleaning file named "netflix_titles.csv" which is sourced from Kaggle with name Netflix movies and tv shows.

goal-
 The goal was to clean up the raw CSV file by handling missing data, fixing formatting issues, and getting it ready for analysis.

cleaning steps-
1) load data 
2) checking for missing values
3) dropped rows which has missing values like 'type' and 'title'.
4) filled with 'not available' into clomns like 'cast' 'director' 'country'
4) remove duplicates with .drop_duplicates.
5) standardizing column names with lower case.
6) fixing date time format and filled with 'Nat'
7) final check to check the changes.

final file named - netflix_cleaned.ipynb