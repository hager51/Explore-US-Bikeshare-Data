# Explore US Bikeshare Data
This project aims to use Python programming language to explore data related to bike share systems for three major cities in the United States - Chicago, New York City, and Washington. The project will require the user to write code that imports the data and answers interesting questions about it by computing descriptive statistics. Additionally, a script will be written to create an interactive experience in the terminal to present these statistics.

## Software Requirements
To complete this project, the following software requirements apply:

- Python 3
- NumPy
- pandas, installed using Anaconda
- A text editor, like Sublime or Atom.
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

## Files used in the Project
The following files will be used in the project:

- **'chicago.csv'**
- **'new_york_city.csv'**
- **'washington.csv'**
- **'bikeshare.py'**

## How to Run the Script
To run the script, open a terminal window and navigate to the project directory. Run the following command:

**'python bikeshare.py'**

## The Code
The code is written in Python 3 and contains the following functions:

- **'get_filters()'**: Asks the user to specify a city, month, and day to analyze and returns the selected data.
- **'load_data(city, month, day)'**: Loads data for the specified city and filters by month and day if applicable. Returns a Pandas DataFrame containing city data filtered by month and day.
- **'time_stats(df)'**: Displays statistics on the most frequent times of travel, such as the most common month, day, and start hour.
- **'station_stats(df)'**: Displays statistics on the most popular stations and trips.
- **'trip_duration_stats(df)'**: Displays statistics on the total and average trip duration.
- **'user_stats(df)'**: Displays statistics on bikeshare users, such as user type, gender, and birth year.

The functions above are called in the main function **'main()'**, which presents an interactive experience to the user by asking questions and presenting the results based on the user's choices.
