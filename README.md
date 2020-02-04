# nlp_masterthesis

Assessing study selection using NLP techniques: 

Stage 1: 
**Data Extraction**
Specific portions(Introduction, Methods, Conclusion) of the data are extracted and is extracted to xslx .

Stage 2:
**Study Selection**
The extracted data is then pre-processed using NLTK  
The processed data is then sent to a clustering algorithms(**K-means**). Similar set of documents is clustered here. The top terms of each cluster is then considered to select the relevant research/data for further assessment.   
Another such method which is considered to select the most relevant research is LDA. LDA helps in discovering abstract "topics" that occur in the collection of documents  
Finally, we club both the methods **LDA + K Means** and select method which yields the best posible research for the defined research topic. 
The topics are then studied and the documents which are most relevant to topic of interest is then selected for further assessment.

Stage 3:
**Quality Assessment**
The selected study is then assessed semi-automatically with the help of a sentence scoring algorithm **BM25**.
The assessment is done based on the defined quality criteria questions.


### Install

This project files requires **Python 3** and **jupyter**
