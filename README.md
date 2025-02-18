# Multi-PDF ChatBot (LangChain - Google Gemini)

## Acknowledgement
I would like to extend my sincere thanks to  [Krish Naik](https://github.com/krishnaik06)  for his invaluable content and guidance, which helped me build this project. This project wouldn't have been possible without his educational resources.

 <br>

## About the Project
The ***Multi-PDF ChatBot*** is an AI-powered application that allows users to upload multiple PDF files and ask questions based on their content. It leverages **[Google Gemini AI](https://deepmind.google/technologies/gemini/)** for intelligent question-answering and utilizes **[FAISS (Facebook AI Similarity Search)](https://ai.meta.com/tools/faiss/)** for efficient text retrieval and similarity search. The chatbot extracts and processes text from PDFs, converts it into vector embeddings, and provides detailed answers using an advanced conversational AI model.

This project supports multiple PDFs, enabling users to upload and query their content seamlessly. It utilizes **Google Gemini AI** to generate smart, context-aware responses while employing **FAISS** to store and retrieve text efficiently. By implementing **[LangChain](https://www.langchain.com/)**, the chatbot processes large documents by splitting them into smaller, more manageable chunks, improving AI understanding. The interface is built with **[Streamlit](https://streamlit.io/)**, ensuring an interactive and user-friendly experience.

Technologically, the project integrates **PyPDF2** for text extraction, **LangChain** for AI-driven text processing, **FAISS** for vector-based similarity search, and **Google Gemini AI** for embeddings and conversational responses. Additionally, **dotenv** is used for secure API key management. This AI-driven chatbot is ideal for applications in research, legal analysis, business intelligence, and education, enabling users to interact with documents more effectively and extract relevant information with ease.

<br>

## How to Run the Project ?
### **1. Clone the Repository**
Clone the repository to your local machine :
```bash
 git clone https://github.com/SoubhikSinha/Multi-PDF-ChatBot.git
```

<br>

### **2. Create a Virtual Environment**
Navigate to the repository's root directory and create a Conda virtual environment :
```bash
conda create --prefix ./venv python=3.11 -y
```
  
<br>

### **3. Activate the Conda Environment**
Activate the newly created environment :
```bash
conda activate venv/
```

<br>  

### **4. Install Required Libraries**
Install all the necessary dependencies :
```bash
pip install -r requirements.txt
```

<br>  

### **5. Set Up Google API Key**
Create and paste your Google API key inside  `.env`  file. Get your API key from  [Google AI Studio](https://aistudio.google.com/app/apikey).

Example  `.env`  file content :
```bash
GOOGLE_API_KEY="your_api_key_here"
```
  
<br>

### **6. Run the Application**
Start the Streamlit application by running :
```bash
streamlit run app.py
```
  
 <br>

### **7. Play Around !**
Explore the features of the **Multi-PDF ChatBot** and experience seamless interaction with your documents. Upload multiple PDFs, ask questions, and get AI-powered responses instantly.
