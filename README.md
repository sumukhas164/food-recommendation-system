# food-recommendation-system
Overview
The Food Recommendation System is a web-based application that suggests recipes based on user preferences. Built with Python, Flask, and scikit-learn, it leverages machine learning and natural language processing to match user input with recipes from a real-world dataset.

🔍 How It Works
The app uses the RAW_recipes.csv dataset, which includes thousands of recipes from Food.com with ingredients, tags, and cooking time.

Text features are created by combining the recipe name, ingredients, and tags.

These features are vectorized using TF-IDF (Term Frequency-Inverse Document Frequency).

When a user types preferences like "spicy chicken garlic", the system:

Converts input into a TF-IDF vector.

Compares it with all recipes using cosine similarity.

Returns the top 5 most similar recipes.

💻 Features
🧠 Text-based recipe recommendations

🥘 Real recipe data with name, ingredients, tags, and cooking time

🌐 Simple Flask web app

🎨 Modern UI using the Poppins font

📊 Scikit-learn for TF-IDF and similarity calculations

🛠️ Tech Stack
Python

Flask

Pandas

scikit-learn

HTML/CSS (with Google Fonts)

📦 Dataset
RAW_recipes.csv (from Food.com)
