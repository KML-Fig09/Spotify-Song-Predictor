# Song Popularity Prediction

### This project aims to predict the popularity of songs using machine learning techniques. The notebook included in this repository is designed to be run in Google Colaboratory (Colab), which provides a convenient and accessible environment for machine learning experiments. 

This was my first ever attempt at training a ML model for predictive data analysis. I have learned and grown a lot since this, and I am working on a little rewrite to clean the code up a bit. However, I wanted to include this on my github to show how far I've come in the 6 months since I made this, when I eventually upload my final MSc project, along with a rewrite of this. ###

## Project Overview

- **Objective:** Predict the popularity of a song based on various features.
- **Dataset:** The dataset used for this project includes various attributes related to songs, such as tempo, loudness, key, etc.
- **Modeling Techniques:** Multiple machine learning models are explored and evaluated to determine the best performance.
- **Evaluation Metrics:** Models are assessed using metrics like accuracy, precision, recall, and F1 score.

## Contents

- `First_ML_Model_Song_Popularity_Prediction.ipynb`: The Jupyter notebook containing the entire workflow of the project, including data preprocessing, model training, and evaluation.
- `requirements.txt/`: Text file with library requirements.
- `README.txt/`: This file.
- `spotify30ksongs.csv/`: Raw dataset file.

## Getting Started

### Running the Notebook in Google Colab

1. **Open the Notebook in Colab:**
   - You can open the notebook directly in Google Colab by clicking the following link: [Open in Colab](https://colab.research.google.com/github/KML-Fig09/song-popularity-prediction/blob/main/First_ML_Model_Song_Popularity_Prediction.ipynb)

2. **Install Required Libraries:**
   - Colab provides many pre-installed libraries. However, if your notebook requires additional libraries, they can be installed by running the following command in a cell:
   ```python
   !pip install -r requirements.txt
   ```

3. **Upload or Access Data:**
   - If your dataset is not hosted online, you can upload it directly into Colab's environment using:
   ```python
   from google.colab import files
   uploaded = files.upload()
   ```
   - Alternatively, if your data is stored on Google Drive, you can mount your Drive to Colab:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

4. **Run the Cells:**
   - Execute the cells sequentially to carry out the data processing, model training, and evaluation steps.

### Running the Notebook Locally

If you prefer to run the notebook on your local machine:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/song-popularity-prediction.git
   cd song-popularity-prediction
   ```

2. **Set Up a Virtual Environment:**
   It’s recommended to use a virtual environment to manage dependencies:
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the Required Libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook First_ML_Model_Song_Popularity_Prediction.ipynb
   ```
   - Follow the same steps for data loading and running cells as mentioned above.

### Running the Notebook in Other Environments

If you're running the notebook in an environment other than Colab or your local machine, such as on a cloud-based Jupyter server or in a Docker container:

1. **Ensure Environment Compatibility:**
   - Make sure that all required libraries listed in `requirements.txt` are installed.
   - If using a Docker container, include a `Dockerfile` in your repository to simplify setup.

2. **Modify Data Access Paths as Necessary:**
   - Depending on where your data is stored, you might need to modify paths within the notebook.

3. **Run the Notebook:**
   - Launch the Jupyter server and access the notebook as usual.

## Project Structure

- **Data Loading and Exploration:** Initial exploration of the dataset to understand its structure and characteristics.
- **Feature Engineering:** Steps taken to preprocess the data and engineer features that are fed into the machine learning models.
- **Model Training:** Training various models to predict song popularity.
- **Model Evaluation:** Evaluation of the models using appropriate metrics to choose the best-performing model.
- **Conclusion:** Final remarks on model performance and potential areas for improvement.

## Results

- A brief summary of the model performance and key findings.
- Include any visualizations or metrics that highlight the success of your model.

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Acknowledgments

Kaggle. 2024. “30000 Spotify Songs.” Accessed Jan 15. https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs?resource=download.

Leshem, Ido. 2022. “Mini ML Project – Predicting Song Popularity.” Medium. Aug 19. https://blog.devgenius.io/mini-ml-project-predicting-spotify-songs-popularity-part-1-ec1c906b8ff8. Accessed Feb 22nd, 2024.

---
