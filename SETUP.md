# Setup Guide for ChatPDF with Gemini

## Prerequisites

1. Python 3.8 or higher
2. Google Generative AI API key

## Installation

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Set up your Google Generative AI API key:
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Create a `.env` file in the project root
   - Add your API key to the `.env` file:
     ```
     GOOGLE_API_KEY=your_actual_api_key_here
     ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Open your browser and navigate to `http://localhost:8501`

## Usage

1. Upload one or more PDF files using the file uploader in the sidebar
2. Click "Process" to extract and index the PDF content
3. Ask questions about your documents in the chat interface
4. The application will use Gemini to answer your questions based on the PDF content

## Troubleshooting

- Make sure your Google API key is valid and has sufficient quota
- Ensure all dependencies are installed correctly
- Check that your PDF files are not corrupted or password-protected 