# Ollama examples
Collection of Jupyter notebooks demonstrating how to use ollama.


I wrote an interoductory blog post on Ollama: [Ollama: The local LLM solution](http://programmer.ie/post/ollama/)



## Install
```
cd d:\projects\ollama-notes
python -m venv ollama-env
ollama-env\Scripts\activate
pip install -r requirements.txt
```

# Update context size of a model
```
ollama run llama3.2
>>> /set parameter num_ctx 131072
```


Notebook | Description
---|---
[chat](/notebooks/chat.ipynb) | Demonstrates simple chatbot functionality using Ollama.  
[list_models](/notebooks/list_models.ipynb) | List  installed Ollama Models  
[Log_file_analyzer](/notebooks/log_file_analyzer.ipynb) | Use Ollama to analyze a log file.  
[pull](/pull.ipynb) | Pull a model.
[template](/notebooks/template_example.ipynb) | Shows how we can use the model to fill in a template with some text data.
[huggingface](/notebooks/huggingface.ipynb) | Pull a model from Hugging Face.
[function_calling](/notebooks/function_calling.ipynb) | Use Ollama to call a function.
[rest_api](/notebooks/rest_api.ipynb) | Use Ollama via the REST API.
[sql](/notebooks/sql.ipynb) | Use Ollama to query a SQL database.
[rag](/notebooks/rag.ipynb) | RAG example.

