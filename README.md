# Movie Plot Analysis with Clustering and Similarity Measurement

## Overview

This project involves the analysis of movie plots using natural language processing (NLP) techniques. The goal is to quantify the similarity between movies based on their plot summaries obtained from IMDb and Wikipedia, and then cluster them into groups based on these similarities. This allows for the exploration of relationships between movies and the identification of similar movies within the dataset.

## Contents

- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this project contains information about 100 movies, including their titles, genres, and plot summaries from both IMDb and Wikipedia.

## Technologies Used

- Python
- NumPy
- Pandas
- NLTK (Natural Language Toolkit)
- SciKit-Learn
- Matplotlib

## Setup

To run this project locally, follow these steps:

1. Clone the repository:


## Usage

The main components of the project include:

1. **Data Import and Observation**: Importing the dataset and observing the movie data.
2. **Combining Plot Summaries**: Combining plot summaries from IMDb and Wikipedia into a single column for analysis.
3. **Tokenization**: Tokenizing sentences and words from the plot summaries.
4. **Stemming**: Reducing words to their root form using stemming techniques.
5. **TF-IDF Vectorization**: Converting the textual plot summaries into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
6. **Clustering**: Using K-means clustering to group movies based on their plot similarities.
7. **Similarity Distance Calculation**: Calculating the similarity distance between movie plots.
8. **Dendrogram Visualization**: Visualizing the hierarchical clustering of movie plots using dendrograms.

## Results

The project provides insights into the relationships between movies based on their plot summaries. Clustering and similarity measurements allow for the identification of similar movies and the exploration of thematic connections within the dataset.

