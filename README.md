# EDA-NLP-on-UrduSpeechDataset

Performed Exploratory Data Analysis and Natural Language Processing (NLP) downstream tasks on a Urdu Speech Dataset available at: https://github.com/siddiquelatif/URDU-Dataset/tree/master

## Data PreProcessing:
1. Merged the speeches of the same speaker into one file.
2. Converted the merged audio files into text using OpenAI Whisper API.

## Exploratory Data Analysis:
1. Identifyied the top 10 most frequent words in the transcribed text for each emotion and plot them in a bar graph.
2. Calculated the average length of the transcribed text for each emotion and plotted them in a bar graph.
3. Analyzed the sentiment polarity of the transcribed text for each emotion using Vader Sentiment Analysis and plotted the results.

## Natural Language Processing (NLP) Downstream Tasks:
Performed Sentiment Analysis on the generated transcription using TextBlob library
