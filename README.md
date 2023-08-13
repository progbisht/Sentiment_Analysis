# Sentiment_Analysis
Covid-Booster Dose Hesitancy (Sentiment Analysis)

# Introduction
The global COVID-19 pandemic, originating in Wuhan, China in 2019, has led to the development and authorization of various vaccines as a primary means to mitigate its spread. In light of concerns related to emerging variants and potential waning immunity, the adoption of booster shots has gained substantial attention as a measure to reinforce protection against the virus and its variants. However,
the proliferation of rumors and controversies surrounding vaccines, including potential side effects, has had a significant impact on individuals&#39; decisions to accept or decline vaccination. Due to the limited availability of comprehensive data, individuals often turn to Twitter, a popular social media platform, to express their emotions and opinions on various topics, including COVID-19. Therefore, we collected publicly available tweets from Twitter to conduct an analysis of public sentiment regarding COVID-19 booster dose hesitancy.
Natural Language Processing (NLP) is an area of computer science that focuses on examining and interpreting text. Over time, notable progress has been achieved by leveraging deep learning (DL), machine learning (ML), and NLP methodologies, as evidenced by a prominent study. Furthermore, ML and NLP have found applications in medical reviews to analyze public behavior. Moreover, such an approach will offer valuable guidance for future studies, enabling them to contribute more to the subject matter.

# Methodology
For our study, we utilized a social media platform (Twitter) to gain insights into people&#39;s perspectives on COVID-19 booster doses and the concerns they expressed regarding booster doses. To collect relevant data, we utilized the Python library Snscrape to scrape public tweets, which enabled us to understand people&#39;s experiences, emotions, and perspectives on health policies. The study commenced with a preprocessing stage in which we eliminated extraneous text from the scraped tweets to ensure suitability for sentiment analysis.
- In the preprocessing step, the data was normalized by removing stopwords, URLs, and retweets, and translating emoji into words from the collected tweets.
- Subsequently, we tokenized the tweets and applied stemming and lemmatization techniques.
- Following the preprocessing, we employed TextBlob to calculate sentiment scores, and the dataset was vectorized using the TF-IDF vectorization technique.
- Lastly, we utilized the LinearSVC machine learning algorithm to classify the COVID-19 Twitter dataset into positive, neutral, or negative categories, thus evaluating our model&#39;s performance.

  # Results
The findings of the sentiment analysis study, the majority of tweets exhibited either a neutral or positive sentiment. Specifically, 46.3% of the analyzed tweets were classified as having neutral sentiments, while 40.7% were determined to convey positive sentiments. These findings indicate a gradual shift in public sentiment towards optimism concerning COVID-19 booster doses, primarily driven by concerns surrounding new variants and waning immunity. 
To assess vaccine hesitancy, we employed the TextBlob computation method in conjunction with the TF-IDF vectorization method and the LinearSVC learning algorithm. Our experimental results demonstrate the effectiveness of employing TextBlob, TF-IDF, and LinearSVC in precisely classifying public sentiment into positive, neutral, or negative categories. Remarkably, our model achieved elevated levels of accuracy, precision, recall, and F1 scores, recording values of 0.9786, 0.9712, 0.9648, and 0.9679, respectively.
