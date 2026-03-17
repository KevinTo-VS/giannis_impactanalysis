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
2. Engineered features such as PRA Rank  
3. Applied filters for MPG and usage to isolate top contributors  
4. Exported processed dataset to CSV  
5. Built interactive Tableau dashboards to visualize player impact  



## Key Findings

- Giannis ranks among a small group of players above league average in both offensive and defensive rating  
- Many high-usage players provide elite offense but fall short defensively  
- Giannis maintains strong performance on both ends, making him a rare two-way player  
- Comparable elite players identified include Jokic, Shai Gilgeous-Alexander, and Wembanyama  



## Conclusion

Giannis Antetokounmpo demonstrates a rare combination of high offensive responsibility and strong defensive performance. Unlike many star players who trade off defense for offensive output, Giannis remains impactful on both ends of the floor.

From a team-building perspective, this level of two-way production strongly supports the case for targeting him as a franchise-level acquisition, as he provides value without requiring defensive compensation elsewhere on the roster.


