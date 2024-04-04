# Knowledge Retrieval with LLMs & LangChain

SFI IT Academic Festival workshop content.

## Installation 

### Download the content

```commandline
git clone https://github.com/pbudzyns/rag_workshop.git
```

### Install dependencies

```commandline
cd rag_workshop
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Install Ollama or get API token

To run the notebooks you will need Ollama installed (recommended). 
Alternatively you can use OpenAI API key or a model from HuggingFace.

To install Ollama follow the [instructions](https://ollama.com/download).
After installation run `ollama run llama2` to pull the model and verify that everything 
is working well. 

To get OpenAI API token you will have to create OpenAI account. 

## Run the notebooks
Run the command below in your shell (having venv activated) and go to 
[localhost:8888](localhost:8888)
```commandline
jupyter notebook
```
