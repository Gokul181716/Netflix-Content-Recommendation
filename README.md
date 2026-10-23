# Netflix Content Recommendation System

## Project Overview
A content-based recommendation system that suggests similar Netflix movies and TV shows using available content metadata.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity
- Matplotlib
- Google Colab

## Methodology
1. Load and explore the Netflix dataset.
2. Handle missing values.
3. Combine content metadata into feature text.
4. Convert text features into numerical vectors using TF-IDF.
5. Calculate cosine similarity between titles.
6. Recommend the five most similar titles.

## Evaluation
The system was tested using Lupin, Stranger Things, and Ganglands. It successfully generated five recommendations for each title.

Similarity scores indicate metadata similarity, not guaranteed viewer preference.

## How to Run
1. Download the repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload `Dataset.csv` when prompted.
4. Run the notebook cells in order.

## Future Improvements
- Include plot descriptions.
- Incorporate user ratings and viewing history.
- Improve recommendation diversity.
- Develop a simple web interface.