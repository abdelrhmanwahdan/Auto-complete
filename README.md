# Auto complete

![Auto complete](./images/stanford.png "Auto complete")


In this project, we will build an auto-complete system.  Auto-complete system is something you may see every day
- When you google something, you often have suggestions to help you complete your search. 
- When you are writing an email, you get suggestions telling you possible endings to your sentence.  

By the end of this project, we will develop a prototype of such a system.
 

# Contents
1. Load and Preprocess Data
    - Load the data
    - Pre-process the data
        - split to sentences
        - tokenize sentences
        - get tokenized data
        - count words
        - get words with nplus frequency
        - replace oov words by unk
        - preprocess data
2. Develop n-gram based language models
    - count n-grams
    - create transition matrix
3. Perplexity
    - calculate perplexity
4. Build an auto-complete system
    - suggest a word

# Credits

- NLP specialization by Deeplearning.ai on coursera