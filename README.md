# spark_airtravel_exercise
This is a PySpark project to analyze air transit data for 2007. This script processes large volumes of flight data, cleans it by handling missing values, and performs various analyses to gather insights about the airline industry.


Getting Started
This project is built using PySpark. To get started, you'll need to install PySpark on your local machine. You can follow the instructions provided here.

The code is designed to run on a cluster and handles large data efficiently using Spark's distributed computing capabilities.

Data
The script requires an input data file named air_transit_2007.csv. This CSV file should contain flight data for the year 2007. Here is a brief description of what the columns in the dataset represent:

Scheduled Departure Time
Destination Airport
Month
Day
Total number of flights
Flight numbers
Arrival and Departure Delays
Air Time
Carrier information
Tail Number
etc.
Make sure to place the air_transit_2007.csv file in the same directory as the script for it to run correctly.

Usage
To execute the script, simply run the Python file with your desired interpreter. Here's an example if you're running it from the command line:

Analysis Questions
The script addresses several questions about the air transit data:

How many total records are there in the dataset?
How many flights per month were there?
What planes (represented by unique tail numbers) had the highest number of flights?
What planes had the most total flight time?
What was the busiest airport each month?
Which airline had the highest average delay of each type in March 2007?
What were the median, mean, and mode of various columns for the flights in the third week of 2007?
How many combinations of flights were possible with the same carrier and various time constraints?
What were the flight statuses?
Please refer to the code comments for detailed explanations of how each question is addressed.

Testing
The script also contains commented-out test code that counts the number of 'NA' values in each column. This is useful for understanding the quality of the data.
