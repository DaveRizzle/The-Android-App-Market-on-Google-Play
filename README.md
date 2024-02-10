# Google Play Store Apps and Reviews Analysis

In this project, we embark on a comprehensive analysis of the Android app market by examining over ten thousand apps on Google Play across different categories. The objective is to derive insights into app preferences, performance, and market dynamics, which can aid developers and companies in strategizing for growth and retention.

## Dataset Overview

The analysis leverages two datasets:
- `apps.csv`: Contains details of applications on Google Play. It includes 13 features such as App, Category, Rating, Reviews, Size, Installs, Type, Price, and more.
- `user_reviews.csv`: Comprises 100 pre-processed reviews for each app, annotated with Sentiment (Positive, Negative, Neutral), Sentiment Polarity, and Sentiment Subjectivity.

## Key Insights

1. **Data Cleaning and Preparation**: Special characters in the `Installs` and `Price` columns were removed to convert them into numeric types, facilitating further analysis.

2. **App Categories Analysis**: The dataset revealed 33 unique app categories, with Family and Game apps dominating the market. A significant prevalence of Tools, Business, and Medical apps was also observed.

3. **App Ratings Distribution**: The average app rating across categories was found to be 4.17. The distribution is left-skewed, indicating that a majority of the apps are highly rated.

4. **Impact of App Size and Price**: Analysis showed that top-rated apps (rating > 4) mainly range from 2 MB to 20 MB in size, and most apps price themselves under $10. This suggests that users prefer apps that are affordable and do not consume excessive storage.

5. **Pricing Trends Across Categories**: Categories such as Medical and Family contain the most expensive apps, some extending up to $80. However, game apps are generally priced below $20, indicating category-specific pricing strategies.

6. **Filtering Out Junk Apps**: Apps priced above $200 were identified as "junk" apps and filtered out to focus the analysis on genuine, functional apps.

7. **Popularity of Paid vs. Free Apps**: Despite the common perception, paid apps do see a substantial number of installs, though free apps dominate in terms of download numbers. This highlights the competitive nature of the free app market but also suggests a viable niche for paid apps.

8. **Sentiment Analysis of User Reviews**: Free apps receive a wide range of feedback, including harsh comments, as indicated by the sentiment polarity scores. Paid apps, conversely, tend to have more moderated feedback, hinting at higher average quality or user expectations.

## Conclusions

The analysis provides valuable insights into the Google Play Store's app ecosystem. Key takeaways include the dominance of specific app categories, the critical role of app ratings in discoverability and popularity, the influence of app size and price on user preference, and the nuanced differences in user feedback between paid and free apps. These insights can inform developers and companies in making strategic decisions regarding app development, pricing, and marketing to enhance user engagement and profitability.

This project underscores the importance of data-driven decision-making in the competitive app market and highlights the potential for targeted strategies to drive growth and user satisfaction.
