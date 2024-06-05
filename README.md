# Workout Tracker

The Workout Tracker is a Python script that automates exercise tracking and logs the data into a Google Sheets spreadsheet using the Sheety API. It leverages the Nutritionix API to convert natural language exercise descriptions into exercise details (duration and calories burned).

## Features
- **Natural Language Input**: Users can describe their exercises naturally (e.g., "30 minutes of jogging").
- **Nutritionix Integration**: Retrieves exercise details (duration and calories burned) based on user input.
- **Sheety Integration**: Logs exercise data (date, time, exercise type, duration, and calories) into a Google Sheets spreadsheet.

## How It Works
1. The user provides a natural language description of their exercise (e.g., "30 minutes of jogging").
2. The script queries the Nutritionix API to get exercise details.
3. It records the exercise data (including date and time) in a Google Sheets spreadsheet using the Sheety API.

## Setup
1. Set up your Nutritionix and Sheety API credentials.
2. Install the required Python libraries (requests, datetime).
3. Run the script and follow the prompts to input your exercises.

## Contributions
Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

The Workout Tracker simplifies exercise tracking, making it easy to maintain a fitness log. Whether you're a fitness enthusiast or just starting your fitness journey, this tool can help you stay on track!
