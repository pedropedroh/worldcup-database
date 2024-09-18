# World Cup Database

This project includes scripts for managing and querying a PostgreSQL database that contains data on World Cup games and teams. The database provides insights into match results, team performances, and other statistics related to the World Cup tournaments.

## Project Overview

The project consists of several key files:

1. **games.csv**: Contains data on World Cup games, including teams, scores, and match details.
2. **insert_data.sh**: A script to import data from `games.csv` into the PostgreSQL database.
3. **queries.sh**: A script that runs various queries to analyze the data in the database.
4. **worldcup.sql**: SQL script for setting up the database schema and initial data.
5. **expected_output.txt**: Contains the expected output from running the query script.

## Files

### 1. `games.csv`

This CSV file includes detailed records of World Cup games, including information such as the year, round, winning team, opponent, and the number of goals scored by each team.

### 2. `insert_data.sh`

This script processes the `games.csv` file and inserts the game data into the `games` and `teams` tables in the PostgreSQL database.

#### Usage

To run the data insertion script, use the following command:

```bash
bash insert_data.sh
