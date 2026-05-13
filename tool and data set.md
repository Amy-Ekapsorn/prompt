One-Stop Resource Hub

Tools to Install (Do this tonight)

bash
# Terminal - copy and paste
brew install python@3.11 docker git ollama
brew install --cask cursor

# Python packages
pip install pandas pyarrow boto3 pytest black ruff pyspark findspark apache-airflow langchain openai anthropic chromadb streamlit

# Pull local LLM (for offline AI)
ollama pull codellama:7b
API Keys (Use your $200 budget)

Service	Sign up	Put $
OpenAI	platform.openai.com	$20
Anthropic	console.anthropic.com	$0 (free tier)
AWS	aws.amazon.com	$180 remaining
Datasets (Download as needed)

Dataset	Size	Link	When
NYC Taxi (2023)	50-200GB	Link	Week 3-4
NOAA Weather	100GB	Link	Week 2
GitHub Archive	Streaming	Link	Week 6
Amazon Reviews	80GB	Link	Week 8
Learning Platforms (Bookmark)

Resource	Link	Use
PySpark docs	spark.apache.org/docs/latest/api/python	Daily reference
Airflow docs	airflow.apache.org/docs	Week 5
LangChain	python.langchain.com	Week 7-8
AWS free tier	aws.amazon.com/free	Week 7-8
Your AI Prompt Library (Save this file)

Create ~/dataeng/ai-prompts/master-prompts.md:

markdown
# CODE GENERATION
"Generate [tech] code that [task]. Include error handling, logging, type hints. Use best practices."

# DEBUGGING
"My job failed with [error]. Code: [paste]. Logs: [paste]. Give me 3 hypotheses ranked by likelihood."

# ARCHITECTURE
"Design a pipeline for [use case]. Constraints: [budget, latency, scale]. Give me 3 options with trade-offs."

# CODE REVIEW
"Review this production pipeline code. Check: idempotency, memory, security, tests. Score 1-10."

# LEARNING
"Teach me [concept] using Feynman technique. Then quiz me. Then tell me what I misunderstood."
