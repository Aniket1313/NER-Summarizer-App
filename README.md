# NER-Summarizer-App

a summarization app as well as a named entity checker app using streamlit,spacy,gensim,wordcloud and sumy

The basic workflow of our app includes

1. Receiving Text Input From User using streamlit st.text_area() and st.text_input() functions
2. Summarizing our Received Text Using Gensim,Sumy and any other packages such as NLTK or SpaCy.
3. Extracting Text From a Given URL using BeautifulSoup and Urllib or Request
4. Entity Recognition using Spacy
5. Rendering our Extracted Named Entities using Displacy and Streamlit
