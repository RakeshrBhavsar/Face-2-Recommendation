

# Inspiration
Try searching "Movies for age 25 Female/Male" on search engine or "Clothes for Women of age 30" on E-commerce websites . The search results will contradicts with your query like you will see results of baby dress instead of women of age 25. This was the seed for our idea. We did research on our first day of Bitcamp for recommendations based on gender and age. We later came across a recent case study conducted in January 2018 - Face Based Advertisement Recommendation with Deep Learning: A Case Study. According to the paper a Face Based Advertisement Recommendation System (FBARS) could raise the accuracy 4 times.

# How we built it
Challenges we ran into
One of the major challenge we had come across was with the data collection. There are very few open source data sets available that has age and gender. We found a Movielens dataset but age field had data in high range. Due to this the distribution of the data was not uniform that affected the performance of the Deep Learning Model. We then tweaked our age data by generating age using row shuffle + random number generator based on age range.

# Accomplishments that we're proud of
We implemented a proof of concept which captures your photo and detects age-gender. Based on the age-gender, recommends movies to the user.

# What we learned
The facial features such as age, gender, can help us classify consumers intuitively and rapidly so that it can raise the accuracy in recommendation in a short time. Face Based Recommendation System could raise the accuracy 4 times.

# What's next for Face 2 Recommendation
More squeezed Neural Network that can be deployed on iPhone or Android devices.



