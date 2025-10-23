# Formula 1 Performance Dashboard (1950–2023)

This project presents an interactive Power BI dashboard analyzing Formula 1 racing performance trends across teams, drivers, and circuits from 1950 to 2023.  
It offers a visually rich, data-driven overview of race wins, podiums, points, and championship outcomes by year, team, and location.

---

## Project Overview
The dashboard explores over seven decades of Formula 1 data to identify dominant teams, successful drivers, and iconic racing venues.  
It allows users to interactively filter by year, team, or driver, updating all visuals dynamically to reveal historical and modern performance trends.

---

### Access the Dashboard
Explore the full interactive version here:  
[View on Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiMTFiZDUxNjItNjQxNC00ZTUzLTliNDYtZmNlYTM4ZjU4Y2JkIiwidCI6ImFjMzUyZjliLWViNjMtNGNhMi05Y2Y5LWY0YzQwMDQ3Y2VmZiIsImMiOjZ9)

---

## Dataset Information

| Attribute | Description |
|------------|-------------|
| **Source** | Kaggle — [Formula 1 World Championship (1950–2020)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020) *(continuously updated by community beyond 2020)* |
| **Years** | 1950–2023 (this dataset is updated every year) |
| **Key Tables Used** | `races.csv`, `results.csv`, `constructors.csv`, `drivers.csv`, `circuits.csv`, `pit_stops.csv` |
| **Main Fields** | Race name, location, year, team (constructor), driver, race points, podium finishes, wins, championship results |
| **Update Note** | Dataset last cleaned and updated in 2023; latest Kaggle version continues to add new race data annually |

---

## Repository Structure

| File | Description |
|------|--------------|
| `F1_Dashboard.pdf` | Static exported version of the dashboard for preview or offline viewing |
| `README.md` | Repository documentation detailing project structure and insights |

---

## Dashboard Overview

### Key Visuals and Interactivity
- **Race Wins by Decade (Top 5 Teams):** Sunburst visualization comparing constructors’ dominance across eras  
- **Races by Location:** Donut and geographic map highlighting global distribution of F1 circuits  
- **Sum of Race Wins by Team:** Comparative bar chart showcasing cumulative victories per constructor  
- **Total Points Per Year:** Historical line chart showing evolution of total points and competitiveness  
- **Key Metrics (KPIs):** Cards displaying total podiums, race wins, championships, and average win percentage  
- **Dynamic Filters:** Year, Team, and Driver slicers that update all charts simultaneously  

---

## Insights
- **Ferrari, McLaren, and Mercedes** lead in total wins and podium finishes over the decades.  
- **Red Bull’s dominance post-2010** reshaped modern Formula 1 competitiveness.  
- The most raced circuits include Monza, Monte-Carlo, and Silverstone, representing the sport’s heritage.  
- The steady increase in points per season reflects evolving race formats and scoring systems.  
- Interactive filtering allows analysis of specific eras, teams, and driver performance trajectories.

---

## License
This project uses publicly available data under the Kaggle dataset license (CC BY-NC 4.0).  
The Power BI dashboard and visualizations were created for educational and analytical demonstration purposes.
