# Gemini LLM Q\&A Demo

A sleek Streamlit app that connects to Google's Gemini 2.0 Flash language model, enabling interactive Q\&A with real-time streaming responses.

---

## Features

* Real-time streaming answers from Gemini LLM
* Persistent chat history during your session
* Simple, clean Streamlit UI

---

## Setup

1. Install dependencies:

```bash
pip install streamlit python-dotenv google-generativeai
```

2. Create a `.env` file and add your Google API key:

```
Google_Api_Key=your_google_api_key_here
```

3. Run the app:

```bash
streamlit run app.py
```

---

## Usage

* Enter your question in the input box
* Click **Ask the question**
* Watch the Gemini model respond live
* Scroll to view full chat history

---

## Notes

* Requires a valid Google API key with access to Gemini
* Response streams in chunks for faster interaction

---

Made with 💡 + 🚀 by leveraging Streamlit and Google Generative AI


