Joining Files
--------------------------------

This file contains a lot of information, but we may want to add more information. For example if we had a file with information about each country (population, capital city, etc), we could join that information with our Olympics data, to get a single file with all information in every row.

For example, if we would like to be able to group by continent, to e.g. count athletes, medals etc per continent, we will have to add a continent column to our file. To do this we would need a second file that maps each country to the corresponding continent. This is what we will do in the next hands-on section.

We obtained country information data from DataHub. More information about this file can be found in the description there. It has 56 columns with a wide variety of data about each country (from country codes, to capital city, languages spoken, etc

I would now like to take my 2008 Olympics dataset as the basis, and add columns to every row of this file with some information about the country. In order to join, I will needto have one column that is shared between the two files, on which I can match. The NOC column is perfect for this because it is a defined standard. Both files also contain a column with the country name in it, which is also a possible candidate to use for joining, but because it is less standardised, it is safer to use the NOC column. For example, if one file uses “Netherlands”, while the other uses “The Netherlands” to indicate the same country, the joining will fail for these rows. So always make sure the columns are join on are compatible!
