# Netflix Movies Analysis: Are Movies Getting Shorter?

![Netflix Logo](image_link_here) <!-- Replace with your image link -->

## Introduction

### Project Description/Overview
In this project, we explore Netflix movie data to determine if movies are getting shorter over time. By performing exploratory data analysis (EDA), we aim to uncover trends in movie duration, particularly focusing on how these trends have evolved over the years. This analysis will provide insights into movie production trends and help us understand whether there is a shift towards shorter films.

## Skills/Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**

## Problem Statement

Movies seem to be getting shorter, and this project investigates this claim using Netflix's dataset. We aim to analyze the trend in movie durations over the years to determine if there is a statistically significant shift towards shorter movies.

## Project Objectives

- To analyze the trend in Netflix movie durations over the years.
- To identify the most common movie durations in different decades.
- To investigate the distribution of movie durations across various genres.
- To determine if specific genres are contributing to the trend of shorter movies.

## The Data

The dataset used in this project, `netflix_data.csv`, contains information about Netflix's movie and TV show library. It includes the following columns:

- **show_id:** ID of the show
- **type:** Type of show (movie or TV show)
- **title:** Title of the show
- **director:** Director of the show
- **cast:** Cast of the show
- **country:** Country of origin
- **date_added:** Date added to Netflix
- **release_year:** Year of Netflix release
- **duration:** Duration of the show in minutes
- **description:** Description of the show
- **genre:** Show genre

You can download the dataset from the [repository link here](your_data_link_here).

## Project Methodology

The project followed these analytical steps:

1. **Data Loading:** Loaded the Netflix dataset and inspected its structure.
2. **Data Cleaning:** Filtered out TV shows and irrelevant columns, focusing only on movies.
3. **Exploratory Data Analysis (EDA):** 
   - Investigated trends in movie durations over different decades.
   - Analyzed the distribution of movie durations by genre.
   - Identified the most common movie durations in the 1990s.
   - Counted the number of short action movies released in the 1990s.
4. **Visualization:** Created scatter plots to visualize movie durations over the years, with a focus on specific genres.

## Results

- **Trend in Movie Duration:** The analysis revealed that there is a visible trend of shorter movies, particularly in specific genres such as children’s movies and documentaries.
- **Most Common Duration in the 1990s:** The most frequent movie duration in the 1990s was 94 minutes.
- **Short Action Movies in the 1990s:** There were 8 short action movies (less than 90 minutes) released in the 1990s.

## Conclusion

The analysis provides evidence that Netflix movies may be getting shorter over time, with a particular trend in specific genres. However, this trend is not definitive and requires further exploration to understand the underlying factors.

## Future Recommendations / Moving Forward

- **Further Analysis:** Explore other factors such as the influence of directors, production companies, or regions on movie duration.
- **Genre-Specific Analysis:** Conduct deeper analysis into each genre to see if the trend holds across different types of movies.
- **Comparison with Other Platforms:** Compare Netflix data with other streaming platforms to determine if this trend is unique to Netflix.

## Acknowledgements

Special thanks to the open-source community for providing datasets and resources that made this project possible.

---

Feel free to fork this project or reach out if you have any questions or suggestions!

