# TMDB Movies Data Analysis
## By Nacer KROUDIR

This Jupyter Notebook contains a data analysis of the TMDB movies dataset. The purpose of this project is to familiarize yourself with the data analysis process and the Jupyter Notebook workflow.

The TMDB Movies dataset contains information about various movies such as their budget, revenue, release date, and popularity. We will use this dataset to explore and analyze trends in the movie industry.

## Key Findings

- The number of movies directed every year increased exponentially since 1960 untill 2014. It is expected to rise more in the next years.
- The top 5 movies `Jurassic World`, `Mad Max: Fury Road`, `Interstellar`, `Guardians of the Galaxy` and `Insurgent` are all released after 2014.
- There are two movies that surpassed the 2 billion $ revenue that are `Avatar` and `Star Wars: The Force Awakens`.
- `Colin Trevorrow` who directed `Jurassic World` surprisingly directed only one other movie that is `Safety Not Guaranteed`.
- The director that released the most movies is `Woody Allen` with 45 movies.
- Most popular movies tend to be long ones (over 2 hours).
- In the last half decade, Drama and Comedy dominated the movie genres as the people's favorite.
- Big production companies produced over 400 movies such as `Universal Pictures`, `Warner Bros`, `Paramount Pictures` and `Colombia Pictures`.
- `revenue` and `budget` have some sort of a linear relationship. That is the more spent on a movie, the more revenue it is expected to generate.
- There is a high linear relationship between vote_count and popularity which is understandable.

## Limitations

- We included all the movie genres in the calculation although many movies have more than one genre assigned to it seperated by `|`.
- `vote_count` & `vote_average` are not clear on how to find them and have no formula of calculation.
- `budget` & `revenue` have a lot of `0`'s and are filled with the mean for that year for the current situation but this may not help us if we want to do any further analysis.
- Overall the missing and 0 values are limiting any further analysis or complex inferential statistics.
