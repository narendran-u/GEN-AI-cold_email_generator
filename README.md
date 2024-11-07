

---

# Cold Email Generator 📧🤖

## Overview
This project is a **Cold Email Generator** designed to create personalized, impactful emails for outreach campaigns using **Generative AI**. The model leverages **LangChain** for language processing and **Groq** for accelerated performance, enabling users to quickly generate email drafts based on input parameters such as target audience, purpose, and tone. 

## Features
- Generates cold emails with personalized tone and structure
- User-friendly interface built with **Streamlit**
- Utilizes **LangChain** and **Groq** for robust language processing and quick inference
- Enables customization by adjusting inputs like target industry, objective, and formal or casual tone

## Technologies Used
- **LangChain** (`langchain`, `langchain-community`, `langchain-groq`)
- **Unstructured**: For text parsing and preprocessing
- **Selenium**: Automates browser tasks for email testing
- **ChromaDB**: Handles embeddings and similarity matching
- **Streamlit**: Builds a user interface for smooth interactions
- **Pandas**: Manages data input and output
- **Python-dotenv**: Manages environment variables securely

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cold-email-generator.git
   ```
2. Install dependencies:
   ```bash
   pip install langchain==0.2.14 langchain-community==0.2.12 langchain-groq==0.1.9 unstructured==0.14.6 selenium==4.21.0 chromadb==0.5.0 streamlit==1.35.0 pandas==2.0.2 python-dotenv==1.0.0
   ```

3. Set up environment variables by creating a `.env` file and adding any necessary API keys or credentials.

## Usage
1. Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Enter relevant parameters such as audience type, desired tone, and purpose.
3. Generate a custom cold email, then preview and refine as needed.

## Future Enhancements
- Incorporating additional language models for multilingual email generation
- Expanding customization options for niche industry targeting
- Enhancing UI/UX for streamlined email export options

---
