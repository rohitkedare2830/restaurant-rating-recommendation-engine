
# Restaurant Recommendation System

## Cognifyz – Where Data Meets Intelligence

## Abstract
This project builds a content-based restaurant recommendation system that suggests restaurants
based on cuisine type, price range, and aggregate ratings using cosine similarity.

## Objectives
- Build a restaurant recommendation system
- Recommend restaurants based on user preferences
- Preprocess and encode restaurant data
- Apply content-based filtering

## Dataset Description
The dataset includes:
- Restaurant Name
- Cuisines
- Price Range
- Aggregate Rating

## Data Preprocessing
- Missing cuisines replaced with 'Unknown'
- Missing price ranges filled with most frequent value
- Missing ratings filled with mean value
- Categorical features encoded using Label Encoding

## Methodology
- Feature vectors created for restaurants
- Cosine similarity applied
- Restaurants with highest similarity scores recommended

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn

## Results
The system successfully recommends relevant restaurants matching user preferences.

## Future Scope
- Add collaborative filtering
- Include restaurant location
- Apply NLP on reviews
- Deploy as a web application

## Author
Rohit Narayan Kedare
