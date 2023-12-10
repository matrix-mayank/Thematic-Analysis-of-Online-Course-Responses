# Thematic-Analysis-of-Online-Course-Responses
This Python script was designed for analyzing textual responses from two questions in an online course focused on Digital Intercultural Competence. The primary goal is to uncover major themes within the participant responses.

## Libraries Used
**re:** For regular expressions.
**pandas:** For data manipulation and analysis.
**numpy:** For numerical operations.
**matplotlib and seaborn:** For data visualization.
**string:** Additional tools for manipulating strings.
**warnings:** To suppress warning messages.
**spacy:** A natural language processing library.
**nltk:** The Natural Language Toolkit for various text processing tasks.
**yellowbrick:** For visualizing part-of-speech tags.
**autocorrect:** For spell-checking.
**pointofview:** A library for determining the point of view in text.
**sklearn:** For machine learning tasks.
**en_core_web_sm:** Spacy's English language model.

## Data Loading and Merging
Loads and merges responses from two questions in the Digital Intercultural Competence course.

## Data Cleaning
1. Removes duplicates, empty responses, and irrelevant phrases.
2. Eliminates specific phrases ('Reply', 'Show original comment', '2019') and special characters.
3. Applies spell-checking to enhance text quality.

## Part-of-Speech Tagging and Visualization
1. Uses NLTK for part-of-speech tagging.
2. Visualizes part-of-speech tags using Yellowbrick.

## Dependency Parsing
1. Applies spaCy for dependency parsing.
2. Renders dependency parse trees for better understanding.

## Shallow Parsing
1. Defines rules to extract specific syntactic structures (Adjective Noun and Verb Adjective/Noun structures).
2. Applies rules to identify patterns within the text.

## Term Frequency Analysis
1. Uses CountVectorizer to analyze the most common words and phrases.
2. Visualizes the 10 most common words to identify recurring themes.

## Lemmatization
1. Lemmatizes the text to reduce words to their base or root form.

## TF-IDF Vectorization and K-Means Clustering
1. Applies TF-IDF vectorization to convert text data into numerical form.
2. Utilizes K-Means clustering to group similar responses and identify major themes.
3. Presents the top terms within each cluster.
