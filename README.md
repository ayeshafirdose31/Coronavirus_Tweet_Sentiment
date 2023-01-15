# Coronavirus_Tweet_Sentiment
The COVID-19 pandemic is a global outbreak of the coronavirus, an infectious disease caused by the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) virus.

The first cases of the novel coronavirus (nCoV) were first detected in China in December 2019, with the virus quickly spreading to other countries around the world. This led the WHO to declare a public health emergency of international concern on 30 January 2020 and to designate the outbreak as a pandemic on 11 March 2020.

Since the start of the COVID-19 pandemic, more than 2 million people have died from the disease in the European region.

Sentiment analysis of tweets related to the coronavirus can provide valuable insights into public opinion and perception of the virus. It can be used to track changes in sentiment over time, identify influential users and groups, and identify specific issues or concerns related to the virus. However, it is important to note that sentiment analysis is not a straightforward task and results may vary depending on the dataset, pre-processing and modeling used. Sentiment analysis of tweets can be challenging due to informal language, use of slang and emoticons, and the presence of sarcasm and irony.
In this project we have data related to covid-19 tweets, where we have done exploratory data analysis, applied multiple text preproicessing techniques, vectorisation of textual data and we have also handled the imbalance in our dataset. And finally we build multiple machine learning models, where Support Vector Classifier was the best model because it gives the highest accuracy on test data as compared to other models. 

                                                Some of the key insights found from this project are as follows👇🏻-:

* Most of the tweets found were in March and April 2020, as the first wave of covid spread widely around the world and many countries declared lockdowns.

* Majority of the sentiments are positive as people try to keep a brave face during the pandemic.

* Username and ScreenName were not important for our analysis because they contained all unique IDs

* Majority of the tweets came from the US, UK, and India as these were the most affected geographies.

* Most of the hashtags used in tweets will be either #COVID19 or #coronavirus.

* Food and coronavirus, covid 19 should be some of the most common words because there was a shortage of food in grocery stores during the pandemic.

* We extracted new features like num_char, num_words, num_sentences to check the sentiment of a tweet. We saw that if there are more words, characters and sentences, then the sentiment of the tweet is more positive. Tweets with neutral sentiment contain fewer words, characters, and sentences.

* If the performance of the multiclass models was not satisfactory, we would convert the problem to a binary class where the target variable could be changed to (0 and 1)

* For vectorization, we tried TF-IDF vectorization for vectorization and used an unbalanced method using smote over_sampling to balance the data because most of the tweets were positive.

* The feature importance is calculated based on the most frequent words in each class. We can see that London, United States, New York, Washington DC, United Kingdom, India, Australia, USA are the places in terms of the number of tweets.

* We can see that the maximum number of tweets was made on March 20, 2020, when the first lockdown was announced. People were more active on Twitter in March because it was the early stage of the coronavirus pandemic and people wanted to know more about the disease.

* We evaluated the multi-class models as categories – positive, neutral, and negative.

* We have applied multiple classification machine learning models where Support Vector Classifier is the one with best accuracy on testing Data.

* And at last we saved our SVC model into a pickle file for further process of deployment.
