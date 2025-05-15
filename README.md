# 📄 PDF Chat Bot with RAG 🤖

A Streamlit application that enables users to chat with their PDF documents using Retrieval-Augmented Generation (RAG) technology powered by OpenAI.

![GitHub contributors](https://img.shields.io/github/contributors/yourusername/pdf-chat-bot)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/pdf-chat-bot)
![GitHub issues](https://img.shields.io/github/issues/yourusername/pdf-chat-bot)
![GitHub stars](https://img.shields.io/github/stars/yourusername/pdf-chat-bot)

## ✨ Features

- 📤 Upload PDF documents
- 🔍 Extract and process text content
- 🧠 Create vector embeddings with OpenAI
- 💬 Ask questions about your document content
- 🔄 View conversation history in the UI

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API Key

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/pdf-chat-bot.git
cd pdf-chat-bot
```

2. Create a virtual environment

```bash
python -m venv streamlitvenv
```

3. Activate the virtual environment

```bash
# On Windows
streamlitvenv\Scripts\activate

# On macOS/Linux
source streamlitvenv/bin/activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Create a `.env` file in the root directory and add your OpenAI API key

```
OPENAI_API_KEY=your_openai_api_key_here
```

### Running the Application

```bash
streamlit run app.py
```

The application will be available at http://localhost:8501

## 📋 Usage

1. Upload a PDF document using the file uploader
2. Wait for the application to process and index your document
3. Type questions about the content in the text input
4. View the AI's responses based on the content of your document

## 🛠️ Technology Stack

- [Streamlit](https://streamlit.io/): Web application framework
- [LangChain](https://python.langchain.com/): Framework for LLM applications
- [OpenAI](https://openai.com/): Provides embeddings and LLM capabilities
- [FAISS](https://github.com/facebookresearch/faiss): Vector store for efficient similarity search
- [PyPDF2](https://pypi.org/project/PyPDF2/): PDF processing library

## 📊 Project Status

[![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-green)](https://img.shields.io/badge/Project%20Status-Active-green)
[![Development Status](https://img.shields.io/badge/Development%20Status-Beta-yellow)](https://img.shields.io/badge/Development%20Status-Beta-yellow)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [OpenAI](https://openai.com/) for providing the AI models
- [Streamlit](https://streamlit.io/) for the amazing web app framework
- All contributors who help improve this project
