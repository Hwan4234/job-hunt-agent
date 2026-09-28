# Job Hunt Agent

An AI agent that uses tools to search job postings, evaluate how well they match
my resume, and track application progress.

> Status: In development

## Planned Features
- Search job postings from company career pages
- Read a resume and score its fit against each posting
- Identify skill gaps for a given role
- Save postings and track application status

## How It Works
The agent runs a loop: the language model decides which tool to call,
the program executes that tool, and the result is sent back to the model.
This repeats until the model has enough information to answer.

## Tech Stack
- Python, uv
- Anthropic Python SDK (tool use)
- httpx, Greenhouse Job Board API
- SQLite
- pytest

## Roadmap
- [x] Project setup
- [ ] Minimal agent loop with a mock tool
- [ ] Real job search tool
- [ ] Resume reader and fit scoring
- [ ] Application tracker with SQLite
- [ ] Web UI
- [ ] MCP server
