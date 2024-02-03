# Taylor-Swift-Lyrics-Analysis

**Description:**
This Python code analyzes Taylor Swift's lyrics by exploring her references to 'midnight' and expanding the search to track her references to day, night, and time in general. The sentiment analysis is used to study her tone and vibe over her career. The final goal is to determine if she writes more favorably about day or night.

**Usage:**
1. **Import Libraries:** The code begins by importing necessary libraries such as pandas, seaborn, matplotlib, nltk, and chardet.
2. **Load and Inspect Data:** It uses the chardet library to automatically detect the encoding of a CSV file containing Taylor Swift's lyrics and loads it into a pandas DataFrame.
3. **Clean the Lyrics:** The lyrics are cleaned by converting them to lowercase, removing punctuation, and eliminating stop words.
4. **Find Keywords:** The code identifies the occurrences of specific keywords ('midnight', night-related words, day-related words, and time-related words) in the lyrics.
5. **Visualize and Investigate Data:** The code creates visualizations to show how Taylor Swift's mentions of time have changed over the years and which albums are most focused on night or day.
6. **Sentiment Analysis:** The lyrics are tokenized, and sentiment analysis is performed using the VADER sentiment analyzer to determine the overall sentiment of Taylor Swift's lyrics and compare sentiments between night and day lyrics.

**Libraries Used:**
1. **pandas:** For data manipulation and analysis.
2. **seaborn and matplotlib:** For data visualization.
3. **nltk:** For natural language processing tasks such as tokenization and sentiment analysis.
4. **chardet:** For automatic character encoding detection.

**Note:**
Make sure to have the necessary CSV file ("taylor_swift_lyrics.csv") containing Taylor Swift's lyrics in the working directory before running the code. Additionally, ensure that the required libraries are installed in your Python environment.

**Acknowledgement:**
1. Thanks to [Codecademy](https://news.codecademy.com/song-lyric-topic-analysis-live/) for the step-to-step guide for doing the sentiment analysis.
2. The dataset is from [Kaggle](https://www.kaggle.com/datasets/PromptCloudHQ/taylor-swift-song-lyrics-from-all-the-albums/data).
