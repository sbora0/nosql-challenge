# nosql-challenge
Nosql Challenge Assignment 12

For this assignment there were three requirements as given below:

1. Database and Jupyter Notebook Set Up

       • Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a   markdown cell in your notebook.
       • Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).
       • Create an instance of the Mongo Client.
       • Confirm that you created the database and loaded the data properly:
       • List the databases you have in MongoDB. Confirm that uk_food is listed.
       • List the collection(s) in the database to ensure that establishments is there.
       • Find and display one document in the establishments collection using find_one and display with pprint.
       • Assign the establishments collection to a variable to prepare the collection for use.

2. Update the Database

       • An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis.
       • Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
       • Update the new restaurant with the BusinessTypeID you found.
       • The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they            were deleted.
       • Some of the number values are stored as strings, when they should be stored as numbers.
       • Use update_many to convert latitude and longitude to decimal numbers.
       • Use update_many to convert RatingValue to integer numbers.
   
3. Exploratory Analysis

       • Use count_documents to display the number of documents contained in the result.
       • Display the first document in the results using pprint.
       • Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.
       • Which establishments have a hygiene score equal to 20?
       • Which establishments in London have a RatingValue greater than or equal to 4?
       • What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
       • How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

       
Files Information:

       •	The file “establishments.json” is in "Resources" folder and is used to create the database.
       •	The file “NoSQL_setup.ipynb” is used to complete the first and second requirement.
       •	The file “NoSQL_analysis.ipynb” is used to complete the exploratory analysis.
