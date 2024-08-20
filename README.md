

# StereotypeAnalysis

## Overview
The primary goal of this project is to analyze and quantify gender-based stereotypes by studying the roles assigned to male and female characters. The project aims to develop a machine learning solution to identify and mitigate these stereotypes in Bollywood movies.

## Dataset
The dataset used for this project includes:

- **Movie Scripts:** Textual data representing the narrative and dialogues of the movies.
- **Movie Trailers:** Visual and audio data used for promoting the movies.
- **Wikipedia Data:** Structured and unstructured data from Wikipedia pages about the movies.
- **Movie Posters:** Visual data in the form of images, used for marketing the movies.

## Methodology

### 1. Face Detection and Gender Detection
To analyze the gender distribution and representation in movie posters:

- **Face Detection:** Used the MTCNN (Multi-task Cascaded Convolutional Networks) algorithm to detect faces in movie posters.
- **Gender Detection:** Applied the VGG16 model, pre-trained on the ImageNet dataset, for gender classification of detected face. Apply a gender detection model (such as VGG16) to classify the detected faces as male or female.
- **Bounding Box Size Calculation:** Calculate the area of each bounding box (width × height).
- **Aggregate Bounding Box Sizes:** Sum the bounding box areas for male and female faces separately.Compare the total areas to determine gender dominance.The code for this part of the analysis is available in the repository.

### 2 Sentiment analysis (yerawise)
The code is designed to analyze the sentiment of adverbs used in descriptions of females over the years, as recorded in a CSV file.
- **Sentiment Analysis:** It calculates how positive, neutral, or negative these descriptions are for each year.
- **Visualization:** The results are visualized using a line plot to show trends in sentiment over time.
This analysis can help you understand how the portrayal of female-related adjectives and adverbs has evolved over the years, and whether there's been a shift towards more positive, negative, or neutral descriptions.


### 3 female-male centrality calculation (moviewise)
The task involved analyzing gender dominance in movies based on centrality metrics provided in two CSV files: male_centrality.csv and female_centrality.csv. Each file contains data on the centrality of male and female characters across various movies, including Total Centrality and Average Centrality values.
The task provided a systematic approach to identifying gender dominance in movies based on the centrality of male and female characters. The analysis revealed which movies had more central or influential male characters versus female characters, based on the aggregated centrality scores. The results can be used to further explore gender representation in films and understand potential biases in character roles.

#### Code for all above analysis is provied in same jupyter notebook
#### No training and testing done (as dataset is not lablled)


