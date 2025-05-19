# Indian Constitution RAG Bot 🤖

A Retrieval-Augmented Generation (RAG) chatbot that provides accurate answers about the Indian Constitution using Streamlit and OpenAI.

## Features ✨

- 🤖 Interactive chat interface
- 📚 Accurate answers based on the Indian Constitution
- 🔍 Context-aware responses using RAG
- 💡 Sample questions provided
- 🎨 Clean and modern UI

## Tech Stack 🛠

- **Frontend**: Streamlit
- **Backend**: Python
- **Vector Database**: Pinecone
- **LLM**: OpenAI GPT-3.5-turbo
- **Embeddings**: OpenAI text-embedding-ada-002

## Prerequisites 📋

- Python 3.12
- OpenAI API key
- Pinecone API key
- Pinecone environment (us-east-1-aws)

## Installation 🚀

1. Clone the repository:
```bash
git clone https://github.com/yourusername/indian-constitution-rag.git
cd indian-constitution-rag
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your environment variables in `.streamlit/secrets.toml`:
```toml
OPENAI_API_KEY = "your-openai-key"
PINECONE_API_KEY = "your-pinecone-key"
PINECONE_ENVIRONMENT = "us-east-1-aws"
```

## Usage 💻

1. Run the Streamlit app:
```bash
streamlit run src/app_streamlit.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Start asking questions about the Indian Constitution!

## Sample Questions 📝

- Who was the President of the Constituent Assembly?
- What are the three lists in the Seventh Schedule?
- How many languages are officially recognized in India?
- What is the Panchayati Raj system?
- What are Fundamental Duties?

## Project Structure 📁
