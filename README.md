# nosql-challenge
 
# Part 1: Database and Jupyter Notebook Set Up
  
  # NoSQL_setup_starter.ipynb

- For the setup starter code we have used NoSQL_setup_starter.ipynb this page.
- First we import the dependencies and created instance of MongoClient.
- We assigned the data base name uk_food.collection name is establishments.
- Created dictionary for adding new restaurant name Penang Flavours.
- Updated this restaurant in establishments. 
- We found longitude and latitude in geocoad.
- After that we have extracted rating value from string to integer.

# Part 2 Exploratory Analysis

  # NoSQL_analysis_starter.ipynb

- For this notebook set up we have import our dependencies, Created instance of MongoClient.
- Assigned database to uk_food. found our database name establishments.
- We have Used count_documents to display the number of documents contained in the result.
- Converted the result in Pandas DataFrame.
- Found the establishments with London as the Local Authority and has a RatingValue greater than 4.
- Extracted 5 establishments with RatingValue 5, Also sortedhygine score.
- Then we created query for establishments in each Local Authority area have a hygiene score of 0.
- Converted results in DataFrame, the displayed 10 rows.