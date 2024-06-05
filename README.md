
# RAG Q&A Chatbot 

Introducing the RAG Chatbot: Retrieval-Augmented Generation an advanced Q&A tool designed to read and interact with multiple PDF files simultaneously. Powered by the Gemini Pro LLM model for robust natural language understanding, it utilizes FAISS Vector DB for efficient word embeddings. The user-friendly interface is built with Streamlit and hosted on Huggingface Space, making it easily accessible for seamless interactions with your documents. Explore and ask questions about your PDFs effortlessly .

## Demo

![Your GIF Description](https://s10.gifyu.com/images/SYhw6.gif)

## Checkout
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
Link : https://huggingface.co/spaces/Mannan7/Chat_with_PDF

## Deployment

To deploy this project run

```bash
    git clone https://github.com/Dev-Mannan/RAG_Q-A_Chatbot.git
```

To create conda enviorment run
```bash
    conda create -p venv  python==3.12
```

To activate conda enviorment run
```bash
    conda activate venv
```
create your .env file and paste your Gemini pro API key from google studio
```bash
    link : https://aistudio.google.com/app/apikey
```
Now install the Dependencies execute requirements.txt
```
pip install -r requirements.txt
```
All set now run this app using this command
```
streamlit run app.python
```

Thank you .
