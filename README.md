# Presentation - Topic Modeling on the Maarten van Rossem Podcast
This repository contains a presentation regarding the analysis of the Maarten van Rossem Podcast using OpenAI's WHISPER model for transcription and Maarten Grootendorst's BERTopic package for topic modeling. The primary goal of this analysis was to gain more understanding in the use-cases, performance and aplicability of these methods in a broad context, using the podcast as a light-hearted proxy for discussing these methods.

[To check out the presentation, click here](https://avvorstenbosch.github.io/Presentation_Topic_Modeling_on_Maarten_de_Podcast/presentatie.html)
![whisper_transformer](./figures/whisper_transformer.png)

## Table of Contents
- Motivation
- Word Embeddings and Transformers
- Data Collection
- Podcast Statistics
- Topic Modeling with BERTopic
- Applications

## Motivation
The motivation for this project came from the OpenAI WHISPER model, which provides competitive performance in multi-language transcription, including Dutch. The idea was sparked of combining the power of WHISPER with one of the most listened-to podcasts in the Netherlands in order to create a thorough text-analysis of it's contents.

## Word Embeddings and Transformers
We explore the use of word embeddings and transformer models, such as BERT, to capture semantic meaning and context. We try to give an conceptual understanding of how *one-hot encodings*, *word-embeddings*, and *transformer-embeddings* are related. 

## Data Collection
We briefly explore how the data was collected using a Selenium webscraper. Transcribing using OpenAI's WHISPER model took roughly 60 hours of transcription time on a contemporary high-end consumer GPU and cost around €14 in electricity.

## Podcast Statistics
The analysis provides insights into various podcast statistics, such as episode duration, content growth, and speech tempo.

## Topic Modeling with BERTopic
BERTopic, a Python package developed by Maarten Grootendorst, was used for topic modeling in this analysis. The package is based on modular independent steps, making it easy to adapt to ones own likings and capabilities.

The analysis provides a 2D and 3D visualization of the topics and a hierarchy of topics. It also shows how actualities can be tracked over time.

# Applications
We briefly explore applications for of these methods, such as:

- Using WHISPER as a tool for local transcription of interviews or meetings, reducing the need for either costly internal manual transcription or costly external transcription services.
- Employing BERTopic to analyze and visualize various internal text sources, like internal documents, news reports, or annual reports.


# Author
- Alex van Vorstenbosch
--------------------------------
For more in-depth explanations and visualizations, view the presentation slides in this repository. I you want to read the full blogpost, please visit the project page at [avvorstenbosch.github.io/Maarten_De_Podcast_Analysis](avvorstenbosch.github.io/Maarten_De_Podcast_Analysis).