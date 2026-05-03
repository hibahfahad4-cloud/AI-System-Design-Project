# AI-System-Design-Project
NutriFit AI is a machine learning-based system designed to recommend meals for athletes based on their macronutrient goals. The system uses a clustering approach (K-Means) to group recipes according to nutritional similarity, then suggests the most relevant meals based on user input such as calories, protein, carbohydrates, and fat.

The project includes data preprocessing, feature engineering (e.g., protein-to-calorie and fat-to-carbohydrate ratios), and a recommendation engine that retrieves the closest matches using similarity measures. To ensure reliability, a rule-based fallback model is implemented when no exact matches are found.

The system is deployed as an interactive web application using Streamlit, providing fast and real-time recommendations with high accuracy and low latency. The main goal is to help athletes optimize their nutrition, improve performance, and reduce reliance on complex or privacy-sensitive data.
