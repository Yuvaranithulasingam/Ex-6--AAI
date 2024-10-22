### NAME :
### REGISTER NO :
### DATE:

## EX. NO.6         Implementation of Semantic ANalysis

### Aim: 
To perform Parts of speech identification and Synonym using Natural Language Processing (NLP) techniques.

### Algorithm:
Step 1: Import the nltk library.</br>
Step 2: Download the 'punkt', 'wordnet', and 'averaged_perceptron_tagger' resources.</br>
Step 3:Accept user input for the text.</br>
Step 4:Tokenize the input text into words using the word_tokenize function.</br>
Step 5:Iterate through each word in the tokenized text.</br>
•	Perform part-of-speech tagging on the tokenized words using nltk.pos_tag.</br>
•	Print each word along with its corresponding part-of-speech tag.</br>
•	For each verb , iterate through its synsets (sets of synonyms) using wordnet.synsets(word).</br>
•	Extract synonyms and antonyms using lemma.name() and lemma.antonyms()[0].name() respectively.</br>
•	Print the unique sets of synonyms and antonyms.</br>

### Program :
```

<H3>Output</H3>

Show your results here

<H3>Result:</H3>
Thus ,the program to perform the Parts of Speech identification and Synonymis executed sucessfully.
