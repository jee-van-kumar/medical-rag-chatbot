# medical-rag-chatbot
Retrieval-Augmented Generation (RAG) chatbot for answering medical queries using LangChain, Pinecone Vector Database, Hugging Face embeddings, and Groq LLMs.


# Demo
![Demo Video](https://github.com/jee-van-kumar/medical-rag-chatbot/blob/main/demo.mp4)


# Features
- Extracts text from medical PDF documents
- Splits documents into meaningful chunks
- Generates vector embeddings using Hugging Face models
- Stores embeddings in Pinecone Vector Database
- Performs semantic similarity search
- Uses Groq Llama 3.3 for response generation
- Implements LangChain RAG pipeline
- Flask backend API
- Interactive chatbot web interface
- Fast context-based medical question answering

# Tech Stack

## Backend
- Python
- Flask
- LangChain

## LLM
- Groq Llama 3.3

## Embeddings
- Hugging Face Sentence Transformers

## Vector Database
- Pinecone

## Frontend
- HTML
- CSS


---

# Installation & Setup

## 1. Clone Repository

```bash
git clone https://github.com/jee-van-kumar/medical-rag-chatbot.git

```
## 2. Navigate into the project

```bash
cd medical-rag-chatbot
```
## 3. Create Virtual Environment

```bash
py -3.10 -m venv myenv

```
## 4. Activate Virtual Environment

### Windows
```bash
venv\Scripts\activate

```
### Linux/Mac
```bash
source venv/bin/activate
```
## 5. Install Dependencies

```bash
pip install -r requirements.txt
```
#  Environment Variables

## Create a `.env` file in the root directory

```env
PINECONE_API_KEY=your_pinecone_api_key
GROQ_API_KEY=your_groq_api_key
```
# Running the Application 

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```
### The aplication will run at http://localhost:5000







