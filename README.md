
# Cleaning Company Data - Lab


## Introduction
Let's take what we learned in the last lesson and get some practice working on an expanded data set.


## Objectives
You will be able to:
* Import data from a csv file into a DataFrame
* Transform data within a DataFrame to clean it up
* Export data from a DataFrame into a csv

## Import Pandas

Remember to start by importing Pandas as `pd` in the cell below...

## Import the Data

Then use the `read_csv()` method in the cell below to import the data into a data frame - let's call it `df`. The data is in a file called `new_data.csv`

## Look at the Data

Take a little time in the next cell to explore the data. If you want to add new cells feel free to "Insert - Insert Cell Below" in the Jupyter Notebook.


## Clean up the Data
Start by looking at the `value_counts()` for EntityType and then write some code to get consistent capitalization to make the value counts method for EntityType return just three records.

## Export the Data

Finally, write some code to export the data to a file called "cleaned_data.csv" and then write a couple of lines of code to re-import that file and make sure that the values_counts() are what you'd want them to be for the EntityType field.

## Extra Credit

For extra credit, try to clean up the state of incorporations so that the `value_counts()` for that are what you would want them to be (hint - in addition to capitalization, you'll also need to transform full state names to abbreviations or the other way around. 

## Summary

Congratulations! Now you're using the same tools you will after this course to import, clean up and then export data sets! Next class we'll introduce a powerful new tool for doing more complex data cleanups - Regular Expressions!

