# anime-recommendation-system
# Anime Recommender System using Feature Extraction and Cosine Similarity

## Introduction

This Python project is an Anime Recommender System that uses feature extraction and cosine similarity to recommend anime based on user-selected anime. The dataset contains various columns such as genre, theme, synopsis, demographic, and more for each anime. The recommendation system utilizes the TfidfVectorizer to convert textual data into numerical representations and then calculates the cosine similarity between anime to find the most similar ones.

## Requirements

To run the project, you need the following:

- Python (version 3.8 or above)
- pandas
- scikit-learn

## Installation

To install the required dependencies, you can use pip. Open a terminal or command prompt and run:

```
pip install pandas scikit-learn
```

## Dataset

The dataset used in this project contains information about various anime and their attributes, such as genre, theme, synopsis, demographic, etc. Make sure to download the dataset and save it as `anime_dataset.csv` in the project directory.

## Usage

1. Clone the repository or download the project files to your local machine.

2. Ensure you have the required dependencies installed (see Requirements).

3. Place the `mal_anime.csv` file in the project directory.

4. Open the `Anime recommendation system.ipynb` file, which contains the main code for the recommendation system.

5. Modify the `anime_name` variable in the code to set the anime selected by the user.

6. Run the `Anime recommendation system.ipynb` file using Python.

7. The program will display a list of recommended anime based on the similarity between the user-selected anime and other anime in the dataset.

## Feature Extraction

In this project, the TfidfVectorizer is used for feature extraction. TfidfVectorizer converts the textual data (synopsis, genre, theme, etc.) into numerical representations (vectors) based on the term frequency-inverse document frequency (TF-IDF) measure. This allows us to represent anime using numerical features for further similarity calculations.

## Cosine Similarity

The cosine similarity metric is utilized to measure the similarity between two anime. Cosine similarity calculates the cosine of the angle between two vectors and provides a value between -1 and 1. A value of 1 indicates that the two anime are identical, while a value of -1 indicates they are dissimilar. The recommendation system uses the cosine similarity to find the most similar anime to the user-selected anime.

## Output

The output of the program will be a list of recommended anime titles along with their similarity scores to the user-selected anime. The anime with higher similarity scores are more closely related to the user-selected anime and are recommended accordingly.

## Example

Below is an example of how the recommendation system works:

```
anime_name = "One Piece"

Recommended Anime:
1. One Piece
2 . One Piece: Episode of East Blue - Luffy to 4-nin no Nakama no Daibouken
3 . One Piece Movie 14: Stampede
4 . One Piece Film: Z
5 . One Piece: Romance Dawn Story
6 . One Piece Film: Strong World Episode 0
7 . One Piece Film: Strong World
8 . One Piece: Oounabara ni Hirake! Dekkai Dekkai Chichi no Yume!
9 . Kaizoku Ouji
10 . One Piece 3D2Y: Ace no shi wo Koete! Luffy Nakama Tono Chikai
11 . Mashou no Nie 3
12 . Gintama Movie 2: Kanketsu-hen - Yorozuya yo Eien Nare
13 . Shironeko Project: Zero Chronicle
14 . One Piece Film: Red
15 . One Piece Movie 08: Episode of Alabasta - Sabaku no Oujo to Kaizoku-tachi
```

In this example, the user selected "One Piece," and the system recommends anime that are similar to "One Piece" based on their synopsis, genre, theme, and other attributes.

## Conclusion

This Anime Recommender System leverages feature extraction and cosine similarity to provide personalized anime recommendations based on user-selected anime. It enables anime enthusiasts to discover new anime that align with their preferences, making their anime-watching experience more enjoyable.

Happy anime watching! 📺✨
