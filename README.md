# AI-Powered Search Assistant 🔍

A powerful web application that combines AI-driven search capabilities with intelligent content summarization. The system searches the web for relevant information, processes the content, and generates comprehensive, well-structured answers to user queries using the Mixtral-8x7b model through Groq.

## 🌟 Features

- **Smart Web Search**: Utilizes Google Search API through Serper for accurate and relevant results
- **Content Processing**: Extracts and processes content from multiple web sources
- **AI-Powered Summarization**: Generates concise, relevant answers using the Mixtral-8x7b model
- **User-Friendly Interface**: Clean, responsive Streamlit frontend with modern design
- **Robust Backend**: Flask-based API with error handling and logging
- **Source Attribution**: Provides links to original sources for transparency

## 🛠️ Technology Stack

- **Backend**:
  - Flask (Python web framework)
  - LangChain + Groq (AI/LLM integration)
  - BeautifulSoup4 (Web scraping)
  - Requests (HTTP client)
  
- **Frontend**:
  - Streamlit
  - Custom CSS
  - Modern UI components

- **APIs**:
  - Serper (Google Search API)
  - Groq (LLM API)

## 📋 Prerequisites

- Python 3.8+
- pip (Python package manager)
- API keys:
  - SERPER_API_KEY (for Google Search)
  - GROQ_API_KEY (for LLM access)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Arjun9271/AI_Powered_Search_Assistant.git
cd ai-search-assistant
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file in the project root with:
```env
SERPER_API_KEY=your_serper_api_key
GROQ_API_KEY=your_groq_api_key
```

## 🏃‍♂️ Running the Application

1. Start the Flask backend:
```bash
cd flask_app_folder
python app.py
```
The backend will start on `http://localhost:5001`

2. In a new terminal, start the Streamlit frontend:
```bash
cd streamlit_app
streamlit run app.py
```
The frontend will be available at `http://localhost:8501`

## 📁 Project Structure

```
.
├── flask_app_folder/
│   ├── app.py          # Flask backend application
│   └── utils.py        # Utility functions for content processing
├── streamlit_app/
│   └── app.py          # Streamlit frontend application
├── requirements.txt    # Project dependencies
├── .env               # Environment variables
└── README.md          # Project documentation
```

## 🔧 Configuration

The application can be configured through the following environment variables:
- `SERPER_API_KEY`: Your Google Search API key from Serper
- `GROQ_API_KEY`: Your API key for accessing Groq's LLM services





## 🔍 Usage Example

1. Access the web interface at `http://localhost:8501`
2. Enter your question in the search box
3. Click the "Search" button
4. Wait for the AI to process your query
5. Review the generated answer and provided sources





## 🤝 Acknowledgments

- Groq for providing the LLM API
- Serper for Google Search API access
- Streamlit for the frontend framework
- Flask for the backend framework


