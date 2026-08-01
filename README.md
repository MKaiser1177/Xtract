# Multi-Language Invoice Extractor

This project is a Streamlit web app that lets you upload an invoice image and ask questions about it in natural language. It uses Google Gemini to analyze the invoice content and generate responses based on the uploaded document.

## Features

- Upload invoice images in JPG, JPEG, or PNG format
- Ask questions about the invoice such as vendor name, total amount, invoice number, due date, and more
- Supports multi-language invoice analysis

## Requirements

- Python 3.9 or later
- pip

## Installation

1. Open the project folder.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Set your Google API key as an environment variable:

   PowerShell:
   ```powershell
   $env:GOOGLE_API_KEY="your_google_api_key"
   ```

   Bash:
   ```bash
   export GOOGLE_API_KEY="your_google_api_key"
   ```

## Run the App

Start the Streamlit app with:

```bash
streamlit run app.py
```

Then open the local URL shown in the terminal in your browser.

## Usage

1. Enter a question in the input box.
2. Upload an invoice image.
3. Click the "Tell me about the invoice" button.
4. Review the generated response.

## Notes

- The app uses the Google Generative AI SDK and Gemini model integration.
- Make sure your Google API key is valid and has access to the required services.
