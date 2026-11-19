# AI Customer Support Agent

My follow-along build of the **AI Engineering Full Course - Build and Deploy a Real AI App** by Dave (Datalumina).

- Video: https://www.youtube.com/watch?v=XzjSx7u9mGw
- Course handbook: https://learn.datalumina.com/docs/customer-support-automation
- Prerequisite (Python basics): https://www.youtube.com/watch?v=ygXn5nV5qFc

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

## Course progress

- [ ] Introduction (0:00)
- [ ] Project setup (6:57)
- [ ] Gmail API access (20:37)
- [ ] Gmail client (36:23)
- [ ] The poller (45:27)
- [ ] Database (53:48)
- [ ] First reply (1:10:36)
- [ ] Knowledge base (1:18:14)
- [ ] AI pipeline (1:23:21)
- [ ] Evals (1:55:31)
- [ ] Server setup (2:08:41)
- [ ] Deploy with Docker (2:23:41)
- [ ] Admin dashboard (2:44:54)
- [ ] Wrap up (3:05:19)

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
