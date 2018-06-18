# Restaurant-Recommendation-System


The whole idea is based on the assumption that if you share the same opinions on a lot of things with someone, it's more likely that you both have similar ideas about others too.

In short, this recommendation system is based on analyzing the similarities between user-pairs and making rating predictions based on historical data.

We use a technique called Collaborative Filtering.

Collaborative Filtering (CF) is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).

Our dataset is from Yelp Dataset Challenge, which provides us the user info, rest info and the review info.

Here's some key steps we take to format data:

Change the .json file into .csv file. (Here's some tips for changing file type.) Limit the city of restaurants to "Las Vegas" Count the review number by user_id, and keep those with more than 3 reviews Merge the review dataset with user and restaurants dataset by user_id and business_id Create Matrix
