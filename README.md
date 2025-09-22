# Personal Agentic AI Chatbot

A production-ready GenAI application built with modern AI technologies, featuring intelligent agents with search capabilities and a clean web interface.

## 🚀 Overview

This project implements a sophisticated AI chatbot using agentic AI patterns with LangGraph ReAct agents, providing users with intelligent conversational experiences backed by multiple LLM providers and search functionality.

## 🛠️ Tech Stack

- **AI Framework**: LangGraph ReAct Agents
- **Backend**: FastAPI with Pydantic for schema validation
- **Frontend**: Streamlit for interactive UI
- **LLM Providers**: 
  - Groq
  - OpenAI
  - Meta Llama
  - Mistral
- **Tools & Utilities**: Langchain for tool integration
- **Server**: Uvicorn for hosting
- **Language**: Python
- **IDE**: VS Code

## 📋 Features

- 🤖 Agentic AI with ReAct (Reasoning and Acting) patterns
- 🔍 Integrated search tool functionality via Tavily
- 🌐 RESTful API with FastAPI
- 💻 Interactive web interface with Streamlit
- 🔧 Multiple LLM provider support
- 📝 Schema validation with Pydantic
- 📚 Comprehensive Swagger UI documentation
- 🎛️ Configurable model providers and system prompts

## 🏗️ Project Structure

The project is organized into three main phases:

### Phase 1: AI Agent Creation
- API key setup for Groq and Tavily
- LLM and tools configuration
- AI agent implementation with search capabilities

### Phase 2: Backend Development
- Pydantic model setup for schema validation
- AI agent integration with frontend requests
- FastAPI application with Swagger UI documentation

### Phase 3: Frontend Implementation
- Streamlit UI with configurable options:
  - Model provider selection
  - Model selection
  - System prompt customization
  - Query input interface
- Backend integration via API endpoints

## 🚦 Getting Started

### Prerequisites

- Python 3.8+
- API keys for:
  - Groq
  - Tavily (for search functionality)
  - OpenAI (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd personal-agentic-ai-chatbot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   ```bash
   # Create a .env file with your API keys
   GROQ_API_KEY=your_groq_api_key
   TAVILY_API_KEY=your_tavily_api_key
   OPENAI_API_KEY=your_openai_api_key  # Optional
   ```

### Running the Application

1. **Start the FastAPI backend**
   ```bash
   uvicorn main:app --reload
   ```

2. **Launch the Streamlit frontend** (in a new terminal)
   ```bash
   streamlit run app.py
   ```

3. **Access the application**
   - Frontend: `http://localhost:8501`
   - Backend API docs: `http://localhost:8000/docs`

## 📖 Usage

1. **Configure your chatbot**:
   - Select your preferred model provider (Groq, OpenAI, etc.)
   - Choose the specific model (Llama, Mistral, etc.)
   - Customize the system prompt for desired behavior

2. **Interact with the AI**:
   - Enter your queries in the chat interface
   - The AI agent will use search tools when needed
   - Receive intelligent responses with reasoning capabilities

3. **API Integration**:
   - Use the FastAPI endpoints for programmatic access
   - Explore the Swagger UI at `/docs` for detailed API documentation

## 🔧 Configuration

The application supports various configuration options:

- **Model Providers**: Switch between Groq, OpenAI, and other providers
- **Models**: Support for Meta Llama, Mistral, and other models
- **System Prompts**: Customize the AI's behavior and personality
- **Search Integration**: Configurable search tool functionality

##  API Documentation

Once the FastAPI backend is running, comprehensive API documentation is available at:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## Acknowledgments

- LangGraph for the agentic AI framework
- FastAPI for the robust backend framework
- Streamlit for the intuitive frontend interface
- Groq, OpenAI, Meta, and Mistral for LLM capabilities
