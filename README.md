# NamedEntityRecognitionCoNLL-2003

## Introduction
In this project, we selected an appropriate model to recognise the type of entity each word represents in a sentence. 

## Background
The CoNLL-2003 dataset contains tokens that are labelled with one of the 9 NER tags. 

e.g.
[ "Itamar", "Rabinovich", ",", "who", "as", "Israel", "'s", "ambassador", "to", "Washington", "conducted", "unfruitful", "negotiations", "with", "Syria", ",", "told", "Israel", "Radio", "it", "looked", "like", "Damascus", "wanted", "to", "talk", "rather", "than", "fight", "." ]	
[ 3, 4, 0, 0, 0, 5, 0, 0, 0, 5, 0, 0, 0, 0, 5, 0, 0, 1, 6, 0, 0, 0, 5, 0, 0, 0, 0, 0, 0, 0 ]

Using a Bi-directional LSTM, an F1 score of about 0.87 was achieved when tagging the test data with IOB/BIO tagging.

Refer to the report for more information.
