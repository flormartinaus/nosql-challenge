# nosql-challenge

**The objective of this project is to analyze food hygiene ratings data provided by the UK Food Standards Agency and assist the editors of Eat Safe, Love magazine in identifying establishments for future articles. The analysis involves setting up the database, updating the data, and performing exploratory analysis to answer specific questions.**

# Part 1: Database and Jupyter Notebook Set Up

Import the establishments.json file into a MongoDB database named "uk_food" and a collection named "establishments."
Import the required libraries: PyMongo and Pretty Print (pprint).
Create a Mongo Client instance.
Confirm the successful creation of the database and data import by listing the databases, listing the collections, and displaying a document using find_one and pprint.
Assign the establishments collection to a variable for further use.

# Part 2: Update the Database

Add a new halal restaurant in Greenwich to the database, including its information and BusinessTypeID.
Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant with the obtained BusinessTypeID.
Check the number of documents containing the Dover Local Authority, remove them from the database, and verify their deletion.
Convert certain number values from strings to decimal numbers and integers using update_many.

# Part 3: Exploratory Analysis

Conduct exploratory analysis to answer specific questions provided by Eat Safe, Love magazine.
Analyze the RatingValue field to determine the overall ratings of establishments.
Perform data analysis to help the magazine find desired locations and avoid certain areas.
 
