Sentiments-and-text-mining
Overview
The task, titled The sentiment of customer reviews: providing insights on customer satisfaction and potential areas for improvement for restaurant based on rating Utilizing Python libraries and NLTK for sentiment intensity analysis, the project aims to determine the proportion of customers who has given excellent reviews based on the overall rating and visualize these reviews while considering whether they are positive or Negative.
Data Cleaning and Transformation
The preprocessing steps involved converting text to lower case, removing special characters and numbers. Tokenization, stop words removal, and lemmatization were performed to refine the text data. Missing values were handled by replacing them with a placeholder. The 'rating' column was transformed using TF-IDF vectorization, preparing the text for machine learning models.
EDA
The analysis involved sentiment analysis using VADER (Valence Aware Dictionary and sentiment Reasoner), frequency analysis, topic modeling, word clouds, and N-gram analysis. Sentiment scores were computed and analyzed through histograms, revealing a distribution with a peak around the positive review. Also the median compound score is 0.76 – which means that over 50% of the reviews have a compound score of more than 0.76, which suggests strong positive sentiment.
Results of Analysis
Sentiment Analysis:
Revealed a significant positive sentiment peak, with 74.66% of the restaurant reviews been positive, 18.79% were negative, and 6.55% were neutral.
Text Mining Analysis:
Common words in the positive reviews are "place," "good," and "food" which indicates that the review are about the restaurants serving good food and great ambience.

Conclusion and Recommendation
The positive dominance indicates growing customer satisfaction and reputation, the negative reviews indicate areas for improvement. The improvements include staff training, quality control procedures, operational strategies, and food and service quality.
Even though there are more positive sentiments than negative ones, the negative sentiments help to point out areas that could use improvement, which helps the restaurants improve customer satisfaction and service quality.

