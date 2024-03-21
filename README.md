# UK Food Standards Agency Ratings Analysis

## Project Overview
This project involved several tasks related to evaluating UK Food Standards Agency ratings data for Eat Safe, Love magazine. The project was divided into three main parts: setting up the database and Jupyter notebook, updating the database, and conducting exploratory analysis.

## Project Structure
The project components and tasks completed are outlined below:

### Part 1: Database and Jupyter Notebook Set Up
- Imported data from `establishments.json` into MongoDB.
- Confirmed database and collection setup.
- Utilized `NoSQL_setup_starter.ipynb` for these tasks.

### Part 2: Update the Database
- Added a new restaurant entry for "Penang Flavours" with a pending rating.
- Updated BusinessTypeID for the new restaurant.
- Removed establishments in the Dover Local Authority.
- Converted string numbers to decimals and integers.
- Performed these tasks in `NoSQL_setup_starter.ipynb`.

### Part 3: Exploratory Analysis
- Utilized `NoSQL_analysis_starter.ipynb` to answer specific questions using MongoDB queries and analyze the data.
  - Identified establishments with a hygiene score of 20.
  - Identified establishments in London with RatingValue greater than or equal to 4.
  - Determined the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score and proximity to "Penang Flavours".
  - Calculated the number of establishments with a hygiene score of 0 in each Local Authority, sorted in descending order.

## Repository Structure
The structure of the repository includes:
- `Resources/establishments.json`: JSON file containing establishments data.
- `NoSQL_setup_starter.ipynb`: Jupyter Notebook for database setup and updates.
- `NoSQL_analysis_starter.ipynb`: Jupyter Notebook for exploratory analysis.
- `README.md`: Project README file.

## Tools Used
The tools used in this project include:
- Python
- PyMongo
- MongoDB
- Jupyter Notebook
- Pandas

## Conclusion
This project demonstrated my ability to work with MongoDB, perform database operations, conduct data analysis using Python and Jupyter Notebook, and answer specific queries to derive insights from the data. 
