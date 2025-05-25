# Data-and-Text-Mining

Text Mining on Journal Abstracts (2000–2022)

This project performs a comprehensive text mining analysis on 4385 article abstracts from three journals: Journal of the Operational Research Society, Health Systems, and Simulation Journal. It includes the following steps:

Preprocessing: Tokenization, cleaning, lowercasing, stop-word removal, stemming, and lemmatization.

Bag-of-Words & TF-IDF: Extracted top words and classified them into thematic categories.

Topic Modeling (LDA): Identified three main research topics and tracked their trends over time.

Regression Analysis: Built a multiple linear regression model to predict citation counts, with 'views' as the strongest predictor.

Classification & Association Rules: Performed text-based journal classification and mined co-occurrence rules like {monte} => {carlo}.

Clustering (K-means): Grouped abstracts into 3 main clusters based on TF-IDF features.

Dimensionality Reduction (PCA): Visualized the data structure in 2D space.

📉 Key findings include:

Medical and health research increased over time.

Simulation and optimization topics remain consistent.

Citation prediction has high variance and weak fit.

Classification accuracy reaches 87%, with category imbalances.

This project demonstrates the application of various NLP and data mining techniques for scientific literature analysis.
