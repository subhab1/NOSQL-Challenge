# NOSQL-Challenge
## Background 
The UK Food Standards Agency checks different places in the United Kingdom that serve food, like restaurants and cafes. They give these places a rating based on how clean and safe their food preparation and handling is. 
Now, a food magazine called Eat Safe, Love has hired me to look at this rating data. They want to know which places are doing really well in terms of food safety and hygiene. This information will help their journalists and food critics decide which places to write about in their future articles.In simple terms, we're going to find out which restaurants and eateries are the cleanest and safest to eat at so that the magazine can talk about them in their stories.
* Import Data: Go to your Terminal and use the command to bring in the data from the "establishments.json" file. Call the database "uk_food" and the collection "establishments".

* Import Libraries: In your notebook, make sure to import two libraries: PyMongo and Pretty Print (pprint).

* Create a Connection: Set up a connection to the MongoDB database using the Mongo Client.

* Check Database and Collection: To make sure everything is working, do the following:

  * List the databases in MongoDB. Check if "uk_food" is among them.
  * List the collections within the "uk_food" database to make sure "establishments" is there.
* Display a Document: Find and display one record from the "establishments" collection using the "find_one" method. Use "pprint" to make it easier to read.

* Assign Collection: Save the "establishments" collection in a variable so you can work with it in your notebook.

## This project is split into two main parts, each handled by a separate notebook:

1. **NoSQL_setup_starter.ipynb**: In this notebook, we set up a database using MongoDB, import data from the "establishments.json" file, and make necessary updates to the database based on the requirements of a food magazine. Essentially, it's about creating the foundation and structure for storing and managing the food establishment data.

2. **NoSQL_analysis_starter.ipynb**: This notebook focuses on exploring and understanding the data. It does this by using various queries, aggregations, and data manipulation techniques. The goal is to answer specific questions related to the hygiene ratings of the establishments. This part of the project helps extract meaningful insights and patterns from the data.

## Conclusion
The data needed for this project is stored in the Resources folder, primarily in the "establishments.json" file. We leverage MongoDB as a NoSQL database, and PyMongo serves as the tool for connecting to the database, querying it, and making updates when necessary. 

In simple terms, the first notebook sets up the database and prepares it for use, while the second notebook dives into the data to find interesting information about hygiene ratings. It's a demonstration of how we can efficiently work with data using MongoDB and PyMongo.
