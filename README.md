# NBA-Statistics-Retrieval-Script

This Python script allows you to retrieve NBA statistics and game scores using the NBA API. It provides information about team statistics and the current scores of NBA games. The script uses the requests library to make API requests and pprint for pretty-printing the results.

Prerequisites
Before running this script, you need to have Python installed on your system. You can download Python from python.org.

You also need to install the requests library, which can be installed using pip:

bash
Copy code
pip install requests
Usage
Clone or download this repository to your local machine.

Open a terminal or command prompt and navigate to the directory containing the script.

Run the script using Python:

bash
Copy code
python nba_stats.py
Features
1. get_scoreboard()
This function retrieves and displays the current scores of NBA games. It fetches data from the NBA API and prints the following information for each game:

Home team vs. Away team
Current score
Game clock and period
2. get_stats()
This function retrieves and displays NBA team statistics, specifically the average points per game (PPG) for each team. It fetches data from the NBA API and prints the following information for each team:

Team name
Team nickname
Average PPG
Customization
You can further customize this script to retrieve other types of data from the NBA API by modifying the functions and endpoints used. Refer to the NBA API documentation for available endpoints and data structures.

Disclaimer
This script relies on the NBA API, and its functionality may be subject to change or require API key authentication. Make sure to check the NBA API documentation for any updates or changes.

License
This script is provided under the MIT License. Feel free to modify and use it according to your needs.

Feel free to include any additional information or instructions specific to your use case. This README provides a basic overview of the script's purpose and usage.
