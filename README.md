# Simple RAG powered by football articles.

This repository provides an easy-to-follow example of a RAG system based on (synthetic) football articles.

It’s designed to be a building block for broader applications, like chatbots, knowledge assistants, or search interfaces.

We’ll also be publishing an article soon on [our blog](https://www.notion.so/pc1913-perf-analytics/Giallobl-Open-Analytics-Lab-4b5f473392624f05a87229ffc16c4b22) that dives deeper into the potential applications.

## Installation
```
git clone https://github.com/parmacalcio1913/a-football-rag.git
cd a-football-rag
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Once you cloned the repo and install the dependencies, you need to set up the environment variables in `.env` file, similar to what shown in the `example.env` file.

```
OPEN_AI_API_KEY="sk-MyUniqueOpenAiKey" # your OpenAI key here
OPEN_AI_MODEL="gpt-4o-mini" # or another model
```

## Usage
Run the `rag.ipynb` file.

The notebook will show you how to:

1. Upload documents to a Vector Store
2. Search the Vector Store using the Responses API
3. Build a very simple Q&A flow

## Blog & Resources
For more football analytics tutorials, insights, and open data projects, visit our blog: [G.O.A.L. - Gialloblù Open Analytics Lab](https://www.notion.so/pc1913-perf-analytics/Giallobl-Open-Analytics-Lab-4b5f473392624f05a87229ffc16c4b22)

## What's next
The repo is intentionally minimal. Soon, we will publish an article to show you possible extensions (like the addition of support for multiple files research and/or web search), and how it can be wrapped into a chatbot.
