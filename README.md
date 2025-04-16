# Radar Chart in R

This project gathers soccer player data from RBref.com using worldfootballR. We clean and manipulate the data to then create a function that makes a radar chart and a simple overall metric. 

# Files
- 'Radar_Chart.Rmd': main visualization file
- 'Radar_Chart.html': Markdown document

# Highlights
- Scraping data using worldfootballR
- Cleaning data to filter 3,000 observations to 300, by only looking at midfielders who have played >10 games and singling out specific statistics of interest
- Manipulating data by changing all stats to per 90, then using rank() to turn data into percentiles.
- Visualize data to show the strengths and weaknesses of a midfield (2-4 midfielders together)
- Create a simple metric that averages the highest percentile in each category, showing the overall quality of the midfield
