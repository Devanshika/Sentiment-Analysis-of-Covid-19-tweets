This data mining project conducted a sentiment analysis on 17k tweets containing the #covid19. Two main data analysis models were used to cross validate the results, Linear Support Vector Classification and Multinomial Naives Bayes. TextBlob and NLTK Vadar Lexicon were used to determine the polarity of tweets and classified into Positive (> +0.3), Neutral (+0.3 to -0.3) and Negative (<-0.3) labels. 
Here are some interesting finds from the analysis: 
1. new cases, cases death, positive case, confirmed cases were the most common words used in tweets.
2. Covid-19, particularly the year 2020 saw an almost 100 percent increase  in the new twiiter account creation as compared to 2018.
3. NLTK Vadar performed better label classification than TextBlob.
4. Linear SVC model provided a better accuracy of 81% than Multinomial NB at 75.6%.
5. Contrary to the popular belief, the overall sentiment of the people according our project was Neutral. 
