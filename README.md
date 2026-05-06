# Multi-Agent AutoGen Research Assistant

A collaborative AutoGen workflow that coordinates planner, engineer, scientist, executor, and critic agents to find and classify recent arXiv papers.

## Why this project matters
This repository demonstrates practical Generative AI engineering skills: model integration, agent workflows, prompt engineering, data preprocessing, tool use, and reproducible notebook-based experimentation.

## Recruiter-ready skills shown
- Multi-agent orchestration with Microsoft AutoGen
- Role-based agent design: planner, executor, scientist, critic
- OpenAI API integration using environment variables
- Research automation and structured markdown output
- Prompt engineering and workflow governance

## Project structure
```text
.
├── notebooks/
│   └── multi-agent_autogen_research_assistant.ipynb
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Setup
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## How to run
1. Open the notebook in Jupyter, VS Code, or Google Colab.
2. Install dependencies from `requirements.txt`.
3. Add required API keys as environment variables, never directly inside the notebook.
4. Run cells from top to bottom.
