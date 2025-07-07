# Machine-Learning-PDF-Q-A
# 🤖 Machine Learning PDF Q&A Bot 

This project builds an interactive **retrieval-augmented question-answering (RAG) system** over a PDF of machine learning interview questions and answers.It uses **LangChain**, **FAISS**, and a local **Flan-T5** model for answering questions based on context extracted from the PDF.

## 🚀 Features
- ✅ Ingests and splits a PDF into semantic chunks.
- ✅ Creates a **FAISS vector store** with sentence-transformer embeddings for efficient similarity search.
- ✅ Uses **LangChain** to retrieve relevant chunks based on a user question.
- ✅ Generates answers using a **local Hugging Face Flan-T5 model**, without OpenAI APIs.
- ✅ Interactive **Gradio web app** to input questions and receive direct answers.

## 🛠️ Technologies Used
- 📝 **LangChain** for building the retrieval chain.
- 🔍 **FAISS** for similarity search.
- 🤗 **Hugging Face Transformers** for embeddings and generation.
- 🧠 **Flan-T5 small** as the local language model.
- 🎨 **Gradio** for the user interface.

## 🚀 How to Run
1. Install dependencies:
    ```bash
    pip install langchain faiss-cpu sentence-transformers transformers torch gradio
    ```
2. Make sure your PDF (e.g. `Machine_Learning_Fundamentals.pdf`) is in the same directory.

3. Launch the app:
    ```bash
    python gradio_app.py
    ```

4. Open the provided local URL and start asking questions!

## 💡 Example Questions
- `What is overfitting?`
- `Explain backpropagation.`
- `What are hyperparameters and why are they important?`
