## NETFLIX Movies and TV_Shows
![NETFLIX](https://github.com/Sadikctg/Project_3_Netflix_Movies_and_TV_Shows_EDA-/blob/main/netflix_page_cover.jpg)

###Business Problem** <br>
- To analyze the data and generate insights that could help Netflix deciding which type of shows/movies to produce and how they can grow the business in different countries.<br>
- To develop a movie and TV show recommendation function, users should have the capability to search for a specific movie or TV show by its name. Upon entering the title, the system should generate recommendations based on similar content. <br>

To achieve the desired solution, a recommendation system will be developed by following these steps.

1. **Data Understanding:**
  - The initial stage involves comprehending the dataset. In this project, there are 12 variables, six of which contain missing values.

2. **Univariate Exploratory Data Analysis (EDA):**
  - Conduct an in-depth analysis of individual variables within the dataset to gain insights and understand their distributions and characteristics.

3. **Data Preparation:**
  - Prepare the dataset for analysis by addressing missing values, handling categorical variables, and performing any necessary transformations or preprocessing steps.

4. **Recommendation System with Cosine Similarity:**
  - Implement a recommendation system using cosine similarity.
  - This method utilizes text similarity between titles and descriptions to recommend similar titles.
  - It involves vectorizing the text data and calculating the similarity between vectors.
  - To obtain title recommendations, select the title with the highest similarity score and retrieve the corresponding TV series or movie title along with its description.

  - 
