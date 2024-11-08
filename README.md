# Book Recommendation System

A robust and versatile Book Recommendation System that provides personalized book recommendations based on user preferences, ratings, location, and pricing from multiple sources (Amazon, Flipkart). This project utilizes various machine learning techniques, clustering, and data processing to deliver accurate and engaging suggestions.

---

## Features

### 1. Recommendation Models
- **Popularity-Based Filtering**: Recommends the top 50 books based on user ratings and reviews.
- **Collaborative Filtering**: Suggests books based on user interaction and similarity in preferences.
- **Price Comparison**: Compares book prices across Amazon and Flipkart to suggest the cheapest option.
- **Location-Based Recommendations**: Uses user location to cluster similar preferences and suggest books tailored to the user's region.

### 2. Data Sources
- **Books Dataset**: Contains metadata about books like titles, authors, and ISBNs.
- **Ratings Dataset**: Includes user ratings for books.
- **Users Dataset**: Contains user information, including location.
- **Amazon Dataset**: Details about books from Amazon, including prices, ratings, and reviews.
- **Flipkart Dataset**: Details about books from Flipkart, including prices, ratings, and reviews.

### 3. Key Functionalities
- Compare book prices and find cheaper options.
- Standardize book titles for consistency across datasets.
- Leverage user location for clustering and tailored recommendations.
- Interactive and visually appealing result display.

---

## Requirements

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `nltk`

Install them using:
pip install pandas numpy matplotlib seaborn scikit-learn nltk
