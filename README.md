# Install Ollama

* Visit https://ollama.com/
* Download the installer according to your OS
* Open a console and download the LLM model, for these examples Llama 3: `ollama pull llama3`

# Configure Python local environment

```
$ python3 -m venv venv
$ source venv/bin/activate

````
Install the Python packages for these examples

```
# For first example
pip install jupyterlab ollama

# For 2nd example
pip install langchain langchain_community langchainhub chromadb 

# For 3rd example
pip install llama-index llama-index-llms-ollama
```


# Run Examples

Open a jupyter notebook

```
$ jupyter notebook
```

