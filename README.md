# Hi, I'm Salman Arif

**Senior Full Stack Software Engineer · Python backends, background jobs & AI automation**

I build APIs, SaaS backends, and automation tools with Python, Django, FastAPI, and PostgreSQL. My current open-source work focuses on understanding failed background jobs and building agents that verify the results of their actions.

## Start here: QueueLoom

**See what happened to a background job, from queue to failure or success.**

[**Try the local demo →**](https://github.com/Salman85365/queueloom#try-the-demo) · [Source code](https://github.com/Salman85365/queueloom) · [Tests](https://github.com/Salman85365/queueloom/tree/main/tests)

QueueLoom records task timelines, queue latency, retries, and exceptions, with a dashboard for investigating failures. The main focus is Celery; adapters for other Python task frameworks are included.

- **Explore:** task lifecycle tracking, event ingestion, failure-rate alerts, and incident summaries.
- **Try it:** the local demo runs sample jobs using SQLite and an in-memory Celery broker.
- **Status:** pre-alpha, under active development.

## More projects

### [OpsMender](https://github.com/Salman85365/opsmender)

Diagnose a broken Docker Compose stack, propose a recovery plan, and verify the result after approved actions.

- **Explore:** evidence collection, deterministic diagnosis, an optional LLM reasoner, and bounded recovery actions.
- **Try it:** [five bundled failure scenarios](https://github.com/Salman85365/opsmender/tree/main/demo).
- **Status:** pre-release. [Tests](https://github.com/Salman85365/opsmender/tree/main/tests) and validation notes are in the repository.

### [PiKVM Work Agent](https://github.com/Salman85365/Pikvm-work-agent)

A local Python agent that observes and operates a remote computer through PiKVM, without installing software on the remote machine.

- **Explore:** screenshot perception, keyboard/mouse actions, local policy checks, and visual verification.
- **Status:** experimental; the README separates hardware-validated milestones from workflows still awaiting validation.
- [Architecture and usage](https://github.com/Salman85365/Pikvm-work-agent#readme) · [Tests](https://github.com/Salman85365/Pikvm-work-agent/tree/main/tests)

## Engineering background

My professional experience includes Django applications, REST APIs, permissions and business workflows, asynchronous processing, cloud deployments, and LLM-assisted data processing.

| Area | Tools I work with |
| --- | --- |
| Backend | Python, Django, Django REST Framework, FastAPI |
| Data & jobs | PostgreSQL, Redis, Celery, RabbitMQ |
| Infrastructure | Docker, Linux, AWS, Azure, CI/CD |
| Frontend | Vue.js, Quasar, Tailwind CSS |
| Quality & AI | Pytest, Ruff, LLM integrations, tool use, multimodal workflows |

## Current focus

Making QueueLoom easier to try, testing failure and retry behavior, and improving the reliability of automation through an **observe → reason → act → verify** loop.

I'm interested in collaborating on Python developer tools, backend systems, and practical AI automation.

[LinkedIn](https://www.linkedin.com/in/salman-arif-backend/) · [Upwork](https://www.upwork.com/freelancers/~01ca6d26d92f5d5a1b)
