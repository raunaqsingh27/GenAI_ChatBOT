# Lumos-Generative-AI-PDF-Chatbot
----------------------------
Lumos Chatbot is a Streamlit-based application that allows users to chat with a conversational AI model trained on PDF documents. The chatbot extracts information from uploaded PDF files and answers user questions based on the provided context.

https://lumos-chatbot.streamlit.app/

## Features
----------------------------
- PDF Upload: Users can upload multiple PDF files.
- Text Extraction: Extracts text from uploaded PDF files.
- Conversational AI: Uses the Gemini conversational AI model to answer user questions.
- Chat Interface: Provides a chat interface to interact with the chatbot.

## Getting Started
----------------------------
Follow these instructions to set up and run this project on your local machine.

   **Note:** This project requires Python 3.10 or higher.

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/Lumos-Generative-AI-PDF-Chatbot.git
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Google API Key:**
   - Obtain a Google API key and set it in the `.env` file.

   ```bash
   GOOGLE_API_KEY=your_api_key_here
   ```

4. **Run the Application:**

   ```bash
   streamlit run main.py
   ```

5. **Upload PDFs:**
   - Use the sidebar to upload PDF files.
   - Click on "Submit & Process" to extract text and generate embeddings.

6. **Chat Interface:**
   - Chat with the AI in the main interface.

## Project Structure
----------------------------
- `app.py`: Main application script.
- `.env`: file which will contain your environment variable.
- `requirements.txt`: Python packages required for working of the app.
- `README.md`: Project documentation.

## Dependencies
----------------------------
- PyPDF2
- langchain
- Streamlit
- google.generativeai
- dotenv

## Acknowledgments
----------------------------
- [Google Gemini](https://ai.google.com/): For providing the underlying language model.
- [Streamlit](https://streamlit.io/): For the user interface framework.
