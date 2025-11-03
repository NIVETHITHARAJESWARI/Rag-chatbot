# RAG Chatbot Project

This project contains chatbots that can answer questions based on your documents using Retrieval Augmented Generation (RAG).

## Files

- `basic_chatbot.py` - Simple chatbot that works with text files only
- `main_chatbot.py` - Universal chatbot that supports multiple file formats (PDF, DOCX, Excel, etc.)
- `requirements.txt` - Required Python packages
- `notes/` - Directory where you should place your documents

## Setup

1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Add your documents to the `notes/` folder

3. Run the chatbot:

**Terminal version:**
```bash
cd chatbot_project
python main_chatbot.py
```

**Web UI version (with file upload):**
```bash
cd chatbot_project
python -m streamlit run web_ui.py
```

## Supported File Types

- Text files (.txt, .md)
- PDF files (.pdf)
- Word documents (.docx)
- Excel files (.xlsx, .xls)

## Usage

**Terminal version:**
1. Run `python main_chatbot.py`
2. Ask questions about documents in the `notes/` folder
3. Type 'quit' to exit

**Web UI version:**
1. Run `python -m streamlit run web_ui.py`
2. Upload files using the sidebar
3. Ask questions in the chat interface
4. No API key needed (pre-configured)