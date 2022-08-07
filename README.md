## Machine Learning models for Natural Language Processing (NLP)

This repository contains the course materials for the course on Machine Learning
for NLP, taught by Sameer Singh for UCI's 
[Summer School on Computational Cognitive Modeling for Language Summer School 2022](https://www.langsci.uci.edu/summerschool.php).
Each session is 90 min long and consists of 45-60 min theory and 30-45 min of interactive notebooks.

The interactive notebooks focus on providing the tools for the students to explore
the limitations and surprising behaviors of the different computational models used
in NLP. Framework-wise, the notebooks rely on Open AI's API, HuggingFace `transformers`, and HuggingFace Hosted Inference API (day 5). The notebooks were run in the free-tier Google Colaboratory notebooks. 

Here is the list of the notebooks:

- [Day 1. Introduction to NLP](./Day1_Introduction_to_NLP.ipynb): a brief walkthrough over some NLP tasks including NLI, automatic question generation, and story-telling with large language models.
- [Day 2. Word Embeddings](./Day2_Word_Embeddings.ipynb): GloVe word embeddings visualization, word analogies, and working with cross-lingual embeddings using MUSE.
- [Day 3. Masked Language Modeling](./Day3_Masked_Language_Models.ipynb): comparing BERT and RoBERTA models using fill-in-the-blank tasks. Optionally, use T5 to perform fill-in-the-blank tasks, as well.
- [Day 4. Left-to-Right (or Causal) Modeling](./Day4_Text_Generation_Models.ipynb): analyse GPT-3 and GPT-2 models generation capabilities.
- [Day 5. Zero-shot and Few-shot Learning](./Day5_Zero_Few_Shot.ipynb): zero- and few-shot capabilities of large language models (including GPT-3, T0, and TK-Instruct-3B).

For more information (including slides), please consult the [Official Course Webpage](http://sameersingh.org/courses/ml4nlp/su22/).