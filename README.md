# US Bikeshare Data Explorer

Interactive Python command-line project for exploring US bikeshare data by city, month, and day of week. The script loads trip data for Chicago, New York City, and Washington, then prints insights about travel times, popular stations, trip duration, and rider demographics.

## Overview

This project helps users explore bikeshare usage patterns through a simple terminal-based workflow. After choosing a city and applying optional month and day filters, the program calculates summary statistics from the selected dataset and can also display raw data in batches.

## Features

- Filter bikeshare data by city, month, and day
- View the most common month, day, and start hour
- View the most popular start station, end station, and trip combination
- View total and average trip duration
- View user type counts plus gender and birth year statistics when available
- Preview raw data directly in the terminal

## Tech Stack

- Python
- pandas
- NumPy

## Dataset

The project expects these CSV files to be available in the same folder as `Bikeshare.py`:

- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

If you prefer not to publish the dataset files to GitHub, you can keep them locally and mention in the repository that users should place the CSV files in the project root before running the program.

## Project Structure

```text
us-bikeshare-data-explorer/
├── Bikeshare.py
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

1. Make sure Python 3 is installed.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

```bash
python Bikeshare.py
```

Then enter a city, month, and day when prompted.

## Example Interaction

```text
Hello! Let's explore some US bikeshare data!
ENTER THE CITY: chicago
ENTER MONTH: march
ENTER DAY : friday
```

The script will then display statistics based on the selected filters.

## Future Improvements

- Improve input validation and error handling
- Refactor the script into smaller reusable functions or modules
- Add charts or notebook-based visualizations
- Add tests for core functions
- Improve raw data pagination and terminal formatting

## Author

Mustafa
