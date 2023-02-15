# Data Wrangeling for WeRateDogs Tweets
## by Nacer KROUDIR

## Dataset:
The dataset used in this project is the tweet archive of the popular Twitter account `@dog_rates`, also known as **WeRateDogs**. The account humorously rates people's dogs and has over 9.3 million followers (as of February 2023). The ratings typically have a denominator of 10, but the numerators are often greater than 10 (e.g. 11/10, 12/10). The data will be wrangled, analyzed, and visualized using Python and its libraries.

## Tasks
The project involves the following steps:
1. Gathering data, including:
    * Directly (available in the Resources section of your classroom or linked in step 1).
    * Using Twitter API to query WeRateDogs Tweets data.
    * Using `requests` library and the URL for the data.
2. Assessing data quality and tidiness.
3. Cleaning the data.
4. Storing, analyzing, and visualizing the cleaned data.
5. Documenting the data wrangling process in a Jupyter Notebook, and presenting the results through analysis and visualization.

## Key Findings
- The number of monthly tweets decreased over time. falling from over 300 tweet a month to around 60 a month.
- The most common dog stage is **pupper** with over 65%; followed by **doggo**.
- The highest rated dog breed is **clumber** (That might be due to its appearance once in the dataset).
- **golden retriever** and **labrador retriever** are the most common dog breeds in the tweets.
- The most common dog name are **Lucy** and **Charlie** with 11 dogs holding that name; followed by **Oliver** and **Cooper** with 10 mentions each.
- There is a positive linear correlation between `favorite_count` and `retweet_count`.
