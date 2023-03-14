# LangChain Toy

This is a collection of notebooks for experimenting with the [LangChain](https://langchain.readthedocs.io/en/latest/index.html) package.

## Environment Setup

Using LangChain will usually require integrations with one or more model providers, data stores, apis, etc.

For this example, we will be using OpenAI's APIs, so we will first need to install their SDK:

```bash
pip install openai
```

We will then need to set the environment variable in the terminal.

```bash
export OPENAI_API_KEY="..."
```

Alternatively, you could do this from inside the Jupyter notebook (or Python script):

```python
import os
os.environ["OPENAI_API_KEY"] = "..."
```