## SHE-FARER - Safe Trip Recommender

**Project description:** Consider a user who is visiting an unknown city and wants to visit the Hotspots near his location. The usual choice is to google 'Places near me', ask friends or post questions on social platforms like Quora, which mostly accounts to biased suggestions and therefore doesn’t always guarantee a satisfactory trip.

<img src="images/shefarer.png?raw=true"/>

**Solution:** "SHE-Farer" is a Recommendation Engine provided in the form of a web application, that can answer the same questions but considers the opinions of the diversified population of wider demography. We have about 10,000 user's data synthetically generated based on a normal distribution and have clustered them based on the euclidean distance of measure of their features. We clustered the user data into 10 different clusters, where 10 (no. of clusters) was obtained from the Elbow curve method of plotting. So, when a new user enters the system, we map him to one of the existing clusters, which contains users who have a similar preference to that of the new user. Based on the historic data of ratings given to different places by the users in this cluster, we predict what our current user will rate those places based on the ML algorithm, Collaborative Filtering. The places with the highest predicted ratings are recommended to the user and plotted as a route in the map.

For Code and other references [DEVFOLIO POST](https://devfolio.co/submissions/shefarer).