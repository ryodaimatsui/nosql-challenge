## NoSQL-Challenge
![takahiro-taguchi-8l_RuuZrOyY-unsplash](https://github.com/ryodaimatsui/nosql-challenge/assets/137141385/2c458881-0e05-420e-b97c-17c5b2b531e5)

Context of this challenge:

"The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles."  (Source: Penn Data Analysis and Visualization Bootcamp)

The initial phase of the challenge involves configuring the database ('uk_food') and selecting the collection ('establishments'). This is achieved by importing data from a JSON file using a command line text.

In the second phase of the challenge, we focus on updating the collection by adding data for a restaurant named 'Penang Flavours.' Subsequently, we verify that the document is updated with the accurate value for the 'BusinessTypeID' field obtained through a basic query. Additionally, all documents with the value 'Dover Local Authority' for the field 'LocalAuthorityName' is removed from the collection.

In the third and final stage, we conduct exploratory analysis, answering the following questions:
- Question 1: Which establishments have a hygiene score equal to 20?
- Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
- Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
