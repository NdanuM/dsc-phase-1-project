# Microsoft Movie Start-up Analysis
![image](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/3baa0f36-e43b-4821-b324-38a1d5064744)

Author: Ndanu Mwatu

## Overview
This project seeks to generate business insights for Microsoft's Movie Start-up by analyzing movie data from Internet Movie Database(IMDB) and The Movie Database(TMDB).

## Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. We are charged with exploring what types of films are currently doing the best at the box office and translating these findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Data
Data used is IMDB Basics data; IMDB Ratings data and TMDB movies data.
IMDB Basics has data on genres.IMDB Ratings has data on movie ratings and number of votes. TMDB database has data on movie release dates, ratings and number of votes.

![image](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/00e92158-f1d1-47c7-ba76-105f9d2e9839)

## Methods
Data preparation includes: Dropping unnecessary columns; Merging dataframes; Checking for duplicated data and Checking for and dealing with missing values.

Data modeling methods include: Filtering the data by certain parameters; Groupby with aggregation; Changing datatype; Creating new feature (column) to the dataframe and Creating Visualizations

## Results
**1. Most commonly produced movie genres**

![most_commonly_produced_movie_genres](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/9530f320-4322-4d58-8e63-6d5d798a78d6)

Dramas are the most commonly produced movie genre without considering ratings.

**2. Top 5 highest rated movie genres**

![top_5_highest_rated_movie_genres](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/00595ab4-24c4-4a38-81ed-697a99991c33)

Top 5 highest rated genres of movies differ from the top 5 most commonly produced genres.

Adventure, Documentary & Western is the most popular genre combination.

**3. Movie lengths**

![movie_length_vs_no_of_movies](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/796d58f7-39f7-4401-9770-32b7216b2060)

90 minutes is the most common movie length.

**4. Runtimes of top 5 highest rated movie genres**

![runtime_of_top_5_highest_rated_movie_genres](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/4cdc9c5d-c557-4bc4-938b-9dbf9072cd7f)

77 to 134 minutes is the range of length for the top 5 highest rated movie genres

**5. Month of release**

![month_of_release_vs_ratings](https://github.com/NdanuM/dsc-phase-1-project/assets/133153210/68cde688-5463-486f-9b78-7b2f567159b1)

November and December  are the best months to release a movie

## Conclusions
An analysis of movies that are currently doing the best at the box office reveals which movies Microsoft new studio should produce:
1. **Genres:** Pursue production of movies of these genres:  Adventure,Documentary,Western;  Documentary,Drama,Thriller; Mystery,News,Thriller;  Comedy,History,Musical ;  Animation,Crime,Mystery.
2. **Runtimes:** Produce movies with these approximate  runtimes:  77 minutes (Adventure,Documentary,Western);  98 minutes (Documentary,Drama,Thriller); 88 minutes ( Mystery,News,Thriller); 134 minutes (Comedy,History,Musical); 116 minutes ( Animation,Crime,Mystery)
3. **Month of release:** Release majority of the movies produced in November and December. Avoid releasing films in January and May as they tend to have lower ratings.

##  Next Steps
Further analysis is recommended in the following areas for additional insights:
* **Gross earnings:** Analysis of box office gross earnings in addition to popularity (ratings), to further refine the kinds of movies to pursue.
* **Production budget:** An examination of production budgets per recommended movie genre, to give the client a feel of the production capital needed.
* **Streaming services:** An investigation into popularity and earnings of films produced for streaming services such as Netflix, as opposed to box office release only, to guide the client on best approaches.

### For More Information
See the full analysis in the Jupyter Notebook or review the presentation

For additional information contact Ndanu Mwatu at Mwatu.Ndanu@student.moringaschool.com

### Repository Structure
* data
* images
* README.md
* Microsoft_Movie_Start-up_Presentation_N.Mwatu.pdf
* Microsoft_Movie_Start-up_Analysis.ipynb


