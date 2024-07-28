# Netflix-Dashboard-Power-BI

## Overview

This project involves developing an interactive dashboard using Power BI to analyze and visualize Netflix shows and movies. The dashboard provides insights into genres, countries of production, release years, and ratings of titles available on Netflix.

## Dataset

The dataset used for this project is `netflix_titles.csv`, which contains information about Netflix shows and movies. The dataset includes the following columns:
- **show_id**: Unique ID for each show.
- **type**: Type of show (Movie or TV Show).
- **title**: Title of the show.
- **director**: Director of the show (if available).
- **cast**: Main cast of the show.
- **country**: Country where the show was produced.
- **date_added**: Date when the show was added to Netflix.
- **release_year**: Year the show was released.
- **rating**: TV rating of the show.
- **duration**: Duration of the show (minutes for movies, seasons for TV shows).
- **listed_in**: Genres the show is listed under.
- **description**: Short description of the show.

## Dashboard Features

### Visualizations
1. **Top 10 Genres by Count of Shows**:
   - Displays the top 10 genres based on the number of shows.
   - Includes a date range slicer to filter the data based on the date added to Netflix.
   
2. **Shows by Country**:
   - Visualizes the distribution of shows by country.
   - Highlights the top countries producing Netflix content.
   
3. **Release Year Distribution**:
   - Shows the number of shows released each year.
   - Helps identify trends in content release over the years.
   
4. **Rating Distribution**:
   - Displays the distribution of shows based on their TV rating.
   - Useful for understanding the content rating spread on Netflix.

### Measures and Calculations
- **Genre Count**: Calculates the count of shows for each genre.
- **Rank of Genres**: Ranks the genres based on the count of shows.
- **Top 10 Genres Filter**: Filters the data to include only the top 10 genres.

## Key Insights

- **Genre Popularity**: Identifies the most popular genres on Netflix.
- **Country Contributions**: Highlights the countries contributing the most content to Netflix.
- **Content Trends**: Shows trends in content release over the years.
- **Rating Analysis**: Provides an overview of the content rating distribution on Netflix.

## How to Run the Project

1. **Download the Dataset**:
   - Download the `netflix_titles.csv` file from the repository.
   
2. **Open the Power BI File**:
   - Open the `Netflix Dashboard.pbix` file in Power BI Desktop.

3. **Load the Data**:
   - Ensure the dataset is correctly loaded into Power BI.
   
4. **Interact with the Dashboard**:
   - Use the interactive features of the dashboard to explore the data.

## Conclusion

This Power BI project provides a comprehensive analysis of Netflix shows and movies, offering valuable insights into the content available on the platform. The interactive dashboard allows users to explore the data and gain a deeper understanding of Netflix's offerings.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
