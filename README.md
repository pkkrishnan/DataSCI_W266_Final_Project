# DataSCI_W266_Final_Project
NLP Final Project

## Introduction
This repository contains the datasets, model codes and final report for the DataSci W266 Final NLP Project.

## Dataset
MediaSum data set on Hugging Face is used for model evaluation. This large-scale media interview dataset contains 463.6K transcripts with abstractive summaries, collected from interview transcripts and overview/topic descriptions from NPR and CNN. For our study, we restricted the dataset size to 1,000 examples for extractive summarization and 100 for abstractive summarization due to computational limitations. CNN / Daily Mail dataset was also used for comparative purposes given its narrative non-conversational structured nature.

MediaSum Link: https://huggingface.co/datasets/ccdv/mediasum
CNN Dailymail Link: https://huggingface.co/datasets/ccdv/cnn_dailymail

## Model Code
The model code folder contains model codes for the following extractive models.
- TFIDF	            
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 
- Sentence level built from scratch using the original Bert Model 
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 

The model code folder contains model codes for the following abstractive models.       
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 
- Sentence level built from scratch using the original Bert Model 
- Pre-trained sentence transformer (‘all-MiniLM-L6-v2’) with sentence-level embeddings 

## Final Report and Slide Deck
The final report and slide deck are contained in this folder

