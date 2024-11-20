##Song Lyrics Generation with RNNs and MIDI Integration##

This repository presents a deep learning project focused on generating song lyrics aligned with musical melodies. By leveraging recurrent neural networks (RNNs) and integrating features from MIDI files, the model produces lyrics that are both contextually and thematically coherent. This project explores the intersection of music and natural language processing to enhance creative AI applications.

#### Repository Contents:
- **`Song_Lyrics_Generation.ipynb`**: A Jupyter Notebook that contains the code for training, evaluating, and generating song lyrics. The notebook also demonstrates key experimental results and visualizations.
- **`Report.pdf`**: A detailed report outlining the project's objectives, methodologies, experimental configurations, and evaluation metrics.

#### Key Features:
- **Data Integration**: Combines MIDI files for musical data and lyrics datasets, preprocessed using GloVe embeddings for word representations.
- **Model Architecture**: Implements an LSTM-based neural network that integrates musical and lyrical features for sequence generation.
- **Feature Engineering**: Explores three strategies for musical feature extraction—melody-based, instrument-based, and combined features.
- **Metrics and Evaluation**:
  - Linguistic metrics like BLEU, Jaccard similarity, and cosine similarity for text quality.
  - Sentiment analysis and genre classification for thematic alignment.
- **Creative Lyrics Generation**: Employs probabilistic sampling techniques for generating diverse and creative song lyrics.
