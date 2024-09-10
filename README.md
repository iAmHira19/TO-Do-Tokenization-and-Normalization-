# Word Tokenization and Normalization Assignment

## Overview
This project involves generating 10 text files, each containing two sentences, followed by word tokenization and normalization. The project is implemented in Python using the NLTK library and runs in Google Colab.

## Steps Performed
1. **Generate 10 Files**  
   Each file contains two sentences, stored in a folder called `generated_files`.
   
2. **Word Tokenization**  
   Each file's content is split into individual words using the `nltk.tokenize.word_tokenize` function.
   
3. **Normalization**  
   The following normalization steps are performed:
   - Convert words to lowercase.
   - Remove punctuation.
   - Remove common English stopwords using NLTK’s stopword list.
   - Lemmatize words using the WordNet Lemmatizer to bring words to their base form.

## Requirements
- Python 3.x
- Libraries: 
  - `nltk`
  
Run the following commands in Google Colab to install necessary libraries:

```python
!pip install nltk
```

## How to Run
1. Clone this repository or download the code.
2. Open the project in Google Colab.
3. Run the Python script to generate the files and process the text.

## Output
The script will output the tokenized and normalized text for each of the generated files.

## Example of Tokenized and Normalized Output:
```python
['first', 'sentence', 'second', 'sentence']
['python', 'powerful', 'programming', 'language', 'widely', 'used', 'data', 'science']
```

## License
This project is licensed under the MIT License.
