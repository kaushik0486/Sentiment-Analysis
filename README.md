# Sentiment-Analysis # Text Sentiment Analysis

Create a program that performs sentiment analysis on a given text. Given a piece of text, the program will determine whether the sentiment of the text is positive, negative, or neutral.

## Example

Input: "I absolutely loved the movie! The acting was brilliant."
Output: Positive sentiment

## How to Use

1. Clone this repository.
2. Open a terminal or command prompt.
3. Navigate to the repository's directory.
4. Compile and run the solution code (see below).

## Solution

The solution is implemented using [Python](https://www.python.org/) and a simple sentiment analysis approach. The `analyze_sentiment` function takes a text as input and uses predefined keywords and patterns to determine the sentiment.

### Usage

```python
def analyze_sentiment(text):
    # Perform sentiment analysis and return the sentiment (positive, negative, neutral)

input_text = "I absolutely loved the movie! The acting was brilliant."
sentiment = analyze_sentiment(input_text)
print("Sentiment:", sentiment)
