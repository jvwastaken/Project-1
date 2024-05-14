# Project-1

## Data Sources:
- Main data was retrieved from [Kaggle](https://www.kaggle.com/) and downloaded as a [CSV file](JV_Analysis/IMDb_All_Genres_etf_clean1.csv).
- The Kaggle CSV file was then combined with data from [OMDb API](https://www.omdbapi.com/) using requests via Python in this [file](Data/OMDB_API_Pull.ipynb). 
- The dataframe of the OMDb and Kaggle data were then combined into a single dataframe which was then output as a [CSV File](JV_Analysis/IMDb_All_Genres_etf_clean1.csv).

## Code Troubleshooting:
- XPert Learning Assistant
- ChatGPT
>[!NOTE]
> The above external sources were used to help us in correcting/debugging our code. Aside that, all code was generated by referencing materials covered in class thus far (Modules 1-6).

Timeline:
    1. Monday, May 5th we created the project propsal for "Blockbuster Breakdown" and had team members review different data sets. 
    2. Tuesday, May 6th JV merged a list of 5000 movies from Kaggle and combined it with data from https://www.omdbapi.com/ to create Movie_RawDataset.csv
    3. Thursday, May 7th I merged the oscar.csv data to the Movie_RawDataset.csv to create movies_oscars.csv
    4. Saturday, May 11th I decoupled the 'Awards' column and created two new columns for Award Wins and Award Nominations.
    5. Saturday, May 11th I created a clean analysis for my awards
    6. Saturday, May 12th at 6:30PM - 8:30PM PST Team met to get an update and share lessons learned.
    7. Sunday, May 13th 11:00 AM - 4:00 PM PST playing with analysis, and went back to cleaning data to remove objects so that it can be played with 