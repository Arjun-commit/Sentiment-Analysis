# Sentiment-Analysis

🕸️**Web Scraping:**

Used the requests library to fetch HTML content from a list of URLs.
Parsed the HTML content using BeautifulSoup to extract the relevant text from specific HTML elements.

![ProcessingGIF](https://github.com/user-attachments/assets/61b95004-933c-43a2-a8da-52a1c4a7e901)
**Data Processing:**

>Removed stop words from the scraped text using the nltk library.
>Counted various textual metrics, including:
>Positive and Negative Word Counts: Compared the words in the text against predefined lists of positive and negative words.
>Polarity Score: Calculated the sentiment polarity by comparing positive and negative scores.
>Subjectivity Score: Measured the subjectivity by considering the positive and negative word counts relative to the total word count.
>Average Sentence Length: Computed the average number of words per sentence.
>Complex Word Count: Counted words considered complex based on a predefined list.
>Fog Index: Calculated the readability of the text using the Gunning fog index formula.
>Syllable Count: Counted the number of syllables in each word of the text.
>Personal Pronoun Count: Identified and counted occurrences of specific personal pronouns (like "I", "we", "my").
>Average Word Length: Calculated the average length of words in the text.

🗨️**Text Analysis:**

Implemented functions to assess various characteristics of the text, such as readability, sentiment, and word complexity.

📂**File Handling:**

Read from an Excel file to get the list of URLs for scraping.
Opened text files to read lists of positive, negative, and complex words.

👽**Output to Excel:**

Stored the computed metrics in an Excel file by writing each metric into specific columns.

⚖️**Use of Libraries:**

Utilized several Python libraries like requests, BeautifulSoup, nltk, re, and openpyxl to perform web scraping, text processing, regular expression matching, and Excel file manipulation.
