## Overview
This repository hosts a book recommendation system implemented using Python. The system utilizes user ratings data to recommend books based on user similarities. The recommendation is based on collaborative filtering technique, leveraging user-item interactions from the dataset.

## Dataset
The dataset named book2.csv includes the following columns:
- User.ID: Unique identifier for each user who has rated books.
- Book.Title: Title of the book that has been rated.
- Book.Rating: The rating given to the book by a user on a scale of 1-10.
The dataset encompasses over 10,000 ratings provided by 2,182 unique users across 9,659 unique books.

## Libraries Used
- Pandas: For efficient data manipulation and analysis.
- NumPy: For numerical operations on arrays.
- Scikit-learn: For accessing the pairwise distances function, which is crucial for calculating similarities between users.
- SciPy: Provides functionality to calculate cosine similarity and other distance metrics.
