# Introduction
## Corpus Description
The Sherlock Holmes Corpus is a collection of texts comprising the works of Sir Arthur Conan Doyle's Sherlock Holmes series. This corpus serves as the foundation for a detailed analysis of proper nouns within the detective fiction genre.
## Target Audience and Intended Use
The primary audience for this corpus analysis includes researchers, linguists, and detective enthusiasts interested in exploring the use of proper nouns in Sherlock Holmes texts. The intended use involves gaining insights into the frequency, context, and varieties of poisonous terms within the detective fiction genre.
## Text Selection Criteria
The texts included in the corpus were selected based on the works of Sir Arthur Conan Doyle's Sherlock Holmes series in digital format from online sources, more specifically from https://www.kaggle.com/datasets/idevji1/sherlock-holmes-stories, due to its large size not analysis available for spaCy and visualization suitable for Github, the dataset was reducted by Yunchi.
## Data Collection and Processing
*See the detailed data collection process above in "text selection criteria".*
For data processing, the texts underwent the following steps:
1. Removal of metadata and non-textual elements;
2. Standardization of text encoding to ensure uniformity;
3. Tokenization, lemmatization and annotation using spaCy for improved analysis.
   The spaCy analysis codes are inspired by turtorial https://spacy.io/usage/spacy-101 and https://programminghistorian.org/en/lessons/corpus-analysis-with-spacy.
## Format of Files in the Corpus
The corpus consists of both plain text (txt) and comma-separated values (csv) files.

Each text file corresponds to a specific work, and the CSV file includes the following columns:

file_name: ID of the Sherlock Holmes work in the corpus.
story_name: Title of the Sherlock Holmes work in the corpus.
discipline: Discipline of the work in the corpus.
type: Literature genre of the work in the corpus.
text: Plain texts of the work in the corpus.
lemmas: Lemmas analyzed by spaCy.
POS: POS analyzed by spaCy.
Proper_nouns:Proper nouns analyzed by spaCy.

# Additional Considerations
Privacy and ethical considerations were taken into account during data collection and analysis.
# Conclusion
This documentation provides an overview of the Sherlock Holmes Corpus, its creation, analysis, and the tools used. It is intended to guide users in understanding the corpus and interpreting the results of the proper nouns analysis.









