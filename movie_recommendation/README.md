# Top 30 Movies Recommendation System

This project implements a **Movie Recommendation System** using a dataset of movies. The system processes various movie features like genre, language, popularity, votes, and crew to generate a list of top 30 recommended movies.

## Dataset

The dataset used is fetched from a public URL and contains the following features:
- **Movie Genre**
- **Movie Language**
- **Movie Popularity**
- **Movie Votes**
- **Movie Crew**

## Requirements

- **Python 3.x**
- Libraries:
  - `pandas`
  - `numpy`

## Usage

 **Loading the Dataset**:
   The notebook loads the dataset directly from the following URL:
   ```python
   df = pd.read_csv('https://raw.githubusercontent.com/YBI-Foundation/Dataset/main/Movies%20Recommendation.csv')

