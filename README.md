# LangChain Chains & Runnables Demo

This repo contains two demo files showing how to build pipelines in LangChain using **Chains** and **Runnables**.

## Files
- `simple_chain.py` → Generates 5 interesting facts about a topic and shows the pipeline DAG.
- `multi_step_chain.py` → Creates a detailed report on a topic, then summarizes it into 5 points using a multi-step pipeline.

## Setup
1. Clone the repo
2. Create a virtual environment
   ```bash
   python -m venv .venv
   .venv\Scripts\activate      # Windows
3. Install requirements
```bash
pip install -r requirements.txt
4. Add your OpenAI API key in .env
.env
OPENAI_API_KEY=sk-xxxxxx

Run
====
```bash
python simple_chain.py
python multi_step_chain.py


Expected Output
--------------------
Generated text (facts or report + summary)
ASCII DAG diagram of the pipeline
Refer attached output screenshots. 