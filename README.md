# Fake_News_Detection_JeyaprakashR_NehaGarg
This project aims to detect fake news using semantic classification. By leveraging Word2Vec embeddings, it captures the meaning of words in news articles and uses supervised learning models to classify them as real or fake. The focus is on understanding context rather than relying on just keywords.

## Models and Techniques

### Models Used
- **Random Forest:** An ensemble method that builds multiple decision trees and combines their results for higher accuracy and stability.
- **Logistic Regression:** A linear model that predicts the probability of fake or real news.
- **Decision Tree:** A simple, interpretable model that classifies news by splitting data based on feature values.

### Key Techniques
- **Word2Vec Embeddings:** Converts words into numerical vectors capturing their semantic meaning based on context.
- **Noun Extraction & Lemmatization:** Using spaCy, only important nouns are extracted and reduced to their base forms to focus on relevant content.
- **Feature Engineering:** Each news article is represented by averaging the Word2Vec vectors of its nouns, producing a semantic summary.
- **Supervised Learning:** Models are trained on these semantic features to classify news as fake or real.
