# 🏥 AI-Powered Medical Chatbot  

An AI-based **context-aware medical assistant** that provides reliable responses to health-related queries using a medical knowledge base. Built with LangChain, Gemini API (`Gemini-flash-1.5`), HuggingFace Embeddings and Pinecone.  

⚠️ **Disclaimer:** This chatbot is for educational and informational purposes only. It is **not a substitute for professional medical advice**.  

---

## 🚀 Features  
- **Medical Knowledge Base** – Uses *The Gale Encyclopedia of Medicine (Second Edition)* as the reference.  
- **Context-Aware Responses** – Answers are grounded in the provided knowledge base.  
- **Vector Search with Pinecone** – Retrieves the most relevant chunks for accurate answers.
- **Conversational Memory** – ConversationBufferMemory from LangChain to retain chat context for more coherent multi-turn conversations. 
- **Flask Web Interface** – Custom backend with HTML/CSS frontend for a user-friendly web app.  


---

## 🛠️ Tech Stack  
- **Language Models**: ChatGoogleGenerativeAI to interact with Gemini gemini-flash-1.5.
- **Embeddings**: sentence-transformers (HuggingFace)  
- **Vector Store**: Pinecone 
- **Framework**: LangChain  
- **Frontend / Deployment**: Flask backend with custom HTML/CSS frontend   

---

## 📂 Project Structure  
```
ChatBot/
│
├── data/                     # PDF knowledge base
│   └── The_GALE_ENCYCLOPEDIA_of_MEDICINE_SECOND.pdf
│
├── research/                 # Research materials or notes
│   └── trials.ipynb
│
├── src/                      # Source code
│   
│   ├── helper.py
│   └── prompt.py
│
├── static/                   # Static assets (CSS, JS, images)
│   └── style.css
│
├── templates/                # HTML templates
│   └── chat.html
│
├── app.py                    # Flask backend (main chatbot)
├── requirements.txt          # Python dependencies
├── setup.py
├── store_index.py
├── .gitignore                # Git ignore file
└── README.md                 # Project documentation


```
---

## ⚡ Quickstart  

1. Clone this repository  
2. Create a virtual environment
3. Install Dependencies
4. Set Up Environment Variables
5. Run the Flask App
      
   
---

## 📬 Contact

If you have any questions, feel free to connect with me:

@ LinkedIn : [Meet Korat](https://www.linkedin.com/in/meet-korat-4353a7284/)

@ Github : [Meet Korat](https://github.com/meetkorat05)  
