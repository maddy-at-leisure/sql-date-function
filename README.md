# sql-date-function
A simple SQL function to convert any type of date like varchar to US standard date (MM-DD-YYYY)

This code matches to 26 date like variations using REGEX and SQL to convert to it into DATE. 

### Each REGEX Variations and example:
  
##### '^[0-9]{2,4}-[0-9]{1,2}-[0-9]{1,2}'         ex. 2020-12-2
##### '^[A-Za-z]{3} +[0-9]{1,2} *, *[0-9]{2,4}$'  ex.Jul 2, 20
##### '^[0-9]{2}/[0-9]{2}/[0-9]{2,4}$'            ex. 20/09/1889
##### '^[0-9]{1,2}-[0-9]{1,2}-[0-9]{2,4}$'        ex.2-12-2020
##### '^[A-Za-z]{3} +[0-9]{1,2} * *[0-9]{2,4}$'   ex. Jun 09, 2020
##### '^[0-9]{4}.[0-9]{1,2}.[0-9]{1,2}$'          ex. 2020.02.09
