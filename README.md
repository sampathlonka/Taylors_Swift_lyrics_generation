# Taylors_Swift_lyrics_generation

# Lyrics Generation for Taylor Swift Lyrics Dataset

This project focuses on generating lyrics using various approaches and models applied to Taylor Swift's Lyrics dataset. The project includes basic data analysis, sentiment analysis, lyrics generation using LSTM, GPT2, and image generation for album covers based on the lyrics available in a given album.

## Table of Contents
- [Taylors\_Swift\_lyrics\_generation](#taylors_swift_lyrics_generation)
- [Lyrics Generation for Taylor Swift Lyrics Dataset](#lyrics-generation-for-taylor-swift-lyrics-dataset)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Dataset](#dataset)
  - [Methods and Models](#methods-and-models)
  - [Results](#results)
  - [Conclusion](#conclusion)
  - [Future Work](#future-work)
  - [References](#references)

## Introduction

In this project, we explore Taylor Swift's Lyrics dataset to gain insights into her music and generate new lyrics based on the existing data. The project utilizes various natural language processing and deep learning techniques to analyze the dataset, generate lyrics using LSTM and GPT2 models, and create album covers based on the lyrics using T5 and Diffusion models.

## Dataset

The dataset used in this project consists of Taylor Swift's lyrics, which can be obtained from [https://www.kaggle.com/datasets/ishikajohari/taylor-swift-all-lyrics-30-albums]. It contains a collection of songs, lyrics, album information, and other relevant attributes.

## Methods and Models

1. Basic Data Analysis: This step involves exploratory data analysis to understand the structure and characteristics of the dataset. It includes quantitative analysis, visualizations, and data preprocessing techniques.

2. Sentiment Analysis: Sentiment analysis is performed on the lyrics to determine the emotional tone of each song using `nltk` library. This helps in understanding the overall sentiment conveyed through the lyrics. For more details, visit the [page](https://github.com/sampathlonka/Taylors_Swift_lyrics_generation/blob/main/Taylor%20Swift%20Lyrics%20%20Data%20Analysis.ipynb).

3. Lyrics Generation with LSTM: Long Short-Term Memory (LSTM) models are trained on the lyrics dataset to generate new lyrics. The LSTM models learn the patterns and structures present in the lyrics and generate coherent and contextually relevant lyrics. You can find the details [here](https://github.com/sampathlonka/Taylors_Swift_lyrics_generation/blob/main/Lyrics_Generation_with_LSTM.ipynb)

4. Lyrics Generation with GPT2: GPT2, a powerful language model, is fine-tuned on the lyrics dataset to generate high-quality and creative lyrics. The GPT2 model leverages its contextual understanding of language to generate lyrics that mimic Taylor Swift's style. The code will be updated soon.

5. Image Generation for Album Covers: To complement the generated lyrics, this project also includes image generation for album covers. The lyrics from a specific album are used as input to a diffusion model to create visually appealing album covers that reflect the lyrical themes and emotions. You find the code [here](https://github.com/sampathlonka/Taylors_Swift_lyrics_generation/blob/main/Album_Cover_Generator.ipynb)


## Results

The project yields the following results:

- Insights into Taylor Swift's lyrics through basic data analysis.
- Sentiment analysis results to understand the emotional tone of the songs.
- LSTM-generated lyrics that mimic Taylor Swift's style and themes.
- GPT2-generated lyrics with improved creativity and contextuality.
- Album cover images based on the lyrical themes and emotions.

## Conclusion

In conclusion, this project provides a comprehensive approach to lyrics generation for Taylor Swift's Lyrics dataset. It explores various techniques, including basic data analysis, sentiment analysis, LSTM-based lyrics generation, GPT2-based lyrics generation, and album cover image generation. The project demonstrates the power of natural language processing and deep learning in generating creative and contextually relevant lyrics.

## Future Work

Possible areas for future work on this project include:

- Fine-tuning the existing models for better performance and lyric generation.
- Incorporating other advanced deep learning models for lyrics generation.
- Implementing user interactions to customize the generated lyrics.
- Expanding the dataset to include more songs and albums from Taylor Swift or other artists.
- Integrating the lyrics generation models into a user-friendly application or website.

## References

[will be updated soon]

