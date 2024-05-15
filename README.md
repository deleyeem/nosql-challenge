# nosql-challenge
## Project Overview
The objective of this project is to analyze food hygiene ratings data from the UK Food Standards Agency. The goal is to assist the editors of a food magazine, "Eat Safe, Love," in evaluating and understanding the ratings data to guide their future articles and recommendations.

## Tools and Libraries
MongoDB: Used as the NoSQL database management system.

PyMongo: A Python library that enables interaction with MongoDB from Python code.

Pretty Print (pprint): A Python module used for pretty printing data structures, particularly helpful for displaying MongoDB documents in a more readable format.

Jupyter Notebook: Utilized as the development environment for running Python code interactively and documenting the process.

## Process Description
Part 1: Database and Jupyter Notebook Set Up
For the initial setup of the project, I iimported the data from the establishments.json file into a MongoDB database named uk_food with a collection named establishments. After importing the data, I created an instance of the Mongo Client to establish a connection to the MongoDB server. I also verified the successful creation of the database and loading of the data.

Part 2: Update Database
Before performing queries or analysis, I made some modifications like adding a new document. removing documents within Dover Loval Authority and updating field data types.

Part 3: Exploratory Analysis
To anlyze the following questions, I created queries (including aggregation), sorted values, counted number of documents, printed via pprint and converted results to Pandas DataFrame

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Conclusion
Through this project, I provide valuable insights into food hygiene ratings data, enabling the food magazine editors to make informed decisions about future articles and recommendations. The exploratory analysis uncovers patterns and trends within the data, empowering the editors to prioritize establishments and locations for coverage based on their ratings and other factors.