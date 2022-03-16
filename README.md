# GDAC2022
The University of Utah Game Day Analytics Challenge is a competition held every year after the superbowl and is an opportunity for students to practice their data analytics capabilities by using twitter to decide which ads during the superbowl were most effective, and present their findings to employers in Utah.  I competed with two other students in 2022. We were given a dataset of just over two million tweets about ads, and we were esentially free to do what we wanted with the data.  My portion of the project work was focused on cleaning and preparing the data.  I spent time in the days leading up to getting the dataset looking at last year's data and familiarizing myself with the data dictionary and meaning of the included variables.  I wrote preliminary scripts for dropping irrelevant columns, formatting data in the columns, and extracting relevant information.  The data was given to us in several excel spreadsheets, so my first script, xlConv, breaks up each excel sheet into its own pandas dataframe and saves it as a pickle.  The next script, pklLoop, grabs each pickle and drops irelevant columns, formats the text, gives it a column with the name of the ad, and saves it as a csv.  Then all the csvs are combined into a matster csv.  the adAnalysis script is used for opening the data and and extracting insights.  Most of the data visualiation and sorting was done using domo, and I took the data snippets and created the final presentation, using Microsoft Office.
