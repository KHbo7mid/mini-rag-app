# mini RAG 

This is a minimal implementation of the RAG model for question answering 


## Requirements

- Python 3.13 or later 


### Install Python using MiniConda

1) Download and install MiniConda from [here](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)

2) Create a new environment using the following command:
```bash
$ conda create -n mini-rag python=3.13
```
3) Activate the environment:
```bash
$ conda activate mini-rag
```

## Installation 

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```
set your environment variables in the `.env` file .

## Run the FastAPI server

```bash
$ uvicorn main:app --reload 
```