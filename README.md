# Personaled-Yelp
Recommendation system to yield personalized results from Yelp - GA Tech Team Project

Problem:
- Yelp cannot recommend you __personalized__ results until it knows you (have an account decorated with written reviews)

Solution:
- Utilize Matrix Factorization and User-based Collaborative Filtering to connect your preferences (a blank slate user with no actual account) to recommended venues.
- Inputs to the model == Business's tags. Ex: "Desserts" "Thai"
- Outputs from the model == Top 5 restaurants based on similarity score ratings

Scope:
- Proof of concept project
- Recommendations are populated for Chicago, CA only (As the users were curated from Chicago for the training model)
