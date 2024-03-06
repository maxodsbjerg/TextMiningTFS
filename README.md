# Text Mining Analysis of Trykkefrihedens Skrifter

This repository contains the results of a text mining analysis conducted on Trykkefrihedens Skrifter using R programming language. Text mining involves extracting meaningful insights and patterns from textual data.

https://tekster.kb.dk/text?editorial=no&f%5Bsubcollection_ssi%5D%5B%5D=tfs&match=one&search_field=Alt


## Overview

Text mining techniques were applied to the Trykkefrihedens Skrifter dataset to uncover valuable information and trends within the text. The analysis aimed to understand the language, themes, and patterns present in the Skrifter.

## Methodology

1. **Loading Data**: The dataset was loaded from a CSV file named "tfs_structured.csv".

2. **Converting to Tidy Text Format**: The text data was transformed into a tidy format suitable for analysis using R packages like tidyverse and tidytext.

3. **Initial Analysis**: Basic analyses were performed to count word frequencies and understand the distribution of words in the text.

4. **Handling Stopwords**: Common stopwords in Danish and German languages, as well as project-specific stopwords, were identified and removed from the text data to focus on meaningful words.
5. **Keywords in Context (KWIC) Analysis**: A KWIC analysis was conducted to explore the context in which specific keywords appear in the text documents.

6. **Bigrams Analysis**: Bigrams, or word pairs, were analyzed to identify associations and patterns in the text.

7. **Saving Results**: The results of the analysis, including visualizations and insights, were saved for further reference and analysis.

## Conclusion

The text mining analysis provided valuable insights into the language, themes, and patterns present in Trykkefrihedens Skrifter. It revealed significant associations between words, common themes, and contextual usage of keywords. These findings contribute to a better understanding of the content and context of the Skrifter dataset.
