# Music Genre Classification with K-Nearest Neighbors (KNN)

This project is a school assignment focused on music genre classification using a Machine Learning approach, specifically the K-Nearest Neighbors (KNN) algorithm.

## Project Overview

The project involves:
1. **Installing Dependencies**: Installing essential libraries such as `python_speech_features` and `scipy` for feature extraction and audio processing.
2. **Importing Libraries**: Bringing in libraries like NumPy, pandas, and `scipy.io.wavfile` for numerical operations, data manipulation, and audio processing.
3. **Feature Extraction**: Using the `python_speech_features` library to extract Mel-Frequency Cepstral Coefficients (MFCC) from audio files.
4. **Defining Functions**: Implementing several functions to facilitate the KNN classification process:
    - `getNeighbors`: Calculates distances between a test instance and all training instances to find the nearest neighbors.
    - `nearestclass`: Determines the most common class among the neighbors.
    - `getAccuracy`: Computes the model's accuracy by comparing predictions to actual values.
    - `loadDataset`: Loads the dataset, splitting it into training and test sets.
    - `distance`: Calculates the distance between two instances.
5. **Main Script**: Applying the nearest class function to make predictions on the test set and evaluating the model's performance.

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebook**:
    Open the Jupyter notebook and run all cells to execute the project step-by-step.

## Files

- `music-genre-classification.ipynb`: The main notebook file containing the code for the project.
- `requirements.txt`: A file listing all the dependencies required to run the project.

## Acknowledgments

This project is part of a school assignment to demonstrate the application of machine learning techniques in audio data classification using the K-Nearest Neighbors algorithm.
