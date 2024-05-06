# Hindustani-Classical-Music-Recommender-System
Developed Hindustani classical music recommender defining multi-faceted similarity metrics (raga, artist, performance details, audio analysis via MFCCs/HMMs). Built dataset of 300+ recordings, 119 ragas capturing intricate attributes like sur sets, jaatis, thaats. Application provides personalized recommendations based on user preferences.

This project aims to develop a recommendation system tailored for Hindustani Classical music, taking into account the intricate nuances of this art form. The system provides personalized recommendations to students and enthusiasts based on their preferences and listening history.

## Motivation

While there are many music recommendation systems currently available, not many are fine-tuned for Hindustani Classical music. This recommender system considers the unique characteristics of this genre, such as ragas, taals, layas, and forms, to provide more relevant and accurate recommendations.

## Approach

Due to the lack of readily available data, the approach involves working with richer data sources and defining similarity metrics based on various characteristics:

1. **Raga-based Similarity**: Considering the attributes of a raga, such as sur set, jaati, thaat, vadi, samvadi, and prahar.
2. **Artist-based Similarity**: Analyzing the relationships between artists, including guru-shishya, common gurus, gharana affiliation, and connectedness.
3. **Miscellaneous Performance Details**: Factoring in the laya, taal, instruments used, and form of the composition.
4. **Audio Similarity**: Utilizing Mel Frequency Cepstral Coefficients (MFCCs) and Hidden Markov Models (HMMs) to model and compare audio features.

## Dataset

The project utilizes a combination of existing datasets and web-scraped data from various sources. The dataset includes 316 performance recordings and information about 119 ragas, capturing details like sur sets, jaatis, thaats, vadi-samvadi, and prahars. Substantial manual curation and addition of metadata were required to ensure consistency and completeness.

## Application

The developed application provides the following functionalities:

1. Initial recommendations based on user preferences for ragas and artists.
2. Refined recommendations based on user interactions and selected recordings, leveraging the defined similarity metrics.
3. Search and recommendation capabilities for specific ragas or artists.

## Challenges

Some of the challenges faced during the project include:

- Limited availability of public data in this domain, requiring extensive manual data collection and curation.
- Ensuring consistency across multiple datasets and standardizing artist and raga names.
- Computational limitations hindering certain planned operations.
- Determining the appropriate weights for each similarity factor.

## Future Improvements

Potential areas for future improvement include:

- Expanding the dataset with more performance recordings and metadata.
- Exploring advanced audio analysis techniques and deep learning models for improved audio similarity.
- Incorporating user feedback and ratings to further refine recommendations.
- Developing a user-friendly interface and enhancing the overall user experience.
