# Eat Safe, Love
## Part1: Working with MongoDB using PyMongo

- Import Data: Use the following terminal command to import data from a JSON file into a MongoDB collection:
- Create MongoDB Client: Create a MongoDB client instance to connect to the MongoDB server
- Confirm Database and Collection: Confirm the existence of the database and collection
- Find and Display a Document: Retrieve and display a document from a collection
- Assign Collection: Assign a collection to a variable for further interaction

## Part2: Update the Database

- Add New Restaurant: A new halal restaurant opened in Greenwich. The information has been added to the database.
- Update BusinessTypeID for New Restaurant: The BusinessTypeID for "Restaurant/Cafe/Canteen" was found and updated for the new restaurant.
- Remove Establishments in Dover: Establishments in Dover were removed from the database, as requested by the magazine.
- Convert Number Values to Numbers: Latitude, longitude, and rating values were converted to numeric data types.

## Part3: Exploratory Analysis of MongoDB Data
- Analysis: The following questions were explored:

    1. Establishments with hygiene score equal to 20.
    2. Establishments in London with RatingValue greater than or equal to 4.
    3. Top 5 establishments with RatingValue 5, sorted by lowest hygiene score and proximity to "Penang Flavours".
    4. Establishments with hygiene score of 0 by Local Authority, top ten areas.
    
For each question, the number of documents, the first document, and a Pandas DataFrame with results were provided.
