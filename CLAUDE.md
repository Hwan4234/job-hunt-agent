# Job Hunt Agent

## Purpose
A tool-using AI agent that searches job postings, evaluates fit against my resume,
and tracks application status. This is a GitHub portfolio project, so code
readability and documentation matter as much as functionality.

## Language Rules
- Always talk with me in Korean during our conversations.
- Write everything that goes into the repository in English: code, comments,
  docstrings, commit messages, README, and other docs.
- When a new concept or term comes up, briefly explain it to me in Korean.

## Tech Stack
- Python, managed with uv
- Anthropic Python SDK (tool use)
- httpx for calling the public Greenhouse Job Board API
- SQLite for storing application status
- pytest for testing

## Project Structure
- Uses the src layout: application code lives in src/job_hunt_agent/
- Tests live in tests/

## Working Rules
- Keep API keys in .env only. Never commit secrets.
- Put a maximum iteration limit on the agent loop.
- Write tests alongside every new feature.
- Work in small steps and check with me before moving to the next one.
- I am learning, so explain why, not just what.
- Commit messages are one-line summaries in the imperative mood
  (e.g., "Add search_jobs tool").

## Environment
- Runs on the OSU ENGR flip server (shared machine, no sudo access)
- GitHub remote uses the SSH alias github-personal (account Hwan4234)
