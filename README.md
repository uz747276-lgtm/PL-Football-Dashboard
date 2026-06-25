# Premier League Football Dashboard

## Overview
A data analytics dashboard that fetches live Premier League data using the football-data.org API and performs statistical analysis with Pandas and NumPy. The project demonstrates API integration, data manipulation, and insights extraction from real football data.

## Features
- **Standings**: Top 5 teams ranked by points
- **Top Scorers**: Top 5 goal scorers across the league
- **Best Goal Differential**: Team with the largest goal difference
- **Home Win Percentage**: Win rate for home teams across all matches
- **Average Goals Per Match**: League-wide scoring average
- **CSV Exports**: All analysis results saved to CSV files for further use

## Tech Stack
- **Python 3.x**
- **Pandas**: Data manipulation, groupby operations, aggregations
- **NumPy**: Numerical calculations and array operations
- **Requests**: HTTP requests to football-data.org API
- **football-data.org API**: Live Premier League data

## How to Run

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Installation
1. Clone or download this repository
2. Install dependencies:
```bash
   pip install pandas numpy requests
```

### Getting an API Key
1. Go to https://www.football-data.org/client/register
2. Create a free account
3. Copy your API key from the dashboard

### Running the Project
1. Open the script file and replace `YOUR_API_KEY` with your actual key
2. Run the script:
```bash
   python pl_dashboard.py
```
3. Check the output folder for generated CSV files

## Key Insights (Example Results)
- **Top Team**: Manchester City (87 points)
- **Top Scorer**: [Player Name] (20 goals)
- **Home Win %**: 52.3%
- **Avg Goals/Match**: 2.84

## Project Learnings
- API data retrieval and handling JSON responses
- Data cleaning with Pandas (missing values, duplicates)
- DataFrame operations (loc, iloc, groupby, aggregation)
- Merging and concatenating datasets
- Exporting analysis results to CSV

## Next Steps
- **Player & Ball Tracking**: Computer Vision project using YOLOv8 to detect and track player positions and ball movement in match footage
- **Advanced Analytics**: Predictive modeling for match outcomes
- **Interactive Dashboard**: Web-based visualization with Flask/Streamlit

## Author
Usama | AI + Sports

## License
MIT (or specify if needed)
