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

# 2.Your First AI Agent

## 2.0 Setup

```sh
uv init my-first-agent
cd my-first-agent
```

```toml
# my-first-agent/pyproject.toml
[project]
name = "my-first-agent"
version = "0.1.0"
description = "Add your description here"
readme = "README.md"
requires-python = ">=3.13"
dependencies = [
    "openai>=1.98.0",
]

[dependency-groups]
dev = [
    "ipykernel>=6.30.0",
]
```

```sh
uv python pin 3.13
uv sync
```

```sh
OPENAI_API_KEY=xx
```

## 2.1 Your First AI Response

- use cheapest model: gpt-4o-mini
- n=10 will return 10 responses ordered by high probability

## 2.2 Parsing the Response

- AI agent: A system cable of performing actions on behalf of a user
  - not only just replying but also use set of tools user gave
  - It just infer the Text, if it replies with function call, we are the one who have to execute it

## 2.3 Adding Memory

- enable system memory with appending messages in While True loop

## 2.4 Adding Tools

- don't need to write prompt anymore
  - instead of prompt, pass TOOLS schema
- F/W will do TOOLS later
- model will read description and decide

## 2.5 Adding Function Calling

- `**` convert json to argument assignments
- handle optional tool_calls column with process_ai_response(message: ChatCompletionMessage)`

## 2.6 Tool Results

- All AI agent works same way
  - if tool_calls, run tools and append result to messages, then call_ai() again
  - else, just print the message content
