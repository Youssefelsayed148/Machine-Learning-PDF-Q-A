# Machine-Learning-PDF-Q-A
# 🤖 Machine Learning PDF Q&A Bot 

This project builds an interactive **retrieval-augmented question-answering (RAG) system** over a PDF of machine learning interview questions and answers.It uses **LangChain**, **FAISS**, and a local **Flan-T5** model for answering questions based on context extracted from the PDF.

## 🚀 Features
✅ Loads and splits a PDF of machine learning concepts into semantic chunks.  
✅ Creates a **FAISS vector store** using `sentence-transformers` embeddings for similarity search.  
✅ Retrieves the most relevant chunks for any question using semantic search.  
✅ Generates natural language answers with a local **Flan-T5 model**, without needing OpenAI or paid APIs.  
✅ Presented in a **Jupyter Notebook** with clear step-by-step cells and **screenshots of sample runs**.

---

## 🛠️ Technologies Used
- 📝 **LangChain** for building retrieval and conversational pipelines.
- 🔍 **FAISS** for high-speed vector similarity search.
- 🤗 **Hugging Face Transformers** for embeddings & text generation.
- 🧠 **Flan-T5 small** as the local language model.
- 📓 **Jupyter Notebook** for demonstration and documentation.

---


## 💡 Example Questions
| Question                          | Example Answer                                                |
|-----------------------------------|---------------------------------------------------------------|
| What is overfitting?               | Overfitting happens when a model learns noise in training data|
| Explain backpropagation.           | Backprop updates weights by computing gradients of the loss.  |
| What is a hyperparameter?          | A setting chosen before training to guide how a model learns. |

