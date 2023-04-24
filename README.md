# Movie-Recommendation-System

The mission
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
You are part of the data team for the Internet Movie Database (IMDB). Your task is to create a recommendation tool for movies and TV shows that an user can interact with.

The tool will take as input the user's favorite movies and shows and recommend new ones in a user friendly manner. You are allowed to use additional resources and incorporate other features that are interesting for users.

The goal is to have a working minimum viable product (MVP) by the end of the project. Each member (or team) in the group should submit a project outline of their MVP on by end of Day 1 to the coach for review and feedback.


Steps:
1. Data Preprocessing
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. EDA(Exploratory Data Analysis)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
EDA stands for Exploratory Data Analysis, which is an approach to analyzing and summarizing a dataset in order to gain insights and identify patterns and relationships between variables.

3. Creating the TF-IDF Matrix
-------------------------------------------------------------------------------------------------------------------------------------------------------------
TF

TF stands for Term Frequency and it measures the frequency of a term (i.e., a word or a phrase) in a document. The term frequency of a term t in a document d is calculated as the number of times t appears in d, divided by the total number of terms in d. This calculation normalizes the term frequency by the document length to avoid bias towards longer documents.

TF is commonly used in natural language processing and information retrieval to represent the importance of a term within a document. It can be used in combination with IDF (Inverse Document Frequency) to calculate the TF-IDF score, which provides a measure of the importance of a term across a collection of documents.

IDF

IDF stands for Inverse Document Frequency and it is used to determine how important a word is in a document collection. IDF measures the rarity of a term across the entire document collection. Words that occur frequently across the collection, such as "the" or "and," will have a low IDF value, while words that are rare, such as domain-specific jargon, will have a higher IDF value.

The IDF score of a term is calculated as the logarithm of the total number of documents in the collection divided by the number of documents that contain the term. The formula for IDF is:

IDF = log(N / df)

4. Dashboard
-----------------------------------------------------------------------------------------------------------------------------------------------
Dashboard
![Dashboard](https://github.com/sainisheetal/Movie-Recommendation-System/blob/main/PowerBi/Movie%20Recomendation%20Dashboard.png)
I have used Powerbi desktop to build this dashboard. This dashboard shows details related to movies. It also shows in which country the movie shooting happen. It shows which movies have what popularity, vote and rating count.

Limitations
---------------------------------------------------------------------------------------------------------------------------------------
I am using the free version which has some less functionality. If we work on paid version we will be able to publish our reports and dashboards.

@Sheetal Saini
