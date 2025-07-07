# This is a Project I did while studying Data Analysis

Netflix 1990s Movie Analysis
This Jupyter Notebook performs an exploratory data analysis (EDA) on a Netflix dataset to uncover insights about movies released in the 1990s. The project is framed as research for a production company specializing in nostalgic styles, aiming to better understand the film landscape of that decade.
Analysis Overview
The notebook walks through the following key steps:
Data Loading: The netflix_data.csv dataset is loaded into a pandas DataFrame.
Data Filtering: The dataset is filtered to create a subset containing only content of the type 'Movie' released between the years 1990 and 1999.
Duration Visualization: A histogram is generated using matplotlib to visualize the distribution of movie durations from the 1990s, helping to identify common runtimes.
Genre-Specific Investigation: The analysis drills down further to count the number of "Action" movies from the 1990s that have a duration of less than 90 minutes.
Technologies Used
Python
pandas
matplotlib
