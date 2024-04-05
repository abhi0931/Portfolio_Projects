
# Analysis of Top 10000 Songs on Spotify (1960-Now)

## Overview
This project delves into the 'Top 10000 Songs on Spotify from 1960 to 2023', providing a comprehensive analysis of musical trends, popularity, and evolution over time. Through data cleaning, exploratory data analysis (EDA), and machine learning, insights into the temporal evolution of music listening on Spotify — including analysis of tracks, albums, artists, labels, and genres — are unveiled. Predictive modeling of song popularity and a recommendation system based on musical features are also covered.

## Visualisations

For an interactive exploration of the project's findings, visit the Tableau Public dashboard at the following link:
[Interactive Music Analysis on Tableau Public](https://public.tableau.com/views/MusicAnalysis_17077501449520/DBTracksD?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

This dashboard complements the analysis, offering a dynamic way to engage with the data.


## Installation
To get started, clone this repository to your local machine. Ensure you have Anaconda installed, then import the musicanalysis environment from the provided environment.yml file by running:
conda env create -f environment.yml

Activate the musicanalysis environment:
conda activate musicanalysis

Note: This project utilizes a custom-built function, describex(), housed within a custom module for enhanced data description. The function and its module are not provided in this repository to maintain the focus on the notebook's methodology and findings. Descriptions of its functionality and intended output are included within the notebook.

## Usage
This project is presented through a Jupyter Lab notebook, offering a narrative journey through the data analysis process. To explore the project:
1. Activate the musicanalysis environment: `conda activate musicanalysis`
2. Start Jupyter Lab: `jupyter lab`
3. Navigate to and open the project notebook.

## Project Structure
- `README.md` - Project overview and setup instructions.
- `environment.yml` - Conda environment file.
- `Music Analysis (Top 10000 Songs on Spotify 1960-Now).ipynb` - Jupyter Lab notebook containing the project's analysis.

## Analysis Overview
The project's analysis section is meticulously structured to cover various aspects of the musical landscape on Spotify:
- Temporal Evolution of Music (1960-Now): Tracks analysis over time, popular tracks and artists, and album and label trends.
- Genre Analysis: Including broad categorization of genres into 4 major categories (Hip-Hop, Pop, Rock, and Others), popularity, and evolution.
- Miscellaneous Analysis: Like popularity over years, musical feature evolution, and distribution of explicit content.
- Machine Learning: Implementation of Random Forest and Gradient Boosting Regressor models for song popularity prediction and development of a recommendation system based on song features.

## Dataset Reference
This project utilizes the 'Top 10000 Spotify Songs from 1960 to Now' dataset, contributed by JOAKIM ARVIDSSON. The dataset can be accessed at Kaggle at this link: [https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now/data](https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now/data)

## Acknowledgements
I would like to extend my gratitude to the numerous YouTube creators who have shared their knowledge on data science and data analysis, which has been instrumental in my learning journey:
- Stefanovic -- [https://www.youtube.com/@Stefanovic92](https://www.youtube.com/@Stefanovic92)
- Luke Barousse -- [https://www.youtube.com/@LukeBarousse](https://www.youtube.com/@LukeBarousse)
- Alex The Analyst -- [https://www.youtube.com/@AlexTheAnalyst](https://www.youtube.com/@AlexTheAnalyst)
- Learn with Lukas -- [https://www.youtube.com/@learnwithlukas](https://www.youtube.com/@learnwithlukas)
- Chandoo -- [https://www.youtube.com/@chandoo_](https://www.youtube.com/@chandoo_)
- codebasics -- [https://www.youtube.com/@codebasics](https://www.youtube.com/@codebasics)

A special thanks to ChatGPT for its invaluable assistance throughout the development of this project.

## Contributing
Feedback and contributions to this project are welcome.

## License
This project is open-source and available under the MIT License. The use of the dataset is subject to the terms provided by its respective owner or contributor.
