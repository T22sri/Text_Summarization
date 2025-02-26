# Generating short summaries of text from headlines

## Overview

This project focuses on applying deep learning in Natural Language Processing (NLP), particularly on an NLP use case: generation of text summaries in the form of short news headlines. The task is to generate a coherent set of new headlines (or summaries) from many of the original headlines for each article provided. The goal is to cover the concept of Sequence-to-Sequence as model, which uses an encoder decoder framework and successfully generates logical headlines for many of the articles provided. 

## Project Background

While the concept of summarization started in the 1950’s, the field is still evolving to give the best and most efficient summaries. There are two approaches to text summarization. 

1. Extractive summarization – which is a more basic solution that extracts the most important words or sentences without ‘writing’ any new content on its own 
2. Abstractive summarization – which is a more sophisticated and promising model that learns to understand language in its syntax and context and generate summary using ‘its own words’. 

The above two types focus on how the key information found in the input text is reconstructed in the generated summary in their own ways. Both of these methods have their own unique challenges that pop up when looking at using longer text. 

This project will provide an overview of summarization techniques in the context of abstractive summarization. Deep learning encoder-decoder (sequence-to-sequence) model is used to construct the text summary, where an encoder accepts the actual text and summary, trains the model to create an encoded representation, and sends it to a decoder which decodes the encoded representation into a reliable summary. As the training progresses, the trained model can be used to perform inference on new texts, generating reliable summaries from them.


