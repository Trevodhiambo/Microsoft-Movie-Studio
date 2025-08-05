
# Exploratory Data Analysis for Microsoft's New Movie Studio

# Overview
This project explores movie industry data to help Microsoft decide what types of films its new movie studio should focus on.

# Business Problem
Microsoft wants to join the competitive original content space but lacks movie production experience. The goal is to identify **what types of movies perform best at the box office** and **what characteristics correlate with success** to inform the strategy that should be adopted

# Datasets Used
- `imdb.title.basics.csv` – movie metadata (title, genres, year, runtime)  
- `imdb.title.ratings.csv` – IMDb ratings and vote counts  
- `bom.movie_gross.csv` – box office data (studio, gross revenue)

# Data Cleaning & Merging
- Filtered only movies
- Dropped null or incomplete entries 
- Converted gross fields to numeric
- Merged datasets on `tconst` (IMDB ID) and `title`

# Exploratory Data Analysis
Explored relationships between genre, rating, runtime and box office gross.
Visualizations include:
- Top 10 Genres      
- Distribution of IMDb Ratings
- Distribution of Movie Runtime 
- Domestic Gross vs Genre
- Runtime vs Domestic Gross
- IMDb Rating vs Domestic Gross  
- Correlation Matrix  
- Top Studios by Average Gross  

# Key Insights
Action and Adventure genres have the **highest average revenue** Focus on producing blockbuster films
Movies between **90–120 minutes** perform better
Many top movies come from a few **consistent studios** Microsoft should aim to build or partner with trusted production houses

# Final Recommendations

1. **Invest in Action and Adventure** for high-grossing potential.
2. **Target runtimes around 90–120 minutes** to maintain audience engagement.
3. Top movies come from a few**Consistent studios** aim to build or partner with trusted production houses.

