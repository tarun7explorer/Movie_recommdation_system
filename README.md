# Movie_recommdation_system
This system helps to select a movie based on your choice depending on your current mood as well as based on the rating &amp; the theme of the movie.
# import pandas library
import pandas as pd

# Get the data
column_names = ['user_id', 'item_id', 'rating', 'timestamp'] 

path = 'https://media.geeksforgeeks.org/wp-content/uploads/file.tsv'

df = pd.read_csv(path, sep='\t', names=column_names)

# Check the head of the data
df.head()
