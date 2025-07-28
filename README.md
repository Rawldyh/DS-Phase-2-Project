#  Box Office Movie Studio Project

## Overview
This project explores what types of films perform best at the box office to help guide a new movie studio's content strategy. We use real-world data from Box Office Mojo, IMDb, and TMDB to uncover trends in revenue, genre, quality, and popularity.

---

##  Business Understanding

### Stakeholder
The executive team of a new film production studio looking to enter the market with data-informed decisions.

### Key Business Questions
1. What genres make the most money at the box office?
2. Do better-rated movies perform better financially?
3. Can pre-release popularity help predict a movie's success?

---

##  Data Understanding & Analysis

### Sources
- **Box Office Mojo:** Revenue data
- **IMDb:** Genre, user rating, vote count
- **TMDB:** Popularity score, vote average

All datasets were merged using `title` and `release_year` to create a unified movie-level dataset.

### Key Visualizations

####  1. Average Revenue by Genre
Genres like Action, Adventure, and Animation bring in the highest average revenue.
![Genre Revenue](images/genre_revenue.png)

####  2. Revenue vs IMDb Rating
Higher IMDb ratings are associated with higher revenue.
![Revenue vs IMDb](images/imdb_rating_vs_revenue.png)

####  3. Revenue vs TMDB Popularity
Movies with higher popularity scores on TMDB tend to make more money.
![Popularity vs Revenue](images/tmdb_popularity_vs_revenue.png)

---

##  Conclusion

- **Go big on Action, Adventure, and Animation**: These genres consistently lead in revenue.
- **Invest in quality**: Higher ratings yield better financial performance.
- **Use popularity as a predictor**: TMDB engagement is a leading indicator of box office success.

---

## Next Steps

- Add production budget data to assess ROI
- Analyze seasonal release timing
- Include international box office for global insights
- Develop a pre-greenlight scoring system for new projects

---

## Repository Structure

```
├── data/                      # Raw and processed data files
├── images/                    # Visualizations used in the README and presentation
├── Final.ipynb               # Final Jupyter Notebook
├── presentation.pdf          # Non-technical slide deck
├── box_office_recommendations_presentation.pptx
├── README.md                 # Project documentation
```

---

## Contact

Created by: *Rolddy SURPRIS*  
Email: rolddysurpris@gmail.com  
