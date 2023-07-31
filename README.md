# Project-2

-This project revolved around evaluating various establishments across the United Kingdom, and gives them a food hygiene rating.

- Part 1 Deliverable: Import data from teh establishments.json file from the terminal and set up the database in MongoDB by using PyMongo.

- Part 2 Deliverable: Scrape and analyze UK Food database and Establishments collection to explore the questions "Which establishments have a hygiene score equal to 20?", "Which establishments in London have a RatingValue greater than or equal to 4?", "What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?", "How many establishments in each Local Authority area have a hygiene score of 0?"

-Highlights of work Done:  

- Correctly create UK Foods database and Establishments collection through mongoimport
  
- Insert the supplied data for the "Penang Flavours" restaurant in correctly into the establishments collection

- Created a query that correctly performed to find the establishments in London with a RatingValue greater than or equal to 4

- Created a query that correctly performed to find the establishments within 0.01 degree of the "Penang Flavours" restaurant

- Created an aggregation pipeline to include a match query, group, and sort

- The group step of the pipeline is grouped on LocalAuthorityName and counts the number of documents

- The sort step of the pipeline sorts the count of the documents in descending order 
