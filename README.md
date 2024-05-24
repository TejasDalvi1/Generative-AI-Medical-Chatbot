===============================================================================
# Generative-AI-Medical-Chatbot
===============================================================================

## Tech stack:
        (1)Python
        (2)Langchain
        (3)Flask
        (4)Meta Llama2 LLM
        (5)Pinecone (Vector DB)
-------------------------------------------------------------------------------

## Steps to run:

### (1) Create Environment
```bash
conda create -n medchatbot python=3.8 -y
```
```bash
conda activate mchatbot
```

### (2) Install "requirements.txt"
```bash
pip install -r requirements.txt
```

### (3) Create a `.env` file in the root directory and add your Pinecone credentials:
```ini
PINECONE_API_KEY = "Put_Your_Key"
```
### (4) Download the quantized Llama2 model from the link provided in "instructions.txt" from model folder & keep the model in the model directory

### (5) To create index in Pinecone (Vector DB):
```bash
# run the following command
python store_index.py
```
### (6) Run "app.py":
```bash
# Finally run the following command
python app.py
```

### (7) Click on the link got after step (6):
```bash
open up localhost:
```
-------------------------------------------------------------------------------