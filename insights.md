#
Variables- 21
Observations- 1528
Column data types: float64(7), int64(1), object(13)
# 
Null values: 
- Headline (818) - Entirely By Twitter
- opening text (818) - Entirely By Twitter
- influencer
- subregion (818) - Entirely By Twitter
- reach (9) - Entirely By Twitter
- desktop reach (818) - Entirely By Twitter
- movile reach (818) - Entirely By Twitter
- twitter social echo (818) - Entirely By Twitter
- facebook social echo (818) - Entirely By Twitter
- reddit social echo (818) - Entirely By Twitter
- engagement 
- state
#
Before cleaning the data, I tried to extract the missing headlines & opening text from twitter through the links provided using TWEEPY but I wasnt able to do so because those posts were SUSPENDED. I wanted to extract these few details to ensure that I avoid any data loss & so that I can perform a deeper analysis and validate things.
#
There is only one value type in the country column - India
Removed column Subregion because of large amount of missing values.
# 
Out of 1528 observations: tata (984), hyundai(477), tata & hyundai (67)
#
Mean Sentiment (0.1099): The mean sentiment score is slightly positive (0.1099). This suggests that, on average, the news articles in the dataset tend to express a slightly positive sentiment regarding Tata Motors, Hyundai and the auto industry.
Median Sentiment (0.0): The median sentiment score is 0.0, which means that half of the articles in the dataset have sentiment scores greater than 0.0, and the other half have scores lower than 0.0. NEUTRAL
Standard Deviation of Sentiment (0.6567): The standard deviation measures the degree of variation or dispersion in the sentiment scores. In our case, a standard deviation of 0.6567 suggests that the sentiment scores vary moderately. There is some diversity in how sentiment is expressed in the news articles, ranging from more negative to more positive.


