# LLM Notebook

## Setup

It's assumed that `pyenv` is used for `virtualenv`.

```shell
pyenv install 3.9.6
pyenv virtualenv 3.9.6 llm
pyenv activate
pip install -r requirements.txt
```

To use OpenAI either pass it in the constructor, set the `OPENAI_API_KEY`
environment variable, or create the file `~/.openai_api_key` with your key in
it.

## Starting Jupyter

This should be done from a terminal with an active `virtualenv`, do that with
`pyen activate`.

```shell
jupyter lab
```

A browser window should be opened to http://localhost:8888/lab.
