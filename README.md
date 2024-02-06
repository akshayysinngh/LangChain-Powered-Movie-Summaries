# LangChain-Powered-Movie-Summaries

## Overview
This project is focused on leveraging Large Language Models (LLMs) to automatically generate summaries of movie scripts. The goal is to provide concise, informative summaries that capture the essence of a movie's plot, themes, and character arcs using advanced natural language processing techniques.

## Features

**Script Scraping**: Automated scraping of movie scripts from the IMSDB (Internet Movie Script Database) using BeautifulSoup to fetch script of a movie.

**Prompt Engineering**: Careful design of prompts to get the most coherent and relevant summaries from the LLM, along with most important keywords from the data.

**MapReduce for Data Processing**: Implementation of the MapReduce programming model to efficiently process large datasets of movie scripts, enabling scalable analysis.

**Visualization**: Use of WordCloud to visualize the most frequent words in the generated summaries, providing a quick and intuitive understanding of key themes.

<img width="1224" alt="wordcloud" src="https://github.com/akshayysinngh/LangChain-Powered-Movie-Summaries/assets/91548001/5e954ff7-fcf5-4e9b-98d8-43d8648ed079">

**Evaluation Metrics** : Utilization of ROUGE scores (ROUGE-1, ROUGE-2, ROUGE-L) to quantitatively assess the quality of generated summaries against reference summaries, focusing on unigram and bigram overlap as well as sentence structure.
<img width="1224" alt="evaluation" src="https://github.com/akshayysinngh/LangChain-Powered-Movie-Summaries/assets/91548001/81e09249-6d60-4c36-b31b-d6bf59a7a1e2">


