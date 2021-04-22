# NMT
English to Spanish Neural Machine Translation using PyTorch

- Imported Libraries and downloaded the necessary files
- Dataset: Corpus of parallel sentences extracted from Wikipedia by Krzysztof Wołk and Krzysztof Marasek [here](https://opus.nlpl.eu/)
- Converted the data into model acceptable format
- Cleaning the data
  - Converting into ASCII from Unicode
  - Lower casing the strings
  - Removing punctuation 
  - Filtering out the sentences longer than the accepted length
- Making One Hot encoded vectors for the languages
  - Filtering out infrequent words
  - Made functions to convert to and from one hot encoded vectors
- Using mini batch gradient descent technique to reduce error
- Padding the sentences to make each batch of same length
