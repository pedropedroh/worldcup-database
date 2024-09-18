# World Cup Database

This project includes scripts for managing and querying a PostgreSQL database that contains data on World Cup games and teams. The database provides insights into match results, team performances, and other statistics related to the World Cup tournaments.

## Project Overview

The project consists of two main scripts:

1. **Data Insertion Script**: Imports data from a CSV file into the PostgreSQL database.
2. **Query Script**: Executes various queries to analyze the data within the database.

## Scripts

### 1. Data Insertion Script (`insert_data.sh`)

This script processes a CSV file named `games.csv` and inserts the game data into the `games` and `teams` tables in the PostgreSQL database.

#### Usage

To run the data insertion script, use the following command:

```bash
bash insert_data.sh
