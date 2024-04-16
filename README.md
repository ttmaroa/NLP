# NLP AND CLEANING TEXT

## Introduction
In this section, we get to se the basic concepts in Natural Language Processing and in particular, common techniques for handling, processing and preparing unstructured text data for use with machine learning models.

NLTK - Natural Language Toolkit - is a widely used library for building Python programs to work with human language data. It provides interfaces to numerous corpora and lexical resources, such as WordNet, along with a suite of text-processing libraries for classification, tokenisation, stemming, tagging, parsing, and semantic reasoning. Additionally, NLTK offers wrappers for various NLP libraries and features an active discussion forum.

Thanks to a hands-on guide introducing programming fundamentals alongside topics in computational linguistics, plus comprehensive API documentation, NLTK is suitable for linguists, engineers, students, educators, researchers, and industry users alike. NLTK is available for Windows, Mac OS X, and Linux. Best of all, NLTK is a free, open-source, community-driven project.

We shall be using The Myers Briggs Type Indicator (or MBTI for short) which is a personality type system that divides people into one of 16 distinct personality types across 4 axes:

  -Introversion (I) – Extroversion (E)
  
  -Intuition (N) – Sensing (S)
  
  -Thinking (T) – Feeling (F)
  
  -Judging (J) – Perceiving (P)

So for example, someone who prefers introversion, intuition, thinking and perceiving would be labelled an INTP in the MBTI system, and there are lots of personality-based components that would model or describe this person’s preferences or behaviour based on their label.

We'll be looking at data containing over 6000 rows of data, where in each row is a person's:
  - MBTI type (4 letter MBTI code)
  - A section of each of the last 50 things they have posted online (Each entry separated by "|||" (3 pipe characters))

With that said, lets get the data and clean it up.
