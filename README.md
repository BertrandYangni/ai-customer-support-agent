# AI Customer Support Agent

> This is a learning project. All credit for the course design goes to the original author.

## What it does

An AI customer support agent that connects to a Gmail inbox, reads incoming emails, searches a knowledge base, and drafts or sends replies. Everything is stored in a database, tested with evals, managed from an admin dashboard, and deployed to a real server with Docker.

## Tech stack

| Layer | Tool |
|---|---|
| Email | Gmail API |
| Backend | FastAPI (Python) |
| AI agent | Pydantic AI + Claude |
| Database | Supabase |
| Testing | Evals |
| Admin dashboard | React |
| Deployment | Docker on a Hostinger VPS |

## Project structure

_To be filled in as the project grows._

## Setup

```bash
git clone https://github.com/BertrandYangni/ai-customer-support-agent.git
cd ai-customer-support-agent
python3 -m venv .venv
source .venv/bin/activate
cp .env.example .env   # then fill in your own keys
```

Required secrets (kept in `.env`, never committed):

- Anthropic API key
- Supabase URL and key
- Gmail API credentials (OAuth client file and token)

## Run

_To be added as the course progresses._

## What I learned

_Short notes per section: what worked, what broke, what I would change._

## Author

Bertrand Yangni - [GitHub](https://github.com/BertrandYangni) - [LinkedIn](https://linkedin.com/in/bertrand-yangni)
