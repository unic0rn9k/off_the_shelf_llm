# Basic off the shelf llm RAG solution 👌
1. install [rye](https://rye.astral.sh/), which is a very easy and simple package manager.
2. Install [Ollama](https://ollama.com/download).
2. Clone this repository, and run `rye sync` from the root of the project. (This installs all the packages needed to run the notebook)
3. Download the main language model fx with `ollama run qwen2.5-coder:7b`
4. run `rye run jupyter lab RAG.ipynb` to open the notebook
5. When you are in the notebook press `run` in the top toolbar, then press `run all cells`

# Easy improvements
- Spell checking in strins in jupyter (so you don't misspell you prompts...)
- LSP for completion of variable names etc
