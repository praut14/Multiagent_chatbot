# Dr. Weather 🌦️: AI chatbot
Dr. Weather is an AI-powered meteorology assistant that uses Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to provide accurate and context-aware weather information.

Features:
Uses GPT-4.1-nano for intelligent response generation
Uses text-embedding-3-small for semantic search and retrieval
Retrieves trusted meteorology data before generating responses
Supports multiple data formats: PDF, DOCX, HTML, CSV, JSON, and TXT

Tech Stack:
Python
Streamlit
OpenAI API
ChromaDB
LangChain

Objectives: 
Provide detailed and accurate meteorological information
Reduce dependence on scattered or unreliable weather sources
Improve AI-generated responses using trusted domain-specific data
Enable efficient retrieval of weather-related insights

Data Sources:
The project uses multiple meteorology-related data formats:

File Type	  Source	             Data Type
CSV / JSON	VisualCrossing API	Historical weather data
DOCX	      Wikipedia	          Meteorology topics
HTML	      NOAA	              Weather phenomena
PDF	        Wikipedia	         Atmospheric studies
TXT	        VisualCrossing     API reference data

Key Advantages:
Accurate weather-related responses
Faster information retrieval
Domain-specific AI assistance
Reduced hallucinations using trusted sources

Challenges Faced:
Data collection from multiple sources
Managing vector store reloads
Prompt engineering for irrelevant questions
GitHub merge conflicts and API key handling
Code refactoring and integration


Future Enhancements:
Real-time weather API integration
Voice-enabled assistant
Advanced weather analytics dashboard
Multi-location forecasting support
