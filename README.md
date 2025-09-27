# Movie Recommendation System

A content-based movie recommendation system built with Python and Streamlit.

## Features
- Recommends similar movies based on content features
- Interactive web interface using Streamlit
- Uses cosine similarity for recommendations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Movie-Recommendation.git
cd Movie-Recommendation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```bash
streamlit run app.py
```

2. Open your browser and go to `http://localhost:8501`
3. Select a movie from the dropdown and click "Recommend"

## Files Description
- `app.py` - Main Streamlit application
- `model.ipynb` - Jupyter notebook for model training and data preprocessing
- `movies_dict.pkl` - Processed movie data
- `similarity.pkl` - Precomputed similarity matrix
- `data/` - Contains raw CSV data files

## Dataset
The project uses the TMDB 5000 Movie Dataset containing movie metadata and credits.