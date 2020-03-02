This module identifies sentiment of the text using AFINN-based sentiment analysis (https://github.com/thisandagain/sentiment), and writes it to the context in the form

```json
{
  "sentiment": {
    "score": 3,
    "comparative": 0.75,
    "calculation": [
      {
        "nice": 3
      }
    ],
    "tokens": [
      "nice",
      "to",
      "meet",
      "you"
    ],
    "words": [
      "nice"
    ],
    "positive": [
      "nice"
    ],
    "negative": []
  }
}
```