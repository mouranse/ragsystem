# mini-rag

## Requirements

- python 3.8 or later

#### install python using miniconda

1) download and install miniconda

2) create a nwe enviroment using the following command:
```bash
$ conda create -n mini-rag pyhton=3.8
```
3) activate the enviroment:
```bash
$ conda activate mini-rag
```
### (optional) setup your command line interface for better readability

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## installation

### install the required packages

```bash
$ pip install -r requirements.txt
```

### setup the enivroments variables

```bash
$ cp .env.example .env
```
set your enviroment variables in the `.env` file. like `OPENAI_API_KEY` value.

## run the fastapi server

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```
