# Historic NBA Drafting, Game, and Player Analysis

## Project Overview
This repository contains code for analyzing NBA draft history, game statistics, and player salary data using SQLite, Pandas, and Plotly. It provides interactive visualizations and statistical insights spanning 1946 to 2020.

## Features
- **Draft Trends**: Year-by-year player draft counts and team-wise drafting patterns.
- **Source Breakdown**: Distribution of drafted players by origin (college, international, etc.).
- **Game & Season Analysis**: Trends in number of teams/games per season; home vs. away win percentages.
- **Performance Metrics**: Median free-throw and three-point percentages by location (home/away).
- **Salary Insights**: Top-paid players and highest-paying teams for the 2020–21 season.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Chessman08/Historic_NBA_Player_Analysis.git
   cd Historic_NBA_Player_Analysis
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
   pip install -r requirements.txt
   ```
## Usage

1. Place the basketball.sqlite database file under the root directory or update db_path in the script.
2. Run the analysis script:
   ```bash
   python Historic_NBA_Player_Analysis.ipynb
   ```
3. Visualizations will open in your default web browser.

## File Structure

```bash
├── Historic_NBA_Player_Analysis.ipynb           # Main script containing SQL queries and Plotly visualizations
├── basketball.sqlite                            # SQLite database (not included)
├── README.md
├── .gitignore                                   # Files and directories to ignore in Git
└── requirements.txt                             # Python dependencies
```

## Technologies

   Python 3.x

   SQLite for data storage and querying

   Pandas for data manipulation

   Plotly for interactive charts

## License

MIT License. See LICENSE for details.
