![microsoft_image](Images/Microsoft_Logo.jpg)

# Microsoft Movie Analysis

**Author**: Lynn Rotich

## Overview

Microsoft aims to launch a movie studio producing original, successful movies. To guide this, the project analyzed movie industry data—focusing on genres, release months, runtimes, and audience ratings. Findings show that combination genres like Comedy, Documentary, and Fantasy receive higher ratings; May, June, and July are the most profitable release months; and films 90–120 minutes long enhance viewer satisfaction. Microsoft can focus on these high-performing genres, months, and runtimes to become successful. For deeper insights, analyzing top release platforms and popular actors will support strategic decision-making as they explore the movie industry.

## Business Problem

Exploring industry data to identify which movie genres generate the highest audience ratings, which months have the most successful movie releases and the optimal movie runtime based on audience ratings to enable Microsoft to strategically position their new movie studio in the market based on the data.

## Data

This project uses multiple datasets from various movie industry sources, including The Numbers, IMDb and TheMovieDB (TMDb). These datasets contain information on movies such as runtimes, audience ratings, box office revenues, genres, production budgets, titles and release dates. Each dataset focuses on a different aspect of movie performance.

The data will be cleaned and analyzed to extract actionable insights that will help Microsoft determine the best path for ensuring success of their new movie studio.

## Method

Methods used to prepare the data for analysis include:
* Dropping rows with missing values
* Creating new columns for better analysis
* Handling outliers in the data

## Results

Top Movie Genre is Comedy, Documentary, Fantasy

<img width="984" height="584" alt="Top Genres by Average Audience Rating" src="https://github.com/user-attachments/assets/2bb8153a-b826-40d7-b685-bc9e5c629474" />



Best months to release movies is in May, June and July based on the Worldwide gross

<img width="784" height="484" alt="Top 5 Release Months by Worldwide Gross" src="https://github.com/user-attachments/assets/0c7fcae6-426a-47e4-b57a-e716f6c78274" />



Optimal movie runtimes is between 90-120 minutes based on Average Audience Ratings

<img width="984" height="584" alt="Best Movie Runtimes Based on Audience Ratings" src="https://github.com/user-attachments/assets/11aa0076-5619-44b7-a195-fb15a86d080a" />


## Conclusions

Based on the analysis, the following recommendations are proposed:

1.Focus on High-Performing Genres

As a new movie studio, Microsoft should prioritize genres that receive higher audience ratings. These include combination genres such as Comedy-documentary-fantasy and Documentary-musical-family. Unique genres like Game-show also appear to pique audience interest. Starting with the top three performing genres would increase the likelihood of early success.

2. Releasing Movies during High-performing Months

Releasing films during peak months—such as May, June and July—can significantly improve revenue. This would help offset the high initial costs Microsoft is likely to incur as a new entrant in the movie industry.

3. Target Optimal Runtime

Producing movies with runtimes between 90-120 minutes is likely to boost audience ratings and overall satisfaction.

### Next Steps

To enhance the depth and accuracy of the analysis in the future, the following steps are recommended:

Expand data sources to include revenue from streaming platforms versus cinema releases. This would help determine the most profitable distribution channels for Microsoft’s movies.
Incorporate actor popularity data, such as the most watched and liked actors for specific genres. This would enable Microsoft to make informed casting decisions, increasing the potential for success in the industry.


## For More Information

See the full analysis in the [Jupyter Notebook](./MS_Movies_Analysis.ipynb) or review this [Presentation](./Microsoft_Movie_Analysis.pdf).


## Repository Structure

```
├── Data
├── Images
├── MS_Movie_Analysis.ipynb
├── Microsoft Movie Analysis.pdf
└── README.md
```




