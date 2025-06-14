# LLM-preprocessing

This notebook includes a full text preprocessing pipeline to clean and prepare raw chat/text data for training or using Large Language Models (LLMs).

🧹 Steps covered:

Lowercasing text

Removing HTML tags (<br>, <p>, etc.)

Normalizing chat words (e.g., "u" → "you", "gr8" → "great")

Correcting spelling using TextBlob

Removing stopwords

Tokenization

Lemmatization (using SpaCy)

🔍 The result is clean, meaningful input ready for use in LLMs like BERT, GPT, or custom fine-tuning tasks.
