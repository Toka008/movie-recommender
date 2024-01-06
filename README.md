# Movie Recommender System

## Context
Because movie-streaming services don't have recommender systems, like their competitors do, they have poor user retention. To remain competitive, they require a method for recommending movies.

## Expected Outcomes
1. Determine the patterns in the viewing of movies
2. Develop a mechanism for recommending movies
3. Develop an app that incorporates the method for recommending movies.
4. Inform interested parties of findings

## Tools Used
1.Python
  - Streamlit
  - scikit-learn
  - nltk
2.Comet
3.GitHub
4.AWS EC2 with S3 bucket

## Output

Our Demo of the App created: 

![Screenshot 2024-01-02 115924](https://github.com/Toka008/HR-Case-Study-Absenteeism-Insights-and-Performance-Improvement/assets/63381061/18f18c6f-0146-4cf1-a6e5-deb34628826a)

A bar graph showing movies published per year
![moviesperyear](https://github.com/Toka008/movie-recommender/assets/63381061/c2d706a0-079a-48b1-ad73-ede3a62f192d)

A bar graph showing movies ratings distribution
![Rating distri](https://github.com/Toka008/movie-recommender/assets/63381061/546a2518-9cc8-4187-9215-985aa152e6e9)

A bar graph showing popular genre
![popular genre](https://github.com/Toka008/movie-recommender/assets/63381061/bfd7c8c5-c178-4150-ac31-17f690553bf8)

A bar graph showing average genre rating
![averageratinggenre](https://github.com/Toka008/movie-recommender/assets/63381061/5790560b-effa-4d73-bb2e-990d2b3facb9)

## Conclusions
1. An excessive amount of ratings have been provided by the most popular users. This could distort the results in favor of their personal preferences if not handled appropriately.
2. Because bad ratings were uncommon and users tended to offer high ratings, we don't have a lot of information on what users dislike.
3. While many movies only got one rating, the top film earned multiple ratings. One user's taste is essentially used to determine the rating of a movie with just one star, which is not optimal.


## Recommendations
1. Inspire users to give movies a rating. in particular, movies with low ratings and infrequent raters. This ought to aid in balancing the data.
2. Users are unlikely to evaluate movies they don't love, yet we still need this information because a person's taste is influenced by both of these factors. Maybe in order to collect this data, watch times should be considered, and movies with low watch times—that is, ones where viewers stop viewing them early—could be regarded as unappreciated.

## Acknowledgements
Special thanks to the project team members for their contributions:

- Quinn Grace
- Shedrack Udeh
- Tebatso Malotane
- Toka Ramakau (Head Designer)

## Note
Due to the sensitive nature of the project, code cannot be shared publicly.

