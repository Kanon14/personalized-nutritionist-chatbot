# personalized-nutritionist-chatbot

## Overview
This application is a web-based tool developed with Streamlit, designed to estimate the calory content of 
food items from uploaded images. It leverages Google's Gemini API for generating content based on textual and visual input. This application aims to assist nutritionists and individuals in tracking calory intake effortlessly.

## Features
1. `Text Input for Custom Prompts`: Users can enter specific prompts to guide the AI in identifying and analyzing food items in the uploaded images.
2. `Image Upload`: Supports uploading food images in JPEG or PNG formats.
3. `Calories Calculation`: After analyzing the uploaded image along with the prompt, the application displays a detailed list of food items and their respective calory counts.

## Project Setup
### Prerequisites
- Python 3.9+
- Anaconda or Miniconda installed on your machine.
- Google Gemini API key

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Kanon14/personalized-nutritionist-chatbot.git
cd personalized-nutritionist-chatbot
```

2. Create and activate a Conda environment:
```bash
conda create -n nutrientenv python=3.10 -y
conda activate nutrientenv
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
### Training and Image Detection:
1. Execute the project:
```bash
streamlit run app.py
```

2. Then, access the application via your web browser:
```bash
open http://localhost:<port>
```

3. Upload the food images and input prompt in text area (optional), click the button for response. 