
## 1.Introduction to the Corpus
The corpus comprises the lyrics of the top 20 most-viewed songs by the singer Lana Del Rey on the Genius platform. These lyrics were obtained by downloading them from web pages dedicated to each song.
## 2.Target Audience and Intended Use:
The target audience for this corpus could be researchers, linguists, music enthusiasts, or developers working on natural language processing (NLP) or sentiment analysis. 
## 3.Text Selection Criteria:
The selection criteria for including songs in this corpus were based on the popularity and viewership metrics on the Genius platform. The top 20 songs were chosen based on the highest number of views to represent the most widely listened-to tracks by Lana Del Rey.
## 4.Data Collection Process:
Data Collection Process: Downloaded from a lyrics website based on song rankings(authorized by the website).
## 5.Annotations and Tools:
Python Libraries: os, spacy, pandas: Python libraries used for file handling, natural language processing, and data structuring.
SpaCy's en_core_web_sm Model: A natural language processing model used for tokenization, lemmatization, and part-of-speech tagging of the text.
## 6.Description of the Columns
| Column     | Description                                                                                      |
|------------|--------------------------------------------------------------------------------------------------|
| Filename   | Names or unique identifiers of Lana Del Rey songs from which lyrics were extracted.              |
| Song Title | Cleaned song titles extracted from the filenames, excluding the "| Genius Lyrics" part.         |
| Tokens     | Individual words, punctuation, and meaningful units extracted from the lyrics.                    |
| Lemmas     | Lemmatized forms of tokens, representing base or dictionary forms of words.                       |
| POS        | Parts-of-Speech categories assigned to each token, indicating grammatical roles in the text.       |
| Document   | The original text exactly as it appears in the text file.                                         |


