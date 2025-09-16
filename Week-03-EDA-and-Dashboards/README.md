# MovieLens Data Analysis Dashboard

## Overview
This project analyzes movie ratings from the MovieLens 200k dataset to answer key analytical questions about movie preferences and ratings patterns. The analysis is implemented as a comprehensive Jupyter notebook with professional visualizations and insights.

## Files
- `movie_ratings_analysis.ipynb` - Main analysis notebook
- `data/movie_ratings.csv` - Dataset containing movie ratings and metadata
- `README.md` - This file

## Requirements
To run this analysis, you need the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn

## Installation
Install the required packages using pip:
```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run
1. Ensure you have all required packages installed
2. Open the Jupyter notebook: `movie_ratings_analysis.ipynb`
3. Run all cells in order (Cell → Run All)
4. The notebook will generate visualizations and insights for each analytical question

## Analysis Questions Answered

### 1. Genre Breakdown
- What's the breakdown of genres for the movies that were rated?
- **Finding**: Drama dominates with over 20% of all ratings, followed by Comedy and Action

### 2. Genre Satisfaction
- Which genres have the highest viewer satisfaction (highest ratings)?
- **Finding**: Film-Noir has the highest average rating (4.18), followed by Documentary and War genres

### 3. Temporal Trends
- How does mean rating change across movie release years?
- **Finding**: Slight positive trend over time, with newer movies receiving slightly higher ratings

### 4. Top Movies
- What are the 5 best-rated movies that have at least 50 ratings? At least 150 ratings?
- **Finding**: Classic films like Shawshank Redemption and The Godfather consistently rank highest

## Key Insights
- **Drama** is the most popular genre, representing over 20% of all ratings
- **Film-Noir** and **Documentary** genres show the highest viewer satisfaction
- There's a **positive correlation** between movie release year and average rating
- **Classic films** from the 1970s-1990s dominate the top-rated lists
- Movies with more ratings tend to have slightly lower average ratings (diverse opinions)

## Visualization Features
- Professional styling with seaborn and matplotlib
- Color-coded charts for better readability
- Statistical annotations and trend lines
- Comprehensive insights and recommendations

## Author
Created as part of Week 3 Dashboard Exercise for Data Science course.