# The Backend Engineer's Field Library

A landing page tying together six battle-tested playbooks — **6 playbooks, 325 topics, one connected mental model** for the whole modern backend stack.

🔗 **Live:** https://baluraut.github.io/field-library/

## The six playbooks

| Playbook | Topics | Covers |
| --- | --- | --- |
| [PostgreSQL Pro Playbook](https://baluraut.github.io/postgres-pro-playbook/) | 46 | UPSERT, window functions, JSONB, indexing, tuning |
| [Ruby &amp; Rails Pro Playbook](https://baluraut.github.io/ruby-rails-pro-playbook/) | 104 | 52 Ruby + 52 Rails — language to production |
| [EKS · ECR · CircleCI Playbook](https://baluraut.github.io/eks-ecr-circleci-playbook/) | 60 | Containers → Kubernetes → CI/CD deploys |
| [Linux &amp; Networking Playbook](https://baluraut.github.io/linux-networking-playbook/) | 60 | The machine, the shell, TCP/IP, debugging |
| [MCP Server Playbook](https://baluraut.github.io/mcp-server-playbook/) | 25 | Building MCP servers — primitives, transports, OAuth, trust |
| [Agentic AI Playbook](https://baluraut.github.io/agentic-ai-playbook/) | 30 | LLM agents, the agent loop, RAG, evals &amp; safety |

## Why one library

These aren't four subjects — they're one stack seen from four heights, and the playbooks cross-reference each other on purpose: a Rails N+1 becomes a Postgres query plan; a container is a Linux process with a cgroup, so a Kubernetes `OOMKilled` and a bare-metal OOM are the same event; jsonb reappears as `store_accessor`; a CIDR block is a CIDR block whether it's a subnet or a VPC.

## View locally

Open `index.html` in a browser. Its cards link to the other four sites once they're published.

## Publish (GitHub Pages)

Push to a repo named `field-library` (or use it as your root `baluraut.github.io` user page), then **Settings → Pages → Source: `main` / root**.

Each linked playbook must be published under the matching repo name for the cards to resolve.
