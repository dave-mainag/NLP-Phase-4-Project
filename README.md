# NLP-Phase-4-Project
NLP-Phase-4-Project

Sentiment Analysis for Product Stocking: NLP Insights for Best Buy

Introduction Best Buy, a major retailer of iPhone and Google products, aims to optimize stocking decisions through Twitter sentiment analysis. This project delves into understanding customer sentiments to align stocking strategies with demand and enhance satisfaction.

Problem Statement Best Buy faces challenges in aligning stocking decisions with customer preferences due to a lack of systematic sentiment analysis. Leveraging Twitter sentiment analysis can address this gap, improving stocking decisions and enhancing loyalty.

Business Value By leveraging sentiment analysis, Best Buy can allocate resources efficiently, enhance product assortment, and increase customer satisfaction and profitability. Understanding customer sentiments better than competitors can position Best Buy as a preferred destination for iPhone and Google products.

Objectives: This project aims to analyze customer sentiments on Twitter to inform Best Buy's stocking decisions, optimizing resource allocation, product assortment, and customer satisfaction to drive profitability.

Data Source: https://data.world/crowdflower/brands-and-product-emotions

Research Questions

What are the predominant sentiments expressed by customers regarding iPhone and Google products on Twitter?
What factors influence the polarity of tweets related to iPhone and Google products?
Which specific features of iPhone and Google products are frequently praised or criticized on Twitter?
Which machine learning model is most effective in sentiment analysis?
Data Description The dataset comprises three columns: tweet_text, emotion_in_tweet_is_directed_at, and is_there_an_emotion_directed_at_a_brand_or_product. Data cleaning involved handling missing values, standardizing emotion labels, and removing duplicates.

Exploratory Data Analysis (EDA) EDA included visualizing brand/product distribution, tokenization, frequency distribution of tokens, emotion/sentiment class distribution by brand, and word cloud representation to gain insights into customer sentiments.

Feature Engineering Feature engineering involved vectorization with TfidfVectorizer, one-hot encoding brand_product column, and appending encoded brand column to TF-IDF matrices.

Baseline Model Evaluation Naive Bayes and Decision Tree classifiers were evaluated on regex and lemmatized data. Random Forest, XGBoost, and Support Vector Classifier were also assessed. Addressing class imbalance with SMOTE significantly improved model performance.

Findings Customer sentiment analysis on Twitter reveals Google and Apple brands garnering neutral and positive emotions, with minimal negativity. The SXSW event and new product releases coincide with increased positive sentiment. Negativity towards iPad design contrasts with positive feedback for the Apple Store. iPhones and iPads evoke the highest positivity, while Android devices and Google Maps receive significant mentions. The Random Forest and Decision Tree classifiers excel, achieving 97% accuracy, 99% precision, and 100% recall post-resampling, enhancing overall classifier performance.

Recommendations Recommendations include implementing real-time sentiment monitoring, tailoring marketing campaigns, utilizing significant events, adjusting product assortment, interacting with social media users, and using sentiment analysis insights for product development.

Conclusion Random Forest and Decision Tree classifiers emerged as top performers, achieving remarkable metrics after SMOTE resampling. Leveraging sentiment analysis insights can help Best Buy customize stocking decisions, leading to increased sales and customer satisfaction.

Next Steps Future steps involve implementing ongoing monitoring and maintenance of deployed models to ensure accuracy and relevance. Regular assessment and fine-tuning will be essential to adapt to evolving business requirements and customer behaviors.
