
## Important Notes

* Collaborative-filtering.ipynb; contains Collaborative filtering implemented on the dataset provided. It tells us whether two books are similar based on how different users have rated the books.
I have also implemented Popularity based recommendation system in the code, so it can display popular recommendations in case of our recommendation system is unable to recognize some unpopular book.

* Content-based.ipynb; contains content based filtering logic which involves formulation of recommendations based on how similar contents are based on their own features. This also includes Popularity based recommendation system for error handling.

* Top_100.pkl; contains top 100 books recommendations based on user high user ratings. These can be useful for cold start recommendations.

* You can try multiple input in "book_name" variable, I have tried "The Notebook" which is a famous Romantic Novel

* Results were better in case of collaborative filtering than content based filtering, because the dataset contains little descriptive features related to the books, A genre would have been suffice to make it work better
