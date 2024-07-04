# Project - FIFA '21 Player Ratings

![fifa-assignment](fifa-assignment.jpeg)


## FIFA '21 Player Ratings
The FIFA 21 player rating dataset contains information about the ratings of football players in the FIFA 21 video game. Each player is assigned a rating that reflects their overall skill level in the game. The dataset includes various attributes such as player name, nationality, club, position, and individual attributes like pace, shooting, passing, dribbling, defending, and physicality. These ratings are used to determine player performance and abilities within the game.

Here, you have a very messy and raw dataset of EA Sports' installment of their hit FIFA series - FIFA21, which was scraped from [sofifa.com](https://sofifa.com).


### Challenges
One of the challenges of web scraping is unclean data. Different front-end developers and data scientist write the HTML their own way, and that makes the incoming data unpredictable. Your task in this assignment is to clean up this dataset

You'll definitely learn a lot about data cleaning with this dataset.


### TODOs
- Look through the data - `fifa_21_raw_data.csv`
- Read the `hints` below to have an idea of what is required to do with the data.
- Work using the provided notebook in the cloned repo.


### HINTS
- Convert the height and weight columns to numerical forms
- Remove the unnecessary newline characters from all columns that have them.
- Handle duplicate player data from the dataset by dropping duplicate rows, while keeping the first occurrence
- Split the LongName into 2 new coloumns - `first name` and `last name`.
- Handle missing values by filling it with `statistical techniques`.
- Are there outliers in the data? If yes, handle them with any of the techniques you've learnt.
- `Value`, `Wage` and `Release Clause` are string columns. Convert them to numbers. For eg, "M" in value column is Million, so multiply the row values by 1,000,000, etc.
- Convert all currency character to dollar i.e, `$` in column `Value`, `Wage` and `Release Clause`
- Some columns have 'star' characters/icons. Strip those columns of these stars and make the columns numerical
- Go beyond these hints and clean any other inconsistencies you can find.
