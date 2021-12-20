# Multi-Hop_QA_SentenceEncoders_KnowledgeGraphs
This is the official repository for the Capstone Project for Araz Sharma, Rudra Prasad Baksi &amp; Pranav Raj, for Btech 2022 CSE, PES University, Bangalore


Our domain is the popular problem of Question Answering. QA has been a long-term focus in artificial intelligence that can date back to the 1960s. This is also popularly known as Machine Reading Comprehension. The task here is to answer questions based on a given comprehension, which is essentially a textual document of a length of a certain number of paragraphs. This is similar to the Comprehension Based Questions given in examinations, to students across the world. Our work aims to explore how different sentence embeddings can be used, on a similarity of sentences level basis, to answer multi-hop questions from the Multi-RC Dataset. We have done a comparative study between 3 popular sentence embeddings – USE, Siamese BERT \& InferSent. We have also generated Knowledge Graphs for the comprehensions, to try to leverage Graph Convolutions, to enrich embeddings, to find the answer sentences for the Multi-RC Dataset. Our work suggests, that we can use Graph Neural Networks with pre-trained sentence embeddings, like USE, to answer Multi-Hop QA, in the future, to surpass the current benchmarks. 

## Files and Data

1. The main files are the 2 Jupyter Notebooks:
- A.  Capstone-Demonstration-Report: This contains all the code for generating Knowledge Graphs, and the Algorithms run to test the embeddings on the metrics
- B. Generate Infersent Embeddings: This notebook shows how the Infersent Model was used to generate the embeddings

2. The Data folder contains all the paragraph sentences and questions in text files, used to generate the Knowledge Graphs.
3. The Graphs folder contains all the KGs generated for the Training Multi-RC Dataset. The code to generate this is present in the Capstone-Demonstration-Report.ipynb
4. USE and BERT Embeddings are present in their respective folders
5. Questions and Paragraph JSONs contain the training data of Multi-RC in JSON format, which has been formatted for ease in parsing
6. Answers.JSON was used while testing the embeddings, on the metrics designed by us


## Contact

Feel free to contact us at arazsharma1103@gmail.com or rudranger@gmail.com for any queries or questions

### Have a Nice Day! :)
