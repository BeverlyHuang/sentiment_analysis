# Sentiment Analysis: Amazon Comprehend vs Cloud Natural Language

By Beverly Huang

### Goal
This project aims to compare and apply the NPL APIs for sentiment analysis. Both Amazon Comprehend and Google Cloud Natural Language will be explored in this project.

### Conclusion
Both AWS and GCP have NLP API tool to analyze the sentiment of text. This project uses a hotel review dataset as an example to demonstrate how to use Amazon Comprehend and Cloud Natural Language for sentiment analysis. Both can effectively identify positive and negative sentiment in hotel reviews.
For Amazon Comprehend, we can get the sentiment score for "Positive", "Negative", "Neural" and "Mixed", then the sentiment with the highest score determines the sentiment for the review. For Cloud Natural Language, we can get one sentiment score. This score determines the degree that this sentiment is "Positive", "Negative" or "Neural". We can also get a magnitude which indicates the emotion of the review.
