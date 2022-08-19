# Movie-Fy
This Application performs Content Based Recommendation of Movies based on the choice of the user. 

In Content Based recommendation systems whatever content is previously watched by the user is kept as a reference for recommending new contents. Thus making it
user centric.


How does it Work ?


This is the landing page when anyone comes for the first time on the website.

<img width="1118" alt="image" src="https://user-images.githubusercontent.com/44739430/185646106-c2cefd65-f687-4184-bd02-263d088a7256.png">



From here the user has to select from the drop down list which movie he/she saw recently.

<img width="713" alt="image" src="https://user-images.githubusercontent.com/44739430/185653836-1642ca7e-3f69-4f04-9cfc-5789aa84bb3e.png">

Based on the choice received from the USER, the algorithm recommends them with the top 5 most relevant movies.


<img width="597" alt="image" src="https://user-images.githubusercontent.com/44739430/185654403-71101062-b02c-437a-96b0-86d861de2a01.png">


The recommendation algorithm uses cosine Similarity as an underlying fundamental principle. 

This application makes use of fundamental NLP tools for making the recommendation system. It computes the similarity between genres and also plot summaries and also considers the name of the actors and directors for making the prediction more relevant to the user's choice.
