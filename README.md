# Data-Science-Task-for-Gaza-Sky-Geeks

## Analysis Report: IMDB Dataset of Top 1000 Movies and TV Shows
### Introduction
In this analysis, we explored the IMDB dataset of the top 1000 movies and TV shows. The dataset contains information such as the title, release year, certificate, genre, IMDb rating, director, and more.

### The requirements
* Download the IMDB dataset of top 1000 movies and TV shows from Kaggle and load it into a pandas dataframe using the read_csv() function.
* Clean and preprocess the data by removing unnecessary columns and handling missing values.
* Explore the data to identify the most popular genre of movies and TV shows using pandas.
* Create a new dataframe containing the count of movies/TV shows in each genre using pandas.
* Visualize the data using a bar chart to show the most popular genre of movies/TV shows using pandas and the matplotlib library.
* Identify the director with the most top-rated movies/TV shows by creating a new dataframe containing the count of movies/TV shows directed by each director using pandas.
* Visualize the data using a bar chart to show the director with the most top-rated movies/TV shows using pandas and matplotlib.
* Write a report summarizing your analysis and findings, including any insights or observations you discovered, using markdown cells in the Jupyter notebook.

### Data Preprocessing
Before analyzing the data, we performed some data preprocessing steps, including removing unnecessary columns and handling missing values. The columns we focused on for analysis were: 'Series_Title', 'Released_Year', 'Certificate', 'Runtime', 'Genre', 'IMDB_Rating', 'Overview', 'Meta_score', 'Director', 'No_of_Votes', and 'Gross'.

### Popular Genre
To identify the most popular genre among movies and TV shows, we analyzed the 'Genre' column. By using the value_counts() function in pandas, we obtained a count of movies/TV shows for each genre. The genre with the highest count was found to be 'Drama'.

### Director Analysis
We also explored the directors and their contribution to top-rated movies/TV shows. We created a new dataframe to count the number of movies/TV shows directed by each director. Sorting this dataframe in descending order allowed us to identify the director(s) with the most top-rated content. The director with the highest count was Steven Spielberg.

### Insights and Observations
* The most popular genre among the top 1000 movies and TV shows in the dataset is Drama, indicating a strong preference for dramatic content.
* Steven Spielberg emerged as the director with the most top-rated movies/TV shows, showcasing his impact and success in the industry.
* It would be interesting to further analyze the relationship between the director and IMDb ratings to understand the influence of different directors on the overall ratings of movies/TV shows.
### Conclusion
This analysis provided insights into the popular genre and top-rated directors in the IMDB dataset of the top 1000 movies and TV shows. Understanding the preferences and contributions of directors can help in evaluating the quality and success of movies/TV shows. Further analysis can be done to explore other aspects of the dataset and gain deeper insights.
