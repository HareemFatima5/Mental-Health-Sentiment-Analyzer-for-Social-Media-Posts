# Mental Health Sentiment Analyzer for Social Media Posts

This project uses Natural Language Processing (NLP) and Machine Learning to analyze and classify social media posts based on their sentiment regarding mental health.
The goal is to help identify posts that may indicate mental health issues, promote awareness, and assist in early intervention.


## Features

- Text preprocessing (lowercasing, tokenization, stopword removal, lemmatization)
- TF-IDF vectorization
- Model training with:
  - Logistic Regression
  - Random Forest
- Performance metrics (Accuracy, Precision, Recall, F1-Score)
- Confusion matrix visualization

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Mental_Health_Sentiment_Analyzer.git
cd Mental_Health_Sentiment_Analyzer
```

### Download required NLTK resources:

```bash
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
```

## How to Use
Open the Jupyter Notebook:

'''bash
jupyter notebook Mental_Health_Sentiment_Analyzer_for_Social_Media_Posts.ipynb
```
- Run all cells sequentially.
- Review model performance and confusion matrices.
- Modify and test with your own text data if needed.

## Future Improvements
- Live integration with Twitter API or Reddit API
- Deploy as a web app using Flask or Streamlit
- Use deep learning models (e.g., BERT)
- Multilingual support
