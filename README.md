# LLM Debate Bots

A three-way debate between local LLMs served via [Ollama](https://ollama.com), each playing a distinct personality:

- **GPT (gpt-oss:20b)** — argumentative and confrontational
- **Gemma (gemma3:12b)** — the peacemaker
- **Llama (llama3.3:70b)** — the confused mediator

## Requirements

- [Ollama](https://ollama.com) running locally (`http://localhost:11434`)
- Python 3.10+

## Setup

```bash
pip install -r requirements.txt
ollama pull gpt-oss:20b
ollama pull gemma3:12b
ollama pull llama3.3:70b
```

## Usage

Open `debate.ipynb` in Jupyter and run all cells. Change the `topic` variable to debate a different subject.
