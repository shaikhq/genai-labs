# 🧠 Watsonx.ai Research Agent

This project contains a Jupyter notebook that demonstrates how to build a personal AI research assistant using IBM Watsonx.ai, LangChain, and LangGraph. The assistant can find and summarize recent research papers from repositories like arXiv based on a user prompt.

---

## 📦 Environment Setup

This project was developed with:

- **Python 3.12**
- **Red Hat Enterprise Linux 9.4**
- **VS Code**
- **[uv](https://github.com/astral-sh/uv)** (fast, drop-in replacement for pip)

### 🔧 Prerequisites

Make sure you have the following installed on your system:

- Python 3.12 (`/usr/bin/python3.12`)
- `uv` package manager ([installation instructions](https://github.com/astral-sh/uv#installation))
- Git (optional, for cloning)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/shaikhq/genai-labs.git
cd genai-labs/search-agent
````

### 2. Create and activate a virtual environment using `uv`

```bash
uv venv wxai-chat --python /usr/bin/python3.12
source wxai-chat/bin/activate
```

### 3. Install dependencies

```bash
uv pip install -r requirements.txt
```

---

## 🔐 Configure Environment Variables

Create a `.env` file in the project folder with the following keys:

```dotenv
WATSONX_API_KEY=your_watsonx_api_key
WATSONX_URL=https://your_watsonx_instance_url
WATSONX_PROJECT_ID=your_project_id
```

These credentials are required to access the Watsonx.ai APIs.

---

## 🧪 Launch the Notebook

After setup is complete, open the notebook in VS Code or Jupyter:

```bash
code .  # or open the notebook manually
```

Then run the notebook:
`research-paper-search.ipynb`

---

## 📁 File Structure

```
search-agent/
├── research-paper-search.ipynb   # Main notebook
├── requirements.txt              # Python dependencies
├── .env                          # Your API keys (not tracked)
└── README.md                     # Project instructions
```

---

## ✅ Output

The agent will:

* Classify your prompt into an arXiv domain
* Search for recent papers
* Present abstracts and links
* Summarize results using Watsonx.ai LLM

---

---

## ✍️ Author

Shaikh Quader
[LinkedIn](https://www.linkedin.com/in/shaikhquader)
