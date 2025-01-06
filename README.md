# Chat with PDF: Interactive PDF-based Conversations

---
license: apache-2.0
title: PDF Chat
sdk: streamlit
emoji: 📚
colorFrom: red
colorTo: blue
short_description: Streamlit app for PDF Chat
---

This Streamlit application enables users to upload PDF documents and interactively query their content using a powerful AI-based retrieval and question-answering system.

##  Features

- **Multiple Session Management:** Create and manage multiple sessions to keep your work organized.
- **PDF Upload and Processing:** pload one or more PDFs, which are processed for efficient retrieval.
- **Interactive Q&A:** Query your PDFs in natural language and receive precise answers.
- **Conversation History:** View a history of your questions and the model's responses for each session.


## Setup

Clone the repository:
```bash
git clone https://github.com/Skrasool1197/Chat-With-PDF.git
cd Chat-With-PDF
```

Create a virtual environment with python version of 3.11.


Install the required dependencies:
```bash
  pip install -r requirements.txt
```

Run the application:
```bash
streamlit run app.py
```
## API Reference




| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `groq_api_key` | `string` | **Required**. Your API key |
`huggingface_api_key` | `string`| **Required**. Your API key|

 






## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`GROQ_API_KEY`

`HUGGINGFACE_API_KEY`



## Usage Instructions



1. Enter Your Groq API Key
- Open the app in your browser (the URL is displayed in the terminal after running the app).
- In the sidebar, input your Groq API key. This key is essential for interacting with the AI model.
2. Start or Select a Session
- To create a new session:
- Click "➕ New Session" in the sidebar.
- Provide a unique session ID and click "Start Session".
- To switch to an existing session:
- Select it from the dropdown menu in the sidebar.
3. Upload PDF(s)
- Use the Upload PDF Document section to upload one or more PDF files.
- The system will process the documents, splitting them into manageable chunks for querying.
4. Ask Questions
- Use the Chat With Your Document input box to ask questions about the uploaded documents.
- The app will retrieve relevant information and provide concise, context-aware answers.
5. Review Conversation History
- View previous questions and responses in the Conversation History section.
- Each question and its corresponding answer are displayed for easy reference.



## Deployment


This project is deployed on Huggingface Spacess, you can access using following url:
 ```bash
      https://huggingface.co/spaces/LeviAc/Chat_PDF
```

