# Movie-Recommendation-System

The mission
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
You are part of the data team for the Internet Movie Database (IMDB). Your task is to create a recommendation tool for movies and TV shows that an user can interact with.

The tool will take as input the user's favorite movies and shows and recommend new ones in a user friendly manner. You are allowed to use additional resources and incorporate other features that are interesting for users.

The goal is to have a working minimum viable product (MVP) by the end of the project. Each member (or team) in the group should submit a project outline of their MVP on by end of Day 1 to the coach for review and feedback.


Steps:
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. EDA(Exploratory Data Analysis)
EDA stands for Exploratory Data Analysis, which is an approach to analyzing and summarizing a dataset in order to gain insights and identify patterns and relationships between variables.

2. Creating the TF-IDF Matrix
TF

TF stands for Term Frequency and it measures the frequency of a term (i.e., a word or a phrase) in a document. The term frequency of a term t in a document d is calculated as the number of times t appears in d, divided by the total number of terms in d. This calculation normalizes the term frequency by the document length to avoid bias towards longer documents.

TF is commonly used in natural language processing and information retrieval to represent the importance of a term within a document. It can be used in combination with IDF (Inverse Document Frequency) to calculate the TF-IDF score, which provides a measure of the importance of a term across a collection of documents.

IDF

IDF stands for Inverse Document Frequency and it is used to determine how important a word is in a document collection. IDF measures the rarity of a term across the entire document collection. Words that occur frequently across the collection, such as "the" or "and," will have a low IDF value, while words that are rare, such as domain-specific jargon, will have a higher IDF value.

The IDF score of a term is calculated as the logarithm of the total number of documents in the collection divided by the number of documents that contain the term. The formula for IDF is:

IDF = log(N / df)

where N is the total number of documents in the collection, and df is the number of documents that contain the term.

The IDF value is used in the TF-IDF (Term Frequency-Inverse Document Frequency) formula to calculate the importance of a term in a document. The higher the IDF score, the more important the term is in distinguishing between documents.

Text Vectorization

Text vectorization is the process of transforming text into numerical vectors that can be processed by machine learning algorithms. In natural language processing (NLP), text vectorization is a crucial step in building machine learning models that can analyze and understand human language.

There are several ways to vectorize text, but one common approach is the Bag-of-Words (BoW) model. In the BoW model, the text is first preprocessed by removing stop words and punctuation, and then the remaining words are tokenized into a list of terms. The model then creates a dictionary of all the unique terms in the corpus and assigns each term an index. Finally, each document is represented as a vector of term frequencies, where each entry in the vector corresponds to the count of the corresponding term in the document.

Another popular approach to text vectorization is the Term Frequency-Inverse Document Frequency (TF-IDF) model, which takes into account the relative frequency of a term in a document and across the entire corpus. This model assigns a weight to each term in the document, based on how frequently it occurs in the document and how rare it is in the entire corpus.

Text vectorization is an important technique in NLP because it allows machine learning models to analyze and process large volumes of textual data, which can then be used to build applications such as sentiment analysis, chatbots, and information retrieval systems.


3. Creating the Cosine Similarity Matrix
Cosine similarity

Cosine similarity is a measure of similarity between two non-zero vectors in a high-dimensional space. It is commonly used in natural language processing and information retrieval to compare the similarity of two documents or pieces of text.

To calculate the cosine similarity between two vectors, we first compute the dot product of the two vectors, which is the sum of the products of their corresponding elements. Then, we divide the dot product by the product of their magnitudes to obtain the cosine of the angle between the two vectors. The resulting value is a measure of the similarity between the two vectors, with a value of 1 indicating that the vectors are identical, and a value of 0 indicating that the vectors are completely dissimilar.

In the context of text similarity, cosine similarity is often used to compare the similarity of two documents or pieces of text that have been vectorized using techniques such as the Bag-of-Words (BoW) model or the Term Frequency-Inverse Document Frequency (TF-IDF) model. By comparing the cosine similarity of multiple documents, we can identify those that are most similar to each other and group them accordingly, which is useful for tasks such as document clustering or information retrieval.
