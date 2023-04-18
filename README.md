# Sentiment Analyzer

This Python script analyzes the sentiment of text files using the VADER (Valence Aware Dictionary and sEntiment Reasoner) algorithm. It calculates a sentiment score for each text file and determines whether the sentiment is positive, negative, or neutral based on the compound score

## Usage

1. Clone this repository to your local machine.
2. Install the vaderSentiment module using pip: `pip install vaderSentiment`.
3. Update the `path` argument in the `analyzer.analyze_sentiment()` method to point to the directory containing your text files.
4. Run the file: `sentimentAnalysisVader.ipynb`.
5. The program will print the sentiment score and sentiment label (positive, negative, or neutral) for each text file in the specified directory.