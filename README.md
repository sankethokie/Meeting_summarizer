# Meeting_summarizer
Augmented Intelligence based Virtual Meeting User Experience

This project implements an Augmented Intelligence system for improving virtual meeting user experience.

It processes meeting transcripts (CSV/Pandas DataFrame) and automatically generates:

Meeting summary (Extractive TextRank)
Action items (regex + heuristic AI detection)
Keywords & important topics (TF-IDF scoring)
Speaker statistics (talk-time, sentiment, turns)
Follow-up suggestions based on detected tasks
Saves JSON + CSV outputs
Shows a complete summary directly in your Jupyter Notebook

This edition is designed to work 100% offline and inside corporate firewalls, with no spaCy, no NLTK downloads, no HuggingFace, and no external dependencies beyond lightweight Python libraries.
