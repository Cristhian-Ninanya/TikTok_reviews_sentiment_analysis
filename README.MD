# **TikTok Reviews Sentiment Analysis**

![alt text](https://github.com/Cristhian-Ninanya/TikTok_reviews_sentiment_analysis/blob/main/Images/tik_tok_cover.png?raw=true)

**Overview:**

TikTok is a popular social media app known for its short and entertaining videos, despite its popularity not everyone shares the same enthusiasm for the platform.

**Target:**

Analyze TikTok reviews to find out what people think about the content of this app.

**DataSet information:**

For this project, we will use the TikTok app reviews dataset stored in kaggle (https://www.kaggle.com/datasets/shivkumarganesh/tiktok-google-play-store-review).

This dataset belongs to the TikTok app available on the Google Play Store.

**Attribute Information**

* **userName**: Name of a User.
* **userImage**: Profile Image that a user has.
* **content**: This represents the comments made by a user.
* **score**: Scores/Rating between 1 to 5.
* **thumbsUpCount**: Number of Thumbs up received by a person.
* **reviewCreatedVersion**: Version number on which the review is created.
* **at**: Created At.
* **replyContent**: Reply to the comment by the Company.
* **repliedAt**: Date and time of the above reply.
* **reviewId**: unique identifier.

## Imported DataSet:

```
                                    reviewId           userName   
448936  3e26b23a-99d4-40fa-86b7-60c89171c2d6    Kushneel Sharma  \
411280  c1353501-ead8-41fa-83cd-8a087ad05b97   Kimbreele Sucess   
108253  1acdc68a-f37e-43a3-9f44-74a9f9482111  Mohsin Hassan2255   
8825    3b66cac3-1cc4-41a6-b5de-ff3cbde2d538           Pana sha   
159131  f83475a8-3030-4737-80f6-c1edc83db2bf     Danish Pervaiz   

                                                userImage   
448936  https://play-lh.googleusercontent.com/a/ALm5wu...  \
411280  https://play-lh.googleusercontent.com/a-/ACNPE...   
108253  https://play-lh.googleusercontent.com/a/ALm5wu...   
8825    https://play-lh.googleusercontent.com/a/ALm5wu...   
159131  https://play-lh.googleusercontent.com/a/ALm5wu...   

                                                  content  score   
448936    Issues with live and cannot see online status 😔      4  \
411280  Like the app but when people spam like my cont...      4   
108253                                   So beautiful app      5   
8825    asgdhgkvihkjgjgjgmvkbvbbbmgjvjhjgjgfjghjhhkhju...      5   
159131                                    Excellent app❣️      5   

        thumbsUpCount reviewCreatedVersion                   at replyContent   
448936              0                  NaN  2022-06-21 22:20:23          NaN  \
411280              0               25.1.3  2022-07-03 14:50:43          NaN   
108253              0               26.4.5  2022-10-15 04:25:54          NaN   
8825                0               27.0.3  2022-11-26 10:48:58          NaN   
159131              0               26.2.3  2022-09-22 18:00:42          NaN   

       repliedAt  
448936       NaN  
411280       NaN  
108253       NaN  
8825         NaN  
159131       NaN 
```

## Rating Distribution:

![alt text](https://github.com/Cristhian-Ninanya/TikTok_reviews_sentiment_analysis/blob/main/Images/rating.png?raw=true)

**OBS:**
* Based on the graph above, it can be observed that the highest rating (5) is given by 64.9% of users, while the lowest rating (1) is given by 18.1% of users.

## Sentiment Analysis:

```
			Total	Percentage(%)
Sentiment		
Positive	142892	49.74
Neutral		113032	39.34
Negative	31370	10.92
```

![alt text](https://github.com/Cristhian-Ninanya/TikTok_reviews_sentiment_analysis/blob/main/Images/sentiment_distr.png?raw=true)

## word cloud with positive sentiments:

![alt text](https://github.com/Cristhian-Ninanya/TikTok_reviews_sentiment_analysis/blob/main/Images/positive_review.png?raw=true)

## word cloud with negative sentiments:

![alt text](https://github.com/Cristhian-Ninanya/TikTok_reviews_sentiment_analysis/blob/main/Images/negative_review.png?raw=true)

**Observations:**

* The sentiment of TikTok users' reviews appears to be predominantly **positive**, accounting for 49.74% of the analyzed data.

* Among the analyzed user reviews, a significant portion (39.34%) expresses a **neutral** sentiment, while a minority (10.92%) conveys a **negative** sentiment.

* Some of the most common words in positive sentiment user reviews include "best", "good", "love", "nice", "great", and "fun".

* Some of the most common words in negative sentiment user reviews include "bad", "annoy", "hate", "stupid", "wrong", and "ban".


