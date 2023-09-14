# Text-Improvement-Engine
This is an assignment for the position of Machine Learning Engineer at Compound Solutions SL.

## Features

- **Data Input**: Allows users to input text from a text file.
- **Standardized Phrases**: Pre-loads the tool with a list of standardized phrases (e.g., business jargon, scientific terminology, etc.).
- **Text Analysis**: Utilizes a pre-trained language model to find phrases in the input text that are semantically similar to any of the standard phrases.
- **Suggestions**: Provides a list of suggestions to replace non-standard phrases in the input text with their more "standard" versions, along with similarity scores.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed
- Required Python libraries: `nltk` and `scikit-learn`

```
pip install nltk scikit-learn
```

## Customization
You can customize the list of standardized phrases and their similarity thresholds by editing the standardized_phrases list in the Text Improvment Engine.py directory.

## Example
**Input Text:** In today's meeting, we discussed a variety of issues affecting our department. The weather was unusually sunny, a pleasant backdrop to our serious discussions. We came to the consensus that we need to do better in terms of performance. Sally brought doughnuts, which lightened the mood. It's important to make good use of what we have at our disposal. During the coffee break, we talked about the upcoming company picnic. We should aim to be more efficient and look for ways to be more creative in our daily tasks. Growth is essential for our future, but equally important is building strong relationships with our team members. As a reminder, the annual staff survey is due next Friday. Lastly, we agreed that we must take time to look over our plans carefully and consider all angles before moving forward. On a side note, David mentioned that his cat is recovering well from surgery.
___
**Recommended:** Optimal performance
**Similarity Score:** 0.05

## Acknowledgments

## Contributors
- Nurserik Orynbaev orynbaevnurserik05@gmail.com
