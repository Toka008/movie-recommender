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


A bar graph showing movies published per year
![moviesperyear](https://github.com/Toka008/movie-recommender/assets/63381061/c2d706a0-079a-48b1-ad73-ede3a62f192d)
- Most movies were released between 1995 and 2000.
- We can relate this to these factors:
    1.Technological advancements.
    2.Cultural and social factors, such as the rise of blockbuster franchises.
    3.Globalisation of the film industry.

A bar graph showing movies ratings distribution
![Rating distri](https://github.com/Toka008/movie-recommender/assets/63381061/546a2518-9cc8-4187-9215-985aa152e6e9)
- Most users give a rating of 4 stars, followed by 3 then 5.
- It is also evident that users are more likely to give a 5 star rating than a 0.5.

A bar graph showing popular genre
![popular genre](https://github.com/Toka008/movie-recommender/assets/63381061/bfd7c8c5-c178-4150-ac31-17f690553bf8)
- The most popular genre is drama.
- The top 5 most popular genres are drama, comedy, action, thriller andadventure.

A bar graph showing average genre rating
![averageratinggenre](https://github.com/Toka008/movie-recommender/assets/63381061/5790560b-effa-4d73-bb2e-990d2b3facb9)
- Film-Noir performed better than all the other genres.
- Wholistically, all genres performed well, averaging at 3 and above.

## Conclusions
1. An excessive amount of ratings have been provided by the most popular users. This could distort the results in favor of their personal preferences if not handled appropriately.
2. Because bad ratings were uncommon and users tended to offer high ratings, we don't have a lot of information on what users dislike.
3. While many movies only got one rating, the top film earned multiple ratings. One user's taste is essentially used to determine the rating of a movie with just one star, which is not optimal.


## Recommendations
1. Inspire users to give movies a rating. in particular, movies with low ratings and infrequent raters. This ought to aid in balancing the data.
2. Users are unlikely to evaluate movies they don't love, yet we still need this information because a person's taste is influenced by both of these factors. Maybe in order to collect this data, watch times should be considered, and movies with low watch times—that is, ones where viewers stop viewing them early—could be regarded as unappreciated.

## Acknowledgements
Special thanks to the project team members for their contributions:

- Matlou Mmatlakala
- Jacinta Mabinda
- Marcus Ayodele
- Akanni Deji
- 

## Note
Due to the sensitive nature of the project, code cannot be shared publicly.

