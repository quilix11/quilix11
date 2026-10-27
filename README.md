# quilix11

I write Python APIs and CLI tools, build Flutter apps, and learn how to run them. My repos cover equipment tracking, Git tooling, Telegram bots, language learning and a few infrastructure experiments.

Lately I've been working with **Kubernetes**: deployments, services, ConfigMaps and resource limits. My **Terraform / AWS** project covers networking, EC2, load balancing, PostgreSQL and S3.

### Projects

<table>
<tr>
<td width="50%" valign="top">

**[ohymeku](https://github.com/quilix11/ohymeku)**

An app for practicing English with AI characters. Voice conversations, vocabulary review, grammar exercises and a story with choices. Progress is saved locally.

`Dart` `Flutter` `Gemini` `STT / TTS`

</td>
<td width="50%" valign="top">

**[-FAE](https://github.com/quilix11/-FAE)**

Tracks applicators across machines and zones: who's using them, where they moved and whether a location has capacity. Operator roles, movement logs and live dashboards.

`Python` `FastAPI` `SQLAlchemy` `WebSockets`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[git-reviewer](https://github.com/quilix11/git-reviewer)**

A pre-commit hook that sends the staged diff to Gemini and prints a review in the terminal. A critical result blocks the commit.

`Python` `Git hooks` `Gemini` `Rich`

</td>
<td width="50%" valign="top">

**[wiki-quizlet](https://github.com/quilix11/wiki-quizlet)**

A Telegram quiz built around Ukrainian Wikipedia. Read an article, answer questions and track your score. Includes AI and rule-based question generation.

`Python` `Telegram` `Gemini` `SQLite`

</td>
</tr>
</table>

### What I use

| | |
| :--- | :--- |
| Backend | Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, SQLite, Alembic |
| Background work | Redis, Taskiq, async HTTP clients |
| Apps & web | Dart, Flutter, JavaScript, HTML/CSS, Bootstrap |
| AI & bots | Gemini API, Telegram, speech recognition, text-to-speech |
| Tools & deployment | Git, Typer, Rich, Docker, Compose, GitHub Actions, Pages |
| Learning | Kubernetes, Terraform, AWS |

In the tracking backend I'm working with domain models, separate command/query handlers, dependency injection and Unit of Work. In the app projects, the work also includes local storage, voice input, progress and the interface around it.

<details>
<summary><strong>Other repos — tools, prototypes and experiments</strong></summary>

| Repo | What is in it |
| :--- | :--- |
| [webhook-replay](https://github.com/quilix11/webhook-replay) | Receive, store, inspect and resend webhooks. Async API, migrations and API tests. |
| [state-vault](https://github.com/quilix11/state-vault) | A CLI/API prototype for finding configuration files and pushing or pulling backups. |
| [ast-graph](https://github.com/quilix11/ast-graph) | Python AST → Gemini → Mermaid diagrams. Experimental; the latest version has known errors. |
| [stratum](https://github.com/quilix11/stratum) | Early workspace/content models and a plugin-based Markdown/TXT parser. |
| [uptime-service](https://github.com/quilix11/uptime-service) | HTTP checks, scheduled Taskiq jobs and Redis results. Paused prototype. |
| [AWS](https://github.com/quilix11/AWS) | Terraform definitions for VPC, EC2, ALB, RDS, S3 and IAM. |
| [k8s](https://github.com/quilix11/k8s) | Deployment, Service and ConfigMap manifests, with CPU/memory requests and limits. |
| [hf-space-waker](https://github.com/quilix11/hf-space-waker) | A GitHub Actions schedule that sends a request to a Hugging Face Space. |
| [quilix11.github.io](https://github.com/quilix11/quilix11.github.io) | A responsive Ukrainian café website, deployed with GitHub Pages. |

</details>
