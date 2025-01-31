# Personalized-Student-Recommendations

NEET Testline - Personalized Student Recommendations
Project Overview
This project develops an AI-driven recommendation system for NEET (National Eligibility cum Entrance Test) preparation, focusing on personalized insights and improvement strategies based on quiz performance analysis.
Key Features

Performance analysis across topics and difficulty levels
Personalized improvement recommendations
Student persona generation
Predictive rank estimation

Setup Instructions

Clone the repository
Install dependencies: pip install -r requirements.txt
Configure API endpoints in config.py
Run main script: python neet_analyzer.py

Project Structure

data_processor.py: Data loading and preprocessing
performance_analyzer.py: Performance analysis and insights
recommendation_engine.py: Personalized recommendation generation
rank_predictor.py: NEET rank probability estimation
student_persona.py: Student persona generation

Requirements

Python 3.8+
pandas
numpy
scikit-learn
matplotlib

Approach

Data Aggregation: Collect quiz submission and historical performance data
Performance Analysis: Identify strengths, weaknesses, and learning patterns
Recommendation Generation: Create targeted improvement strategies
Persona Mapping: Define learning archetypes
Predictive Modeling: Estimate potential NEET rank

