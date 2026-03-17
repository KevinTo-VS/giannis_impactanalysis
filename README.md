# Giannis Antetokounmpo Impact Analysis (2025–26 Season)

## Overview
This project analyzes Giannis Antetokounmpo’s on-court impact during the 2025–26 NBA season using Python and Tableau. The analysis focuses on how Giannis compares to other high-usage NBA players in terms of offensive and defensive efficiency, with an emphasis on identifying elite two-way performance.


## Objective
The goal of this project is to assess Giannis Antetokounmpo’s impact relative to other high-usage NBA players and determine whether his two-way performance justifies targeting him as a franchise-level acquisition in a team-building context.

This mirrors the type of evaluation NBA front offices perform when deciding whether to pursue high-impact players via trade or free agency.

## Methodology
To ensure meaningful comparisons, the dataset was filtered to include only primary contributors:

- Minimum **20 minutes per game (MPG)**
- Minimum **20% usage rate (USG%)**

This removes low-impact role players and focuses the analysis on players with significant offensive responsibility.

Key metrics used:

- **Offensive Rating (O Rtg)** — measures offensive efficiency  
- **Defensive Rating (D Rtg)** — measures defensive impact  
- **Usage Rate (USG%)** — identifies offensive workload  
- **P+R+A and PRA Rank** — provides production context  

Players performing above league average in both offensive and defensive rating were classified as **elite two-way players**.


## Tools Used
- Python  
- Pandas  
- Jupyter Notebook  
- Tableau  

## Project Workflow
1. Loaded and cleaned 2025–26 NBA player data using Python  
2. Applied filters for MPG and usage to isolate top contributors  
3. Exported processed dataset to CSV  
4. Built interactive Tableau dashboards to visualize player impact  






