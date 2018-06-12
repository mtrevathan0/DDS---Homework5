# Codebook DDS---Homework5

Description
This is a repository created for MSDS 6306: Doing Data Science Unit 05 Homework. Contained is raw data involving the occurrences of child names, male and female, in 2015 and 2016. The purpose of the assignment was to clean up the data for each year, combine them and sort them by occurrence. 

Objects created for this assignment
df - Data frame created from the yob2016.csv file. This contained raw data for children's names used in 2016

y2016 - Created to remove an unwanted value, "Fionayyy," from the df data frame

y2015 - Data frame created to import the data from the yob2015.csv file

final - The merged data from y2016 and y2015

final2 - Data frame with the "Totals" column added containing the combination between the two years

final3 - final2 data frame in decending order

finalgirl - data frame, in decending order, with only the females in final2

Toptengirls.csv - csv created with the top 10 girls in terms of number from the finalgirl data frame


