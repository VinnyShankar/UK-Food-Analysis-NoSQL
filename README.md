# UK-Food-Analysis-NoSQL
Analyzing the best rated restaurants in London
### - Overview
- Author: Vinny Shankar
- Acknowledgements:
    - Study Groups: worked together with several students to understand the assignment
    - Classmates: [Hany Dief](https://github.com/hanydief), [Jed Miller](https://github.com/Jed-Miller), and [Jésus Jímenez](https://github.com/JesusJimenez3318)
    - Program: University of California Berkeley Data Analytics Bootcamp
    - Starter Code: The Module Challenge provided starter code that guided the process
    - Instructor: Ahmad Sweed
    - Tutor: [Bethany Lindberg](https://github.com/bethanylindberg)
### - Contents
- One `UK-Food_Analysis` folder containing:
    * A `Resources` folder that contains a .json file
    * A `setup` Jupyter Notebook that uses the .json file to create a new MongoDB NoSQL database called "uk_food" with a new collection called "establishments", transforms the data in the collection, and prepares the collection for analysis
    * An `analysis` Jupyter Notebook that analyzes the data in the newly inserted collection
    
- This README.md file
### - Setup
* Create a new MongoDB database called "uk_food"
* Import the .json file into a new collection inside "uk_food"
* Insert a new document into the collection
* Update the new document
* Drop all documents from the "Dover" Local Authority
* Update all latitudes and longitudes from strings to doubles/floats
* Update all non-numeric `RatingValue`s to `Null`
* Update all `RatingValue` to integers
### - Analysis
* Note: the lower the `RatingValue` and `Hygiene`, the better
* The following questions are answered:
    * Which establishments have a Hygiene score of 20?
    * Which establishments in London have a `RatingValue` greater than or equal to 4?
    * What are the top 5 establishments with a `RatingValue` of 5, sorted by lowest Hygiene score, within 0.01 degrees of the newly inserted establishment "Penang Flavours"?
    * How many establishments in each Local Authority Area have a Hygiene score of 0?