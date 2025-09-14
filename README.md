# HR Policy Assistant Chatbot  

An interactive **HR Policy Assistant Chatbot** built as part of an MBA project on *GenAI & Business Applications*.  
The chatbot allows employees to ask HR policy–related questions and get instant, contextual answers backed by the official HR policy handbook.  

---

## 🔹 Demo  
👉 [Try the Streamlit App](https://hr-policy-chatbot-porject-6ywceuokb5mvtyumztbryf.streamlit.app/)  

---

## 🔹 Features  
- 📄 Upload and process HR policy PDFs.  
- 💬 Interactive Q&A with contextual, policy-grounded answers.  
- ✅ Feedback logging (Yes/No) on responses.  
- 📝 Employee suggestions for missing or unclear policies.  
- ⚡ Lightweight, budget-friendly implementation (Groq API + FAISS + Streamlit).  

---

## 🔹 Tech Stack  
- **Frontend:** Streamlit  
- **Document Handling:** pypdf  
- **Embeddings & Retrieval:** sentence-transformers, FAISS  
- **LLM Integration:** Groq API (LLaMA 3.1)  
- **Feedback Logging:** pandas (CSV storage)  

---

## 🔹 System Workflow  
1. **Upload HR policy PDF**  
2. **Extract & chunk text** from the document  
3. **Convert chunks into embeddings** and store in FAISS  
4. **Employee query → relevant policy retrieval → enriched prompt**  
5. **Groq API (LLaMA-3.1)** generates contextual response  
6. **Streamlit displays** the answer, collects feedback & suggestions  

---
