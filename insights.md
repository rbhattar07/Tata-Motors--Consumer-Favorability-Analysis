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