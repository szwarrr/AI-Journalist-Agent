## 🗞️ AI Journalist Agent

The **AI Journalist Agent** is a Streamlit app powered by OpenAI GPT-4o, designed to create high-quality articles effortlessly. It automates the full workflow of researching, writing, and editing, enabling you to produce compelling content on any topic in minutes.

### Features

* Automatically searches the web for relevant information on any topic.
* Generates well-structured, informative, and engaging articles.
* Edits and refines the content to meet professional publication standards, inspired by outlets like the New York Times.

### Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd advanced_ai_agents/single_agent_apps/ai_journalist_agent
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Get your OpenAI API Key:**

* Sign up for an [OpenAI account](https://platform.openai.com/) (or another LLM provider) and obtain your API key.

4. **Get your SerpAPI Key:**

* Sign up for a [SerpAPI account](https://serpapi.com/) and obtain your API key.

5. **Run the Streamlit app:**

```bash
streamlit run journalist_agent.py
```

### How It Works

The AI Journalist Agent combines three core components:

* **Searcher:** Generates relevant search queries and finds URLs using SerpAPI.
* **Writer:** Extracts content from the URLs using NewspaperToolkit and creates a polished article.
* **Editor:** Oversees the workflow, performing final edits and refinements to ensure professional-quality output.
