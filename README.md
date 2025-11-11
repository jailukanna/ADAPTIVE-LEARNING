# ADAPTIVE-LEARNING
MATH ADVENTURES
# Math-Adaptive-Prototype

A small adaptive math practice prototype demonstrating rule-based adaptation.

## Overview
- Three difficulty levels: Easy / Medium / Hard
- Rule-based adaptive engine that changes difficulty based on recent correctness and response time.
- Console app demo shows adaptive flow and session summary.

## Run
1. python -m venv venv
2. source venv/bin/activate
3. pip install -r requirements.txt
4. python src/main.py

## Files
- src/puzzle_generator.py : creates math problems per difficulty
- src/tracker.py : logs performance & computes rolling stats
- src/adaptive_engine.py : rule-based adaptation logic
- src/main.py : console flow demo

## Extensions
- Replace rule-based engine by training a lightweight classifier (e.g., logistic regression) that predicts the next difficulty from recent stats.
- Add a web UI (Flask/Streamlit) and persistent storage (sqlite).

