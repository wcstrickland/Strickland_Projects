# [Project 1: Call Center performance analysis and visualization](https://github.com/wcstrickland/call_center)
Business Case: A call center supervisor is provided an excel spreadsheet with performance metrics generated by call monitoring software and desires a format with improved insight.

Reformatted [original](images/call_raw_xl.png) excel workbook designed for rudimentary analysis.
Then used Python to reorganize data and calculate new fields specific to business case,
and generated [statistical analysis](images/jupyter_img.png) of performance by group. 
Finally, exported data to tableau and created [interactive dashboard](https://public.tableau.com/shared/KXPPY74GJ?:display_count=y&:origin=viz_share_link) for the end user.

![alt text](https://media.giphy.com/media/LoZyUPDg7HZu2sgd5I/giphy.gif)


# [Project 2: Convert CSV file to SQL insert statement](https://github.com/wcstrickland/call_center)
A python script that converts an existing CSV file to an SQL insert statement

The program automatically determines column names by reading the first row of the CSV file, attempts to resolve any conflicts with SQL compatability such as whitespace,
or prohibited symbols, and then generates the values in SQL format. 
The reulting text file allows the user to cast data types, assign keys, or auto-incrementation as well as resolve any reserved word conflicts. 

The goal of the project was to provide a tool to quickly migrate files to a SQL database in instances where an import wizard was unavailable or would bog down creating large
insert satements. 

![alt text](https://media.giphy.com/media/cYXoBXI8JRL4yeJhpp/giphy.gif)


