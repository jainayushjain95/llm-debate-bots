# 🎤 LLM Debate Bots

Three chatbots walk into a bar. One won't stop arguing, one just wants everyone to get along, and one has absolutely no idea what's going on. Welcome to the debate.

Powered entirely by local models via [Ollama](https://ollama.com) — no API keys, no cloud bill, just your GPU quietly suffering.

## 🎭 Meet the cast

| Model | Personality | Vibe |
|---|---|---|
| **GPT** (`gpt-oss:20b`) | 😈 The instigator | Disagrees on principle, snarky, will absolutely find a hole in your argument |
| **Gemma** (`gemma3:12b`) | 🕊️ The peacemaker | "Can't we all just find common ground?" |
| **Llama** (`llama3.3:70b`) | 🤝 The confused mediator | Tries to summarize the argument, gets it hilariously wrong, asks pointed questions anyway |

## 🧰 Requirements

- [Ollama](https://ollama.com) running locally (`http://localhost:11434`)
- Python 3.10+
- Patience, for when the confused mediator says something unhinged

## 🚀 Setup

```bash
pip install -r requirements.txt
ollama pull gpt-oss:20b
ollama pull gemma3:12b
ollama pull llama3.3:70b
```

## 🥊 Usage

Open `debate.ipynb`, run all cells, and grab popcorn. Change the `topic` variable to start a fight about anything you like:

```python
topic = "Should AI replace software engineers?"
```

Runs for 3 rounds. No referees. No winners. Just vibes.
