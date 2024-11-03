# Psycholinguistic Personality Profiling using Latent Dirichlet Allocation and Vader
An analysis on the psycholinguistics of twitter tweets

**Project Description:**

This project explores the application of Natural Language Processing (NLP) techniques, specifically Latent Dirichlet Allocation (LDA) and VADER sentiment analysis, for psycholinguistic personality profiling. 

**Methodology:**

1. **Data Acquisition:**
   - The project utilizes the "MBTI Personality Type Twitter Dataset" available on Kaggle: [https://www.kaggle.com/datasets/mazlumi/mbti-personality-type-twitter-dataset/data](https://www.kaggle.com/datasets/mazlumi/mbti-personality-type-twitter-dataset/data)

2. **Data Preprocessing:**
   - Text cleaning: Removing URLs, mentions, and special characters.
   - Tokenization: Splitting text into individual words.
   - Stop word removal: Eliminating common words that do not carry significant meaning.
   - Lemmatization: Reducing words to their base form.

3. **Topic Modeling with LDA:**
   - Applying LDA to identify latent topics within the text data associated with different MBTI personality types.
   - Visualizing topic distributions using pyLDAvis.

4. **Sentiment Analysis with VADER:**
   - Utilizing VADER to analyze the sentiment expressed in the text data for each MBTI personality type.
   - Comparing average sentiment scores across different personality types.

**Ethical Considerations:**

- **Potential Biases:**
   - It is important to acknowledge that the dataset may contain biases due to the search phrases used for data collection and the self-reported nature of the MBTI personality types.

**Results and Discussion:**

- The project aims to uncover insights into the relationship between language use and personality traits.


**Getting Started:**

**To run this code, you will need to:**

1. **Upload the `kaggle.json` file:**
   - Obtain your `kaggle.json` API key from your Kaggle account settings.
   - Upload this file to your Colab environment.

2. **Upload the `mbti-personality-type-twitter-dataset.zip` file:**
   - Download the dataset from the Kaggle link mentioned above.
   - Upload the zipped dataset file to your Colab environment.

**License:**

This project is licensed under the **MIT License**. See the LICENSE file for details.
