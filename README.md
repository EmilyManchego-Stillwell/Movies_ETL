# Movies_ETL
## Purpose:
    The purpose of this project was to extract, transform, and load raw movie data. We extracted data from different sources and loaded it into a jupyter notebook so we could transform the data. We transformed each data file(wiki-movies.json, movies_metadata.csv, and ratings.csv) by creating Pandas DataFrames for each file. With the different data frames we cleaned up and removed unnecessary columns, converted data types in each data frame to correct data types, and then merged data from two data frames to create two new data frames. Once the clean and transform process was complete, we loaded the merged movies_df into PostgreSQL as a table, called movies, in a new database named movie_data_db. We also loaded the rating.csv file into the database as a separate table, named ratings. 