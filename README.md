# DataPreprocessing
Saving for later. A script to help do data preprocessing for maching learning.

## Imports the dataset
- Creates an X set with the independant variables
- Creates a Y set with the dependant variables

## Fills in missing data for specified columns 
- Where data is missing, and the columns are specified, it will add the mean value for the column into that cell

## Encodes categorical data
- Where there is categorical data in text form, it will convert these to numerical values
- It will then split these into seperate columns so that later categories are not given greater prominence

## Splits the data into training and testing
- Allows for checking of work and hopefully will flag up overfitting issues

## Feature scaling
- Currently just feature scaling for X. Suitable for Y/N output at the moment.
- Most values fall between -1 and 1, some values fall a little outside this range.
