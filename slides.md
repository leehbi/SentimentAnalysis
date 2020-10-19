# Chester Data Insights

## Meet up usually at Cornerhouse Bar in Chester, England

## Moved online due to CV

### Welcome to join the [meet up](https://www.meetup.com/chester-data-insights/)



A friendly meet up with speakers invited to give a talk
on a wide range of Data related topics ranging from

* Open Data
* Self-service analysis,
* Business Intelligence,
* Data integration,
* AI/Data Science


People across society with an interest in data are welcome.

Very much look forward to seeing you
---

Subject : Natural Language Processing with Python

Speaker : Lee Hawthorn - recently joined Manchester University.

Goal/Reason for this meetup - demystify data analysis


Thanks to sponsors:

[Shortlist Recruiters](www.ontheshortlist.co.uk)

With a background in IT management and technical leadership, the directors of ShortList Recruitment know what good IT skills really look like

[Intilery](www.intilery.com)

Intilery is the leading real-time Customer Data and CRM platform. Receiving 100's of thousands of data points per second, transforming these into meaningful customer data. 

-------------------------

# Natural Language Processing

Natural Language Processing (NLP) is the technology used to help machines to understand and learn text and language. 

With NLP we aim to teach machines to understand what is said and written to make sense of the human language. It is used to apply algorithms to text and speech to extract 

Massive subject area - this is an introduction

# Pre-requsitives

Basic knowledge of python


# Concepts

## Syntactic Analysis

* Parsing — Involves undertaking grammatical analysis for the provided sentence.

* Lemmatisation — reduces various inflected forms of a word into a single form.  Returns the lemma for the word based on it's intended meaning.  Openly researched.  

 * Stemming — Cuts the inflected words to their root form.  Very fast but not very accurate. 

* Word segmentation — divides a large piece of continuous text into distinct units.

* Morphological segmentation — divides words into individual units.

 * Part-of-speech tagging — identify the part of speech for every word.

* Sentence breaking — Places sentence boundaries on a large piece of text

## Semantic Analysis

Semantics refers to the meaning of the sentence. A sentence that is syntactically correct does not mean lto be always semantically correct.

# Examples

| Type  | Sentence | Result
|---|---|---|
|Lower case|I Love Python|i love python
|Punctuation|Where is Guido ?|Where is Guido
|Stop words|This is an introduction to NLTK|"Introduction NTLK"
|Tokenisation|This brand is great|['This','brand','is','great']
|Stemming|I like travelling|I like travel
|Lemmatisation|This coffee filter is better than instant|This coffee filter is good than instant"



# NLTK

Natural Language Toolkit (NLTK) is an open-source package in Python which allows us to run all common NLP tasks. 

It provides easy-to-use interfaces and a suite of text processing libraries with steps involved during preprocessing i.e. classification, tokenization, stemming, tagging, parsing, and semantic reasoning.


# Use case : Sentiment Analysis

Lee wants to analyse the sentiment of his blog.

# Data pipeline steps

* Posts on leehbi.com/blog 
* Extract paragraphs
* Load to Dataframe 
* Clean Data
* Prepare Data
* Extract Sentiment
* Summarise results : Worldcloud, Averages

# Other use cases

* Creditworthiness assessment
* Neural machine translation
* Chatbots
* Sentiment analysis
* Market intelligence
* Survey Analysis
* Clinical Translation
* Customer feedback analysis

# Taking it further

* Learn about TextBlog [sentiment](https://planspace.org/20150607-textblob_sentiment/)

* Learn about [WordNet -Semantically Ordered Dictionary](https://medium.com/parrot-prediction/dive-into-wordnet-with-nltk-b313c480e788)

* Train a model on your own data for more domain specific results

