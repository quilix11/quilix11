<p>
  <img src="assets/header.svg" width="100%" alt="quilix11 — Python, backend and infrastructure" />
</p>

<h3><samp>01 / ABOUT</samp></h3>

I write Python APIs, CLI tools and Telegram bots. My projects cover equipment tracking, code review, webhook debugging, configuration backups and monitoring.

I'm also learning the infrastructure side: **Kubernetes** deployments, services and configuration, plus **Terraform / AWS** networking, compute, databases and storage.

<h3><samp>02 / PROJECTS</samp></h3>

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/-FAE"><samp>-FAE</samp></a></h3>

Equipment tracking across machines and zones. Capacity rules, operator roles, movement history and live dashboard updates.

`FastAPI` `SQLAlchemy` `WebSockets`

<sub>CQRS · Unit of Work · dependency injection</sub>

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/git-reviewer"><samp>git-reviewer</samp></a></h3>

A pre-commit hook that sends the staged diff to Gemini and prints a terminal review. A critical result blocks the commit.

`Python` `Git hooks` `Gemini` `Rich`

<sub>Staged diff → review → commit decision</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/webhook-replay"><samp>webhook-replay</samp></a></h3>

Receive a webhook, save its headers and payload, inspect it, then replay it to another endpoint. Includes migrations and API tests.

`FastAPI` `async SQLAlchemy` `httpx`

<sub>Receive → store → inspect → replay</sub>

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/wiki-quizlet"><samp>wiki-quizlet</samp></a></h3>

A Telegram quiz based on Ukrainian Wikipedia. Article reading, AI and rule-based question generation, player scores and rankings.

`Python` `Telegram` `Gemini` `SQLite`

<sub>Articles → questions → quiz rounds</sub>

</td>
</tr>
</table>

<h3><samp>03 / STACK</samp></h3>

| | Tools in my projects |
| :--- | :--- |
| **Backend** | `Python` `FastAPI` `Pydantic` `SQLAlchemy` `Alembic` |
| **Data & workers** | `PostgreSQL` `SQLite` `Redis` `Taskiq` `asyncio` `httpx` |
| **CLI & automation** | `Git` `Typer` `Rich` `GitHub Actions` |
| **Containers** | `Docker` `Compose` |
| **Infrastructure practice** | `Kubernetes` `Terraform` `AWS` |

<h3><samp>04 / INFRASTRUCTURE</samp></h3>

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/k8s"><samp>k8s</samp></a></h3>

Deployment, Service and ConfigMap manifests. Working through replicas, application/database workloads and CPU/memory requests and limits.

`Kubernetes` `YAML`

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/quilix11/AWS"><samp>AWS</samp></a></h3>

Terraform definitions for VPCs and subnets, EC2, an application load balancer, RDS PostgreSQL, S3 and IAM.

`Terraform` `HCL` `AWS`

</td>
</tr>
</table>

<details>
<summary><samp>05 / MORE REPOS</samp></summary>

| Repo | What is in it |
| :--- | :--- |
| [state-vault](https://github.com/quilix11/state-vault) | A CLI/API prototype for finding configuration files and pushing or pulling backups. |
| [ast-graph](https://github.com/quilix11/ast-graph) | Python AST → Gemini → Mermaid diagrams. Experimental; the latest version has known errors. |
| [stratum](https://github.com/quilix11/stratum) | Early workspace/content models and a plugin-based Markdown/TXT parser. |
| [uptime-service](https://github.com/quilix11/uptime-service) | HTTP checks, scheduled Taskiq jobs and Redis results. Paused prototype. |
| [hf-space-waker](https://github.com/quilix11/hf-space-waker) | A scheduled GitHub Actions request to a Hugging Face Space. |

</details>
