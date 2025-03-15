# FIFA 22 Player Foot Preference Analysis

## Overview
This project analyzes FIFA 22 player data to examine foot preference (left vs. right) across different dimensions such as position, nationality, league, and club. The analysis utilizes Python with `pandas`, `seaborn`, and `matplotlib` for data processing and visualization.

## Features
- **Data Cleaning & Preprocessing**
  - Reads player data from a CSV file (`fifa_players_22.csv`).
  - Filters relevant columns and ensures appropriate data types.
  - Extracts primary player positions and excludes goalkeepers and full-backs.

- **Foot Preference Analysis**
  - Calculates and visualizes the percentage of left vs. right-footed players.
  - Analyzes average player ratings based on foot preference across different positions.

- **Nation-wise Analysis**
  - Identifies top 10 footballing nations by player count.
  - Determines left or right-footed dominance in each nation using a heatmap.

- **League-wise Analysis**
  - Compares average overall ratings of left vs. right-footed players across leagues.
  - Identifies leagues with left-footed or right-footed dominance.

- **Club-wise Analysis**
  - Filters major European leagues (Premier League, La Liga, Bundesliga, Serie A, Ligue 1).
  - Identifies top 10 clubs favoring left-footed players.
  - Identifies top 10 clubs favoring right-footed players.

## Dataset
- **Source:** FIFA 22 Player Dataset
- **Columns Used:** `short_name`, `nationality_name`, `preferred_foot`, `player_positions`, `league_name`, `club_name`, `overall`

## Visualizations
The project generates insightful visualizations, including:
- Bar plots showing left vs. right-footed player distribution.
- Point plots analyzing player ability by position and preferred foot.
- Heatmaps for nationality-wise left vs. right-footed dominance.
- Count plots for league-wide left/right-footed player preferences.
- Bar charts showcasing club-specific trends.


