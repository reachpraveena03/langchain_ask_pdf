# langchain_ask_pdf
Ask Your PDF – Powered by LangChain
This is a Python app that lets you upload a PDF and ask questions about it in plain English. It uses a language model (LLM) to understand your question and give answers based only on the content of the uploaded PDF — it won't answer anything outside the document.

Here's how it works:
The app reads your PDF and breaks it down into smaller sections. Then, it turns those sections into smart number-based formats (called embeddings) using OpenAI. When you ask a question, it looks for the parts of the PDF that are most related to what you asked and sends those to the language model to generate an accurate response.
