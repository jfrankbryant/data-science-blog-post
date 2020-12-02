Motivation  
This is a repository for my Udacity Data Scientist Nanodegree Introduction to Data Science: Project 1: Data Science Blog Post.
I choose this dataset because I'm interested in bringing inclusivity of marginalized communities (Black, Indigenous, Latinx, disabled, etc.) to the publishing industry and I want to look into what the current state of inclusivity is.

Necessary Libraries  
NumPy  
Pandas  
Matplotlib  
Seaborn  

Files in the Repository w/ Summary  
books.csv: the base GoodReads dataset  
connected_books_bar.png: image of bar graph of the connected books for the top 20 most rated books  
connected_books_pie.png: image of pie chart of the connected books for the top 20 most rated books  
corrected_goodread_df.csv: wragled dataframe to start with for future data analysis purposes  
DataScienceBlogPost-DataAnalysis.ipynb: Jupyter notebook to analyze data from GoodReads dataset  
DataScienceBlogPost-Wrangling.ipynb: Jupyter notebook to tidy and clean the GoodReads dataset from Kaggle  
gender_sum_pie.png: image of pie chart of the gender of the authors of the books for the top 20 most rated books  
genres_subgenres_bar.png: image of bar graph of the connected books for the top 20 most rated books  
isbn.csv: book identifier exported to use in the future to pull data from an API  
isbn13.csv: book identifier exported to use in the future to pull data from an API  
ratingsslice_ratings_reviews_bar.png: image of bar graph of the connected books for the top 20 most rated books  
README.md: documentation file  
reviewsslice_ratings_reviews_bar.png: image of bar graph of the review slice of the books for the top 20 most rated books  
skin_color_pie.png: image of bar graph of the connected books for the top 20 most rated books  
zero_booklength_updated.csv: updated file to import into the Data Analysis file of data found for the exported zero_booklength dataframe  
zero_booklength.csv: exported dataframe of the Data Analysis file of dataset found with zero book length books (zero audio hours or page numbers)  


Analysis Summary  
Inclusivity is not looking good on two basic, visible (for the most part) marker: gender identity and skin color. Cis gender identity and white skin color is extremely over-represented in the dataset. It was also confirmed that publishing a series helps the popularity of your books (specifcally the first book of your popular series). There is evidence that being cis, white, and male helps your popularity-- however this maybe more likely due to bias in who gets published and who is thrust upon impressionable teens as who to read as part of the literary canon as well as who to read for funsies, who gets more marketing money, and who is picked to be part of the literary canon to begin with.

Acknowledgements  
Thank you to [Kaggle user jealousleopard](https://www.kaggle.com/jealousleopard/goodreadsbooks/notebooks) who provided the book data being used.
