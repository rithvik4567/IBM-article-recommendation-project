# IBM Recommendation System Project

## Project Overview
This project focuses on building a recommendation system using real data from the IBM Watson Studio platform. The goal is to recommend articles to users based on their interactions with the platform. The project explores multiple recommendation techniques, including rank-based recommendations, user-user collaborative filtering, content-based recommendations, and matrix factorization.

## Repository Files

Here is a list of all the files in this repository along with their descriptions:

- **starter/**
  - `Recommendations_with_IBM.ipynb`: The main Jupyter notebook containing the implementation of the recommendation system.
  - `project_tests.py`: A Python script containing automated tests to verify the correctness of the implemented functions.
  - `top_5.p`, `top_10.p`, `top_20.p`: Pickle files for testing purposes.
  - `data/user-item-interactions.csv`: The dataset used for building the recommendation system, containing user-article interactions.

### Dependencies
Ensure you have the following dependencies installed:
- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn

## Project Structure
The project is divided into the following sections:

1. **Exploratory Data Analysis**:
   - Analyze the dataset to understand user-article interactions.
   - Handle missing values and visualize interaction distributions.

2. **Rank-Based Recommendations**:
   - Recommend articles based on their popularity.
   - Suitable for new users with no interaction history.

3. **User-User Collaborative Filtering**:
   - Recommend articles based on the preferences of similar users.
   - Uses cosine similarity to find similar users.

4. **Content-Based Recommendations**:
   - Recommend articles similar to a given article based on their titles.
   - Uses TF-IDF vectorization and K-means clustering.

5. **Matrix Factorization**:
   - Use Singular Value Decomposition (SVD) to find latent features in the user-item matrix.
   - Recommend articles based on these latent features.

## Testing

### Automated Tests
The project includes automated tests to verify the correctness of implemented functions. These tests are located in the `project_tests.py` file.

### Running Tests
To run the tests, execute the following command:
```bash
python starter/project_tests.py
```

## Deliverables
- Implemented recommendation functions for each technique.
- Visualizations and insights from exploratory data analysis.
- A detailed notebook documenting the implementation and results.


## License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.
