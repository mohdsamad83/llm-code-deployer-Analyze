# Project Title
Data Processing Application

## Summary
This application loads CSV data, processes it to compute revenue statistics, and presents the results on the web page.

## Setup
1. Ensure you have a web server to host this application.
2. Place the `data.csv` file in the same directory as this file.

## Usage
- Click the "Load and Process Data" button to retrieve and compute the data.
- The results will be displayed in a formatted JSON structure.

## Code Explanation
- The application fetches a CSV file and processes the data using JavaScript.
- It calculates row counts, distinct regions, and top products by revenue.
- A moving average of the last 7 days' revenue per region is also computed.

## License
This project is licensed under the MIT License.