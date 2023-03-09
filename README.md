# NLP-Sentiment-Analysis
Sentiment Analysis about Disneyland Reviews Dataset

## Step by step explanation:

### 1. Data Manipulation: 
This step contains reading data and checking its shape, type and non null value count in each column.

### 2. Data Pre-Processing:
Following pre processing is done on the reviews text:
- Handling null and missing values
- Dropping unnecessary columns
- Converting to lower case
- Removing punctuation
- Removing numerical values
- Removing Stopwords
- Lemmatization (Morphological analysis to reduce a word to its base word or lemma)
- Word Tokenization (Splitting a phrase or sentence in its individual words called tokens)
              
### 3. Data Visualization:
In this step of the project, the data is visualized by:
- Creating Word Cloud
- Creating Barplot of most common words
- Creating Pie plot of most common words
- Plotting rating of the reviews
- Plotting number of reviews from each brach
- Lineplot of rating over the years
                 
### 4. Sentiment Analysis:
The library used here for sentiment analysis is TextBlob. After analysis , a new column named Sentiment is appended to the dataframe. The result is visualized in the form of a barplot showing positive and negative sentiments.

              
