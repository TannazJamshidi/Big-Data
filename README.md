# Big-Data
Files bikes_RDD and bikes_DF consider the occupancy of bike stations, where users can both pick up and drop off bikes in two different ways(data frame structure and RDD structure). The objective is to identify the most "critical" time slots (day of the week and hour) for each station.
The historical data is stored in register.csv, which includes information about the number of slots used and free for approximately 3000 stations spanning from May 2008 to September 2008.
station.csv provides descriptions of the stations. 


File flights_graph utilizes the GraphFrames Spark library, utilizing its DataFrame API, to analyze a dataset containing information about flight connections and airports worldwide. Here's an overview of the dataset:
/data/students/bigdata_internet/lab5/airports.csv: This file contains detailed information about airports globally, with each line representing one airport entry.
/data/students/bigdata_internet/lab5/airlines.csv: This file offers additional insights into each airline's operations.
/data/students/bigdata_internet/lab5/routes.csv: This file lists the flight routes operated by each airline between two airports.
