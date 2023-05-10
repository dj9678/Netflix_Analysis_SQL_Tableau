<h1>Netflix Analysis SQL & Tableau</h1>								
<p>By Dongsuk Jeong | November 2022</p>
<h2>Purpose</h2>
<p>
  - To explore the Netflix Movies and TV Shows dataset using PostgreSQL<br>
  - To visualize the result of query using Tableau
</p>

<h2>Methodology</h2>								
<span class="image main"><img src="Portfolio_Methodology4.jpg" alt="" /></span>

<h2>Data Collection & Wrangling</h2>
<p>
  - Collected Netflix Movies and TV Shows dataset from kaggle<br>
  - The dataset consists of listings of all the movies and tv shows available on Netflix with details such as cast, directors, ratings, release year, duration, etc
</p>

<h2>Exploratory Data Analysis</h2>
<p>
  - Check unique value in the column using DISTINCT<br>
  - Count number of rows where identifier is 'Move' and identifier is 'TV Show' using WHERE<br>
  - Look up and count the number of rows where the column of listed_in contains word "Family" using LIKE<br>
  - Check what is the top 5 countries that release the most content on 2021 using GROUP BY and WHERE<br>
  - Check how many null is in the country column<br>
  - Look up the movie and tv show added on each months using DATE_TRUNC<br>
  - Check the most popular genre added by country during April, 2021 using COUNT, GROUP BY, and ORDER BY<br>
  - Check which country add same genre more than 5 using HAVING<br>
  - Search how many tv show or movie added by date_added using WITH function
</p>

<h2>Tableau Visualization</h2>
<span class="image main"><img src="Portfolio_Methodology4_1.png" style="width: 50%; margin: 5% 0px 30px 0px;" /></span>
<span class="image main"><img src="Portfolio_Methodology4_2.png" style="width: 50%; margin: 30px 0px 30px 0px;" /></span>
<span class="image main"><img src="Portfolio_Methodology4_3.png" style="width: 50%; margin: 30px 0px 5% 0px;" /></span>

<h2>Conclusion</h2>
<p>
  - The director having the most work in Netflix is "Rajiv Chilaka"<br>
  - The most popular rating in Netflix is TV-MA and the most popular genre is Drama, International Movie<br>
  - Comparing between the number of contents added between South Korea and United States, United States have a lot more contents than South Korea. In addition, both of countries added the most contents in 2021, then decreased<br>
  - During 2019 to 2021, United States showed the most contents added way more than other countries all of three years<br>
  - The movie added more than TV show overall countries in 2021
</p>
