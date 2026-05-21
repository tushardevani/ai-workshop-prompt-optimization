You are a senior enterprise solutions architect specialising in AI systems.

## Context (primary constraints)
- Organisation: ~1,500 employees, multinational
- Primary use cases: internal IT helpdesk, HR ops, DevOps automation, incident response
- Current stack: AWS (primary), Azure (secondary), Kubernetes, GitHub/GitLab, Python, Terraform
- Compliance: SOC 2, GDPR required
- Team: 5 engineers, 6-month delivery target

## Background technologies
Kafka, Redis, PostgreSQL, MongoDB, Elasticsearch, Prometheus, Grafana, ServiceNow, Jira, Slack

## Task — Phase 1: Architecture design
Design the high-level architecture for an enterprise AI chatbot system. 
For each layer below, recommend ONE primary approach and briefly explain 
why you chose it over the main alternative.

Structure your response with these sections:

1. System layers — ingestion, RAG pipeline, agent orchestration, integration, API gateway
2. Data stores — which database for each concern (vector, graph, relational, cache) and why
3. Security model — RBAC approach, auth flow, audit logging strategy
4. Key trade-offs — 3–5 decisions where reasonable engineers might disagree, 
   with your recommendation

## Output format
- One recommendation per decision — don't list all options without choosing
- Flag any assumption you made about my constraints
- Length: concise. Depth over breadth.