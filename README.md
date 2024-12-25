# TikTok Data Analysis & Machine Learning Model

This repository contains a machine learning project aimed at analyzing TikTok data and applying machine learning models to make predictions based on the dataset.

The script and models are built using Python, including popular libraries such as `pandas`, `numpy`, `scikit-learn`, `tensorflow` The code includes preprocessing, feature engineering, and training machine learning models for specific tasks with TikTok-related data.

Model implementation: Choosing the best performance model between random forest and XGboost, and adjust its hyperparameters. Then perform a rigorous test-validation process

## Project Overview

This project utilizes **TikTok data** to apply machine learning models, and ultimately use the model to make predictions of claimed or opinion videos. That helps to reduce a significant amount of work of controlling claimed videos.

The model gives an accurate prediction of nearly 100%.

## Dataset

The dataset used for this analysis includes various TikTok-related data such as:

- Video IDs
- Views
- Comments
- Shares
- Likes
- User data (user profiles, engagement metrics)
- Hashtags and captions

### Data Structure Example

The dataset should have columns like:

- `video_id`: ID for the TikTok video.
- `likes`: Total likes on the video.
- `shares`: Number of times the video was shared.
- `comments`: Number of comments.
- `hashtags`: List of hashtags in the video.
- `engagement`: Engagement score.

## Requirements

To run the project, you will need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt
