# MovieLens Recommendation System

This project implements a movie recommendation system using the MovieLens 100k dataset. 
It uses a Neural Collaborative Filtering (NCF) model built with PyTorch to predict user ratings 
and provide movie recommendations.

## Project Overview

- Loads the MovieLens 100k dataset.
- Creates a PyTorch dataset and dataloader.
- Defines a neural network model with user and item embeddings.
- Trains the model and saves the best weights.
- Provides a function to get top-N movie recommendations for any user.

## Files in this Repository

- `MMovie_YT_Recommendation_System.ipynb` : The main Jupyter notebook containing the full workflow.
- `concatnet_best_weights.pth` : Saved trained model weights for making predictions without retraining.
- `requirements.txt` : Python packages needed to run the notebook.
- `README.md` : This file.
- `ml-100k/` : The folder where the dataset should be placed (not included in the repo).

## Dataset Instructions

1. Download the MovieLens 100k dataset from: [MovieLens 100k](https://grouplens.org/datasets/movielens/100k/)
2. Extract the files into a folder named `ml-100k/` in the repository root.
3. Ensure the notebook path matches:


`data_path = 'ml-100k/'`
## How to Run

1. Clone or download this repository.

```bash
git clone https://github.com/your_username/MovieLens_Recommendation.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open `Movie_YT_Recommendation_System.ipynb` in Jupyter or Google Colab.
4. Run the notebook cells in order.
5. When prompted, enter a user ID (1-943) to get top-5 movie recommendations.
6. Type 'q' to quit the recommendation input loop.
