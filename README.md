# Project Name: Flavourful Insights

**Problem Statement:** We discovered that patrons of a certain restaurant frequently ponder what to order. To address this, we conducted a comprehensive analysis of customer reviews.

**Approach:** I employed a two-pronged approach to comprehensively understand the restaurant: first, summarizing its key offerings and overall concept, and second, identifying its most distinct and noteworthy highlights.

**Approach 1:** Sentiment Analysis and Text Summarization
    Sentiment Analysis: We employed VADER sentiment analysis to categorize reviews into positive and negative sentiments.
    Text Summarization: Subsequently, we performed text summarization on the positive and negative reviews separately, yielding comprehensive summaries that              encapsulate both positive and negative aspects of the restaurant.

**Approach 2:** Topic Modeling and Detailed Sentiment Analysis
    Data Cleaning: Reviews were meticulously cleaned by converting text to lowercase, removing punctuation and emojis, and applying lemmatization.
    Topic Modeling: Utilizing Latent Dirichlet Allocation (LDA), we identified four primary topics: food, service, ambience, and price.
    Sentiment Analysis: We conducted sentiment analysis using BERT, which provided positive and negative sentiments for each identified topic.
    POS Tagging: To extract detailed highlights, we used Part-of-Speech (POS) tagging to identify dish names, adjectives, and other relevant parts of speech,             enabling us to associate specific highlights with each topic.
    Analysis Techniques: We employed topic modeling and sentiment analysis to identify key themes and sentiments expressed in the reviews.

**Actionable Summaries:** Based on our findings, we created concise and actionable summaries with highlights, designed to empower both diners and restaurant owners.
This project not only enhances the dining experience for customers but also provides valuable insights for the eatery to improve its offerings.
