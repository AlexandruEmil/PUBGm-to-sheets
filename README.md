# PUBGm-to-sheets

### PUBG Match stats to Google Sheets

This script collects match stats data from a specified API endpoint for a PlayerUnknown's Battlegrounds (PUBGmobile) match, and writes the data to a Google Sheets document using the Google Sheets API.

### Flowchart

![252616513-2c5e9c50-a62c-4b3a-a92d-a77db6f86174](https://github.com/user-attachments/assets/d05aa5b8-3866-464f-b8b9-25a67aa28bbe)

# Requirements:
```
requests library
gspread library
Google API credentials JSON file
A Google Sheets document to write the data to
```
# Installation:
```
Clone or download the repository to your local machine
Install the required libraries by running pip install -r requirements.txt in the command line
Replace the url variable with the API endpoint for the desired PUBG match
Replace the PATH TO FILE in the creds = ServiceAccountCredentials.from_json_keyfile_name('PATH TO FILE', scope) line with the path to your Google API credentials JSON file

Replace the NAME OF SHEET in the sheet = gc.open("NAME OF SHEET").sheet1 line with the name of your Google Sheets document
```
# Usage
Run the script in the command line using ```python pubg_match_stats.py```.

