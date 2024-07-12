# CC-Task2-RAG

Retrieval-Augmented Generation (RAG) model to retrieve and generate information from placement and SI chronicles. The model first decomposes a question into 5 sub-questions. Each sub-question is answered indpendently using HyDE to efficently retrieve relevant documents. The sub-questions and their respective answers are given to the LLM in the form of QA pairs to be used as context to answer the main question. 
