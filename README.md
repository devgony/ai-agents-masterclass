# 0 Introduction

## 0.3 Why So Many Frameworks

- There is no startdard in ai-agent industry yet.
- So We are gonna learn slightly different 5 frameworks.

## 0.4 Course Structure

- high level to low
  - CrewAI
  - MS Autogen
  - OPENAI Agent SDK
  - Google Agent Devkit
  - LangGraph
- agent: just while true loop

## 0.6 Breaking Changes

- Watch and follow as soon as possible
- Adapt to the changes
  - Go to docs and find differences
  - Share differences each other
- Study concepts not specific api or functions

## 1.0 UV

```sh
uv init example-agent
```

## 1.1 PyProject

- install pacakges
  - configurate with pyproject.toml
  - create .venv, uv.lock

```sh
# add pyproject.toml
uv sync
```

- add packages

```sh
uv add {package_name}
```

- how to run

  1. IDE will run source .~
  2. maunally run `source .venv/bin/activate`
     - or in windows `.venv\bin\activate.ps1`
  3. or use `uv run main.py`

- install pylance on vsc

## 1.2 Jupyter

- install Jupyter extension
- create `main.ipynb`

```sh
uv add ipykernel --dev
```
