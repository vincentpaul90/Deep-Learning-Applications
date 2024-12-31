
# Pfizer Vaccine Sentiment Analysis

This repository contains a Python-based sentiment analysis project on Twitter data related to the Pfizer COVID-19 vaccine. The project demonstrates data preprocessing, sentiment classification, and visualization of sentiments using Python libraries like `pandas`, `seaborn`, `TextBlob`, and `wordcloud`.

## Dataset

The dataset used in this project contains tweets related to the Pfizer vaccine. The data is cleaned and processed to extract insights about public sentiment. The original dataset can be sourced from [The Clever Programmer](https://thecleverprogrammer.com/2021/10/12/pfizer-vaccine-sentiment-analysis-using-python/), or use the dataset included in this repository.

## Features

1. **Data Cleaning:**
   - Removes mentions, URLs, special characters, and numbers from tweets.
   - Converts text to lowercase for consistency.

2. **Sentiment Analysis:**
   - Uses `TextBlob` to classify tweets as Positive, Negative, or Neutral based on polarity scores.

3. **Visualization:**
   - Distribution of sentiments using bar plots.
   - Word clouds for positive and negative sentiments.

4. **Tokenization:**
   - Tokenizes tweets and removes stop words to extract meaningful words.

5. **Common Words Analysis:**
   - Identifies the most common words used in positive and negative tweets.

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `TextBlob`
- `wordcloud`
- `nltk`
- `sklearn`

## Steps to Run the Notebook

1. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn textblob wordcloud nltk scikit-learn
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Pfizer vaccine sentiment analysis using twitter data.ipynb"
   ```

3. Execute the cells step by step to:
   - Load and preprocess the data.
   - Perform sentiment analysis.
   - Visualize the results.

## Results

- The analysis reveals the distribution of public sentiment (Positive, Negative, Neutral) towards the Pfizer vaccine.
- Word clouds and tokenized word lists highlight the most frequently used words in tweets.

## Example Visualizations

- **Sentiment Distribution:**
  ![Bar Plot Example](example_bar_plot.png)

- **Word Cloud for Positive Sentiment:**
  ![Word Cloud Example](example_wordcloud_positive.png)

## Contributions

Feel free to contribute to this project by:
- Improving data preprocessing.
- Exploring other sentiment analysis techniques.
- Adding more visualizations.

## License

This project is open-source and available under the MIT License.

---

If you have any questions or suggestions, feel free to raise an issue or contact the repository maintainer.
