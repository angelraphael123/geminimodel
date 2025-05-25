# Q&A Chatbot with Gemini LLM

This project demonstrates a Q&A chatbot application built using the Gemini Language Model from Google Generative AI. It also supports generating insights from uploaded images using the `gemini-pro-vision` model.

## Features

- Text-based Q&A functionality using the Gemini Pro language model.
- Image understanding and analysis using the Gemini Pro Vision model.
- Integrated chat history to track user queries and bot responses.
- Intuitive web interface built with Streamlit.
- Secure configuration of API keys using environment variables.

---

## Requirements

To run this project, ensure you have the following:

1. **Python**: Version 3.8 or above.
2. **Libraries**: 
    - `streamlit`
    - `google-generativeai`
    - `python-dotenv`
    - `Pillow`
3. **Google Generative AI API Key**: Obtainable from [Google Cloud Console](https://console.cloud.google.com/).

---

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/qna-gemini-chatbot.git
    cd qna-gemini-chatbot
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory with the following content:

    ```env
    GOOGLE_API_KEY="AIzaSyBL-SZv8JdegrabyK-yCcMdwJLMIZVHRV4"
    ```

---

## Usage

1. Start the application:

    ```bash
    streamlit run app.py
    ```

2. Open the app in your web browser at `http://localhost:8501`.

3. Use the text input to ask questions or upload an image for analysis.

4. View the chatbot's responses and interaction history on the interface.

---

## File Structure

