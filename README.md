README for Netflix Data Analysis 

Overview
This project focuses on analyzing Netflix shows and movies data using Python and R. It encompasses tasks such as data preparation, cleaning, exploration, and visualization.
The workflow is designed to ensure systematic handling of the dataset and the generation of meaningful insights.

Steps and Workflow
1. Data Preparation:
The objective is to organize the dataset for analysis.
Process:
•	The dataset (netflix_data.zip) is unzipped using Python’s zipfile module.
•	The extracted file is renamed to Netflix_shows_movies.csv for clarity and consistency.
2. Data Cleaning:
The objective is to ensure the dataset is accurate and ready for analysis.
Process:
•	Rows with missing values are removed.
•	Columns are renamed for better readability (e.g., listed_in → genres).
•	The "Date Added" column is converted into a proper date format.
•	The cleaned dataset is saved as Clean_Data_Set.csv.
3. Data Exploration:
The objective is to gain valuable insights from the data.
Process:
•	Display basic dataset information, including data types and column names.
•	Generate descriptive statistics for categorical data.
•	Identify the mode (most frequent values) of key columns, such as genres and title.
4. Data Visualization:
The objective is to create impactful visual representations of the data.
Visualizations:
Most Watched Genres: A bar chart showcasing the top 10 most-watched genres.
Saved as Python_genre_most_watched.png.
Ratings Distribution: A histogram depicting the distribution of ratings.
Saved as Python_Rating_Distribution.png.
5. Error Handling
The script includes comprehensive error handling to ensure robustness and smooth execution. Meaningful error messages are provided for issues such as:
Missing files.
Data type conversion errors.
How to Use the Code

Prerequisites
1. Python 3.x installed on your system.
2. Required Python libraries:
pandas
os
zipfile
seaborn
matplotlib
3. The dataset file (netflix_data.zip) should be placed in the same directory as the script.
Steps to Run
1. Ensure all dependencies are installed. Use the command:
pip install pandas seaborn matplotlib
2. Run the Python script step by step in a Jupyter Notebook or any IDE.
3. Verify that netflix_data.zip is present in the working directory.
Outputs
1. Cleaned Dataset: Saved as Clean_Data_Set.csv.
2. Visualizations:
Python_genre_most_watched.png: Bar chart for the most-watched genres.
Python_Rating_Distribution.png: Histogram of rating distribution.
File Structure
BAN 6420 ASSIGNMENT MOD 4  
├── netflix_data.zip                 # Original zipped dataset  
├── Netflix_shows_movies.csv         # Renamed and unzipped dataset  
├── Clean_Data_Set.csv               # Cleaned dataset  
├── Python_genre_most_watched.png    # Genre visualization  
├── Python_Rating_Distribution.png   # Ratings visualization  
├── README.md                        # Instructions for the project  
├── Netflix_Data_Analysis.py         # Python script for analysis
The script is designed to handle common errors such as missing files or data conversion issues gracefully, ensuring a seamless execution process.
Examples of Errors Addressed:
File not found.
Errors during data type conversion.

