# Prompt-Tuning Playground

🧪 A hands-on tool for experimenting with and comparing large language model (LLM) prompts.

## 🚀 Features
- Compare multiple prompts side-by-side
- Inject user input into prompt templates
- View LLM responses with ratings and comments
- Save and load history of prompt runs for later review

## 📦 Tech Stack
- Python
- [Streamlit](https://streamlit.io)
- OpenAI API (or other LLM endpoints)
- Local JSON for lightweight storage

## 📂 Project Structure
```
prompt-tuning-playground/
├── app.py                   # Streamlit front-end
├── utils/
│   ├── prompt_runner.py    # LLM API interface and prompt handling
│   └── history.py          # History load/save functionality
├── prompts/
│   └── history.json        # Stored prompt evaluations
```

## 🔧 Setup
1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/prompt-tuning-playground.git
cd prompt-tuning-playground
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the app:
```bash
streamlit run app.py
```

## 🛠 Requirements
- Python 3.8+
- OpenAI API key (set as `OPENAI_API_KEY` env variable)

## 📘 License
MIT

## 📄 requirements.txt
```
streamlit
openai
python-dotenv
```
*You may need to add additional dependencies later, like `langchain` or `faiss` if you expand the project.*

