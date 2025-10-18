# Netflix Data Analysis

A data analysis project exploring **Netflix’s global content library** using Python, Pandas, and Matplotlib. This project provides insights into content diversity, genre popularity, audience targeting, and evolving trends over time.  

## Project Overview

The goal of this project is to analyze Netflix’s dataset to uncover patterns in:

- **Global Content Diversity:** Which countries have the most content available.  
- **Evolution of Documentaries:** How documentary content has changed over the years.  
- **Top Genres per Country:** Popular genres in different regions.  
- **Targeted Age Groups:** Distribution of content across different age groups.  
- **Least Represented Genres:** Genres with minimal content, highlighting potential opportunities.  

This project demonstrates **data cleaning, aggregation, visualization, and insights extraction**, which are essential skills for a data scientist.  

## Dataset

The dataset includes Netflix titles with the following attributes:

- `show_id` – Unique identifier for each title  
- `type` – Movie or TV Show  
- `title` – Name of the show/movie  
- `director` – Director(s) of the title  
- `cast` – Main cast members  
- `country` – Country of origin  
- `date_added` – Date when added to Netflix  
- `release_year` – Year of release  
- `rating` – Content rating (e.g., PG-13, TV-MA)  
- `duration` – Duration of the movie/TV show  
- `listed_in` – Genre(s)  
- `description` – Brief description of the content  
 

## Key Insights

- The **United States** has the highest content (2,818 titles), followed by **India** (972).  
- Documentary content grew steadily from 2012 to 2017, then slightly declined.  
- **Documentaries** dominate in the US/UK; **Comedies and Dramas** are popular in India; **Anime** and **Korean TV shows** lead in Japan and South Korea.  
- Most content is targeted at **Adults and Teens**, while **Kids and Family** content is limited.  
- Niche genres like **Action & Adventure Cult Movies** are rarely represented.  

## Tools & Libraries Used

- **Python** – Core programming  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  

## Future Scope

- Extend the analysis with **user ratings, viewership, or revenue data**.  
- Build **recommendation systems** or predictive models to analyze content success.  
- Explore **regional content trends** for market expansion strategies.  

## How to Run

1. Clone the repository:  
```bash
git clone <repository_url>
