# Nutrition Vision App — Multimodal Food Analysis with Gemini

Upload a photo of your food and get an itemized calorie and nutrition breakdown, powered by Google's Gemini vision model.

**Live demo:** https://nutrition-gemini.streamlit.app/

## How it works

1. A Streamlit front end accepts a food image
2. The image plus a structured nutritionist prompt are sent to Gemini's vision API
3. The model identifies the food items and returns itemized calorie and nutrition insights

## Stack

Gemini (vision) · Streamlit · Python · PIL
