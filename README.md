# NER-Summarizer-App

a summarization app as well as a named entity checker app using streamlit,spacy,gensim,wordcloud and sumy

The basic workflow of our app includes

-Receiving Text Input From User using streamlit st.text_area() and st.text_input() functions
-Summarizing our Received Text Using Gensim,Sumy and any other packages such as NLTK or SpaCy.
-Extracting Text From a Given URL using BeautifulSoup and Urllib or Request
-Entity Recognition using Spacy
-Rendering our Extracted Named Entities using Displacy and Streamlit
