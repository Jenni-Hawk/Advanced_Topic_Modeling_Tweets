# Advanced_Topic_Modeling Research

## Objectives: 
- How does deep learning compare to classic machine learning models for topic modeling? 
- Which model(s) bring the best human comprehension to the topics it defines? 
- Which model(s) can make us feel most confident that they're accurately defining the topics? 
- Can OpenAI create an improvement in model performance?  


## Methodology:
Algorithms being tested:
LSA with TF-IDF, BERTopic, and ChatGPT-4.

- Each algorithm will be scored based on how humans interpret the coherence of the topics. 
- A random sampling of content is taken from each topic. 'Intruder' content is randomly injected into this content. Humans are asked to identify the intruder content. Scoring is based on how many times humans can correctly identify the intruder content. This indicates the strength of coherence of a topic that an algorithm creates.   


