# Language detection

This module identifies the language of the text using [language-detection library](https://github.com/newmsz/node-language-detection) for node.js.

## Node: language

The node gives a list of possible languages of the input text and for every detected language its probability.

The results appear in the context in the form:

```json
{
  "language": [
    {
      "lang": "en",
      "prob": 0.8571415388379429
    },
    {
      "lang": "so",
      "prob": 0.14285748315457536
    }
  ],
}
```