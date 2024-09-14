# NLP-Homeworks

This repository contains my homework assignments for the NLP course. With the exception of the first and fifth homework, all reports are in English, accompanied by the corresponding code. Below is a description of each assignment:

- **HW#1**: Experimenting with various tokenizers and performing sentiment prediction using n-grams.
- **HW#2**: Exploring different text representations, such as Term Frequency (TF), TF-IDF, and Positive Pointwise Mutual Information (PPMI), and applying them to sentiment analysis using a Naive Bayes model. Additionally, building a sarcasm detection model using GloVe embeddings and creating a skipgram-based representation.
- **HW#3**: Performing semantic role labeling using an encoder-decoder architecture. This task was implemented once with LSTMs and once with GRUs. The possibility of switching the task to question answering was also explored, and a model for that was trained.
- **HW#4**: Fine-tuning the RoBERTa-large model for a classification task on the Multi-NLI dataset. Additionally, exploring zero-shot and few-shot performance of the LLaMA3-8B model on the same dataset, with fine-tuning via quantization and p-tuning.
- **HW#5**: Training translation models based on LSTM and Transformer architectures for translation from English to Persian, and evaluating the models using metrics such as BLEU and COMET.
- **HW#6**: Developing a Retrieval-Augmented Generation (RAG) system based on the LLaMA3-70B model, capable of navigating between different response routes: vector space, search engine, and fallback, depending on the query. The vector space is built using the course's source book by Dan Jurafsky. If the question is related to NLP, the system uses the vector store to generate an answer. If it pertains to general computer science, it utilizes the search engine. For other queries, it defaults to a fallback chain.
