Project 1 — Levenshtein Distance (Edit Distance)

Implements the Levenshtein distance algorithm using Dynamic Programming to calculate the minimum number of edits required to transform one string into another.

Features

Supports insertion, deletion, substitution operations

Uses DP matrix for efficient computation

Example

Input: START → STARE
Output: Edit Distance = 1


📌 Based on DP table comparison between characters. 

Project1

🔹 Project 2 — Sentence Cleaning & Basic NLP Preprocessing

Performs text cleaning using:

Lowercasing

Regex word extraction

Stop word removal

Simple stemming using mapping

Example Processing

Input: The quick,Brown foxes... they are JUMPING over 10 lazy dogs!
Output: ['quick', 'brown', 'fox', 'jump', 'lazy', 'dogs']


📌 Uses regex and dictionary-based stemming. 

Project2

🔹 Project 3 — Spam Detection (Keyword Based)

Simple spam classifier using keyword matching.

Spam Keywords

win

free

prize

click here

subscribe now

Output

Returns "spam" if spam words detected

Otherwise "not spam"

📌 Uses case-insensitive keyword search. 

Project3

🔹 Project 4 — Text Cleaning for Sentiment Analysis

Prepares text for sentiment analysis by removing:

Hashtags

Special characters

Stop words

Example

Input: I Love this movie!!! #awesome
Output: ['i', 'love', 'movie']


📌 Uses regex filtering and tokenization. 

Project4

🔹 Project 5 — Advanced Distance + Keyboard Error Weighting

Contains:

Standard Levenshtein Distance

Weighted Keyboard Distance (accounts for nearby keyboard mistakes)

Example

Typed: HELLP
Correct: HELLO


Suggests correction if weighted distance is lower than standard edit distance.

📌 Useful for typo correction systems.
