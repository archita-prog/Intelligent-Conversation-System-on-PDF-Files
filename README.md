An NLP-powered application that:
Extracts key sections from PDFs using tokenization and keyword matching.
Chats with documents via a Streamlit UI powered by Google’s Generative AI.

Key Features
PDF Text Extraction: Uses PyPDF2 to parse documents.

Semantic Search: Embeds text with FAISS/Vector Store for efficient retrieval.
Conversational AI: Generates human-like responses using LangChain + Google Generative AI.
Interactive UI: Streamlit-based interface for seamless user interaction.

Technical Approach
1. NLP Document Processing
Tokenization & Text Classification: Splits PDFs into meaningful chunks.
Keyword Matching: Identifies key sections (e.g., "Abstract," "Methodology").
Vector Embeddings: Uses FAISS for similarity search over extracted text.

2. Generative AI Chat
LangChain Pipeline: Connects document retrieval to generative AI.
Google Gemini/PaLM: Generates context-aware responses from PDF content.

