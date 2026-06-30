# Final Project — NLP Emotion Detection

## Description

A Flask web application that analyzes text input and detects emotions using the IBM Watson NLP Emotion Predict API. Given a piece of text, the app identifies the intensity of emotions (anger, disgust, fear, joy, sadness) and returns the dominant emotion.

## Setup & Installation

**Prerequisites:** Python 3.8+

1. Clone the repository and navigate to the project folder:
   ```bash
   cd final_project
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install flask requests
   ```

4. Run the Flask server:
   ```bash
   flask --app server run
   ```

5. Open your browser at `http://127.0.0.1:5000`
