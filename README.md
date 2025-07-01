## 🏏 Smart Cricket Predictor Dashboard

**Smart Cricket Predictor** is an interactive web application built using **Gradio**, **TensorFlow**, and **machine learning models** to analyze and forecast cricket player performance based on uploaded CSV stats. Whether you're a cricket analyst, coach, or just a fan, this dashboard provides deep insights into players' roles, predicted metrics, and comparisons.

### 🔍 Features

* **Upload Player Dataset** – Easily upload your CSV file containing player stats.
* **Role Prediction** – Automatically classify players as Batsman, Bowler, or All-Rounder using a deep learning model.
* **Performance Forecasting** – Predict key performance metrics:

  * Runs
  * Batting Average
  * Bowling Average
  * Economy Rate
* **Simulated Time-Series** – Visualize how a player might perform across the next 10 matches.
* **Smart XI Selector** – Automatically selects the best possible team of 11 players based on predicted performance.
* **Player Comparison** – Compare two players side-by-side using a visual and data-driven approach.

### 🧠 Tech Stack

* **Frontend**: Gradio (for interactive UI)
* **Backend**: Python
* **ML Models**: TensorFlow (Role Prediction) and Scikit-learn-based regression models
* **Visualization**: Matplotlib, Seaborn
* **Deployment Ready**: Hugging Face Spaces or Colab-compatible

### 📁 Input CSV Format

The uploaded file should contain the following columns:

* `player_name`
* `runs`
* `balls_faced`
* `batting_avg`
* `strike_rate`
* `balls_bowled`
* `economy`
* `bowling_avg`
* `wickets`

### 📌 Note

This project uses a deep learning model for role prediction, so running it on CPU might be slower. For better performance, a GPU environment is recommended.
