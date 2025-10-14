# Trip Advisor Mock Dashboard

## Overview
This Tableau project visualizes mock hotel and user review data modeled after TripAdvisor.  
The dashboard summarizes hotel amenities, user engagement, regional travel patterns, and seasonal behavior. It highlights how different hotel services and locations influence guest activity and overall popularity.

## Dataset
**File:** `review_data.csv`

The dataset contains simulated hotel and user review information designed to mimic TripAdvisor metrics.  
It includes:
- Hotel name, star rating, and total number of rooms  
- Available amenities (Free WiFi, Pool, Gym, Club, Basketball Court)  
- User count per region and per travel season  
- Aggregated summaries for hotel star ratings and top properties  

The data was cleaned and structured for Tableau to provide insights into travel trends and accommodation preferences.

## Dashboard Features

### Hotels by Additional Services
Displays which amenities are most commonly offered, allowing quick comparison of hotel features such as Free WiFi, gym access, and pool availability.

### Total Users by Continent
Visualizes the distribution of users across continents, showing that North America has the highest number of users.

### Total Hotels by Stars
Highlights the number of hotels by star category, with 5-star hotels being the most frequent.

### Users by Period of Stay
Shows user activity by travel season (Dec–Feb, Mar–May, Jun–Aug, Sep–Nov), identifying the busiest periods.

### Top 10 Hotels by Total Rooms
Ranks the largest hotels by room count, including major Las Vegas resorts like Bellagio, Caesars Palace, and The Venetian.

## Key Insights
- North America leads in total user interactions, followed by Europe and Asia.  
- Most users stay in 4- to 5-star hotels, suggesting a preference for luxury accommodations.  
- Hotel amenities such as Free WiFi and pool access are dominant among high-rated properties.  
- Travel activity peaks during March–May, reflecting major travel and leisure periods.  

## Repository Structure
| File Name | Description |
|------------|--------------|
| **review_data.csv** | Raw dataset containing mock TripAdvisor hotel and user review data used for visualization. |
| **review_data.hyper** | Tableau extract file generated from the CSV for optimized performance. |
| **Trip Advisor Dashboard.twb** | Tableau workbook containing all visualization sheets and dashboard layout. |
| **Trip Advisor Dashboard.twbx** | Packaged Tableau workbook with embedded data and design for easy sharing. |
