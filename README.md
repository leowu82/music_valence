# Data Analysis Project

## Objective
- Analyze how each dimensions of a piece of music (key, mode, dancability, acousticness, etc.) influences the valencity (perceived emotional positivity) of the music
- Build a model to predict valence
- Determine which audio dimensions most strongly influence valence

## Dataset
- Dataset obtained from kaggle： https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre
- Cleaned and preprocessed the raw/dirty dataset for effective analysis

## Methods
– Applied K‑means clustering (using an elbow curve to select k) to uncover natural groupings
– Visualized feature relationships with matplotlib charts and heatmaps
– Trained a Random Forest classifier to predict valence from audio features
– Extracted and ranked feature importances to pinpoint key drivers

## Results
– Developed a model achieving 89.5% accuracy in valence prediction
– Identified danceability, energy, and acousticness as the top three contributors to emotional positivity
