# Sentiment_Analysis
Covid 19 Booster Dose Hesitancy (Sentiment Analysis)

# Introduction
Natural Language Processing (NLP) is an area of computer science that focuses on examining and interpreting text. Over time, notable progress has been achieved by leveraging deep learning
(DL), machine learning (ML), and NLP methodologies, as evidenced by a prominent study.
Furthermore, ML and NLP have found applications in medical reviews to analyze public
behavior. Moreover, such an approach will offer valuable guidance for future studies, enabling them
to contribute more to the subject matter.

# Methodology
For our study, we utilized a social media platform (Twitter) to gain insights into people&#39;s perspectives
on COVID-19 booster doses and the concerns they expressed regarding booster doses. To collect
relevant data, we utilized the Python library Snscrape to scrape public tweets, which enabled us to
understand people&#39;s experiences, emotions, and perspectives on health policies. The study commenced
with a preprocessing stage in which we eliminated extraneous text from the scraped tweets to ensure
suitability for sentiment analysis.
In the preprocessing step, the data was normalized by removing stopwords, URLs, and retweets, and
translating emoji into words from the collected tweets. Subsequently, we tokenized the tweets and
applied stemming and lemmatization techniques. Following the preprocessing, we employed
TextBlob to calculate sentiment scores, and the dataset was vectorized using the TF-IDF vectorization
technique. Lastly, we utilized the LinearSVC machine learning algorithm to classify the COVID-19
Twitter dataset into positive, neutral, or negative categories, thus evaluating our model&#39;s performance.
