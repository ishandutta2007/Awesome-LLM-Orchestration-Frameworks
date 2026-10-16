# Awesome-LLM-Orchestration-Frameworks

## Top LLM Orchestration Frameworks Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agent Orchestration, Workflow Automation & Production LLM Applications*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Orchestration Frameworks**. These tools provide abstractions for chaining prompts, managing agent state, coordinating multi-agent systems, and building production-grade LLM applications with observability and evaluation built in.



**Examples** include LangChain, LlamaIndex, Haystack, Semantic Kernel, Flowise, Langflow, AutoGen, CrewAI, Dify, and DSPy (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom agent development, and transparent orchestration — ideal for AI engineers, product builders, and teams building vendor-neutral LLM applications.



Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[LangSmith](https://smith.langchain.com/)**  

  LangChain's observability, evaluation, and deployment platform — framework-agnostic with deep integration for LangGraph teams. Closed-source with SDK under MIT; enterprise self-hosting available .



- **[Dify Cloud](https://dify.ai/)**  

  Managed version of the open-source Dify platform with 142K+ stars; combines visual workflow, RAG pipeline, agent builder, and LLMOps in a single system. Modified Apache 2.0 with commercial restrictions on multi-tenant hosting .



- **[Flowise Cloud](https://flowiseai.com/)**  

  Managed offering for the Flowise drag-and-drop LLM builder; $35/month plan. Acquired by Workday in August 2025, raising long-term open-source governance questions .



- **[Braintrust](https://www.braintrust.dev/)**  

  Eval-first SaaS platform with no per-seat pricing ($249/mo flat). Raises $80M Series B led by ICONIQ; favored by teams treating prompts as CI artifacts .



- **[Vellum](https://www.vellum.ai/)**  

  LLM development platform with prompt engineering, evaluation, and deployment workflows; part of the Tier A LLMOps roster .



- **[PromptLayer](https://www.promptlayer.com/)**  

  Prompt management and observability platform for tracking prompt versions, evaluating outputs, and monitoring production LLM applications .



## Open-Source GitHub Projects



- **[LangChain](https://github.com/langchain-ai/langchain)**  

  **The most widely-adopted general-purpose LLM framework** — provides abstractions for prompts, chains, agents, tools, memory, and 700+ integrations. Best for rapid prototyping and teams new to LLM development. Note: abstraction overhead and historical breaking changes are common challenges .



- **[LangGraph](https://github.com/langchain-ai/langgraph)**  

  **Graph-based agent orchestration from the LangChain team** — models agent steps as explicit nodes and edges with persistent state across runs. The natural pick for checkpointing, human-in-the-loop pauses, and rollback/retry of specific steps. MIT licensed, pairs with Redis or Postgres for durable memory .



- **[LlamaIndex](https://github.com/run-llama/llama_index)**  

  **Data framework for connecting LLMs to structured and unstructured data** — 53K+ stars. Excels at ingestion, indexing, retrieval, and query orchestration across documents, databases, and APIs. Frequently used as the retrieval and memory layer in agentic systems. Pick this when retrieval is the primary abstraction .



- **[Haystack](https://github.com/deepset-ai/haystack)**  

  **Production-ready orchestration framework** with modular pipelines and agent workflows. Explicit control over retrieval, routing, memory, and generation. Built for scalable RAG, multimodal applications, and semantic search.



- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)**  

  **Microsoft's enterprise AI orchestration SDK** — 37K+ stars. Native C#, Python, and Java support with Azure integration, planners for automatic function orchestration, and semantic memory. Ideal for .NET enterprise environments and making existing code AI-callable. Stronger typing and IDE support than Python-only frameworks .



- **[Flowise](https://github.com/FlowiseAI/Flowise)**  

  **Lightweight drag-and-drop LLM builder** — 54.9K+ stars, Apache 2.0. Runs as a single Docker container on 1 GB RAM, deployable to a $4/month VPS. Built on LangChain.js with 10+ vector store integrations. Best for solo developers and small teams needing minimal footprint. Acquired by Workday (Aug 2025) — monitor governance .



- **[Langflow](https://github.com/langflow-ai/langflow)**  

  **Visual builder for LangChain and LangGraph pipelines** — 144K+ stars, MIT licensed. Python-based with 15+ vector store integrations, hybrid search, multi-query retrievers, and reranking strategies. LangGraph integration enables cyclic agent loops and state machines. Exports to clean Python code — targets AI engineers treating pipeline quality as the product .



- **[Dify](https://github.com/langgenius/dify)**  

  **Most-starred open-source LLM platform** — 142K+ stars. Combines orchestration, prompt management, evaluation, and deployment into one system. Multi-container Docker Compose stack requiring 4 GB RAM. Features automatic API gateway, SSO/RBAC, and best-in-class per-node debugging. Modified Apache 2.0 with commercial restrictions on multi-tenant SaaS .



- **[AutoGen](https://github.com/microsoft/autogen)**  

  **Conversational multi-agent framework** — 60K+ stars. Agents communicate via structured messages for agent-to-agent collaboration, tool usage, and conversation-based task decomposition. Microsoft origin; the AG2 fork continues community governance after Microsoft's Agent Framework merger .



- **[CrewAI](https://github.com/crewAIInc/crewAI)**  

  **Role-based multi-agent orchestration** — 57K+ stars, MIT licensed. Define agents with roles, goals, and tools; assemble into "crews" with Flows for event-driven and hierarchical control. Fastest code-first framework for getting a multi-agent workflow running, at the cost of less granular control than LangGraph .



- **[DSPy](https://github.com/stanfordnlp/dspy)**  

  **Framework for programming—not prompting—foundation models** — separates declarative modules from automatic prompt optimization. Treats prompts as learnable parameters optimized against a metric, enabling systematic improvement rather than manual prompt engineering.



- **[MetaGPT](https://github.com/FoundationAgents/MetaGPT)**  

  **"AI software company" multi-agent framework** — 70K+ stars, MIT licensed. Role-played PM, architect, and engineer agents turn a one-line requirement into specs, designs, and code along an SOP assembly line. The most-starred multi-agent orchestration project .



### Additional Strong Open-Source Options



- **[CAMEL](https://github.com/camel-ai/camel)** — Role-playing agents for studying agent society; 17.8K+ stars, Apache-2.0 .

- **[PraisonAI](https://github.com/MervinPraison/PraisonAI)** — Multi-agent workflows with self-reflection; 9.1K+ stars, MIT .

- **[OpenAgents](https://github.com/xlang-ai/OpenAgents)** — Agent networks over WebSocket, gRPC, MCP and A2A protocols; 4.2K+ stars .

- **[Agno](https://github.com/agno-agi/agno)** — Lightweight agent framework focused on composability and minimal abstractions .

- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)** — Convergence of AutoGen and Semantic Kernel; enterprise multi-agent deployments on Microsoft infrastructure, MIT licensed with Foundry hosting billed separately .

- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation with 400+ integrations and dedicated AI Agent nodes; Sustainable Use License (source-available, no resale) .



**Frameworks for building custom systems**: Combine **LangGraph** for stateful agent orchestration, **LlamaIndex** for retrieval-heavy pipelines, **CrewAI** for role-based multi-agent teams, and **Langfuse** or **LangSmith** for observability. For visual prototyping, start with **Flowise** (lightweight) or **Langflow** (Python-native, LangGraph support). For enterprise .NET, **Semantic Kernel** or **Microsoft Agent Framework** provides the strongest Azure integration .



**Key architectural insight**: The **no-code to code-first migration arc** is the dominant pattern — teams prototype in Dify, Flowise, or n8n, then migrate to LangGraph or LlamaIndex when hitting scale ceilings . The coordination model, not the framework, is the lock-in: MCP and A2A protocols (both Linux Foundation projects as of 2026) handle tool access and cross-agent coordination at the protocol level . Pick the framework that matches your team's language, control level, and durability needs — and be prepared to migrate when you outgrow it.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **License awareness**: LangChain, LangGraph, LlamaIndex, Haystack, Flowise, Langflow, AutoGen, CrewAI, DSPy, MetaGPT are MIT or Apache-2.0. Dify is modified Apache 2.0 (no multi-tenant resale). n8n is source-available under Sustainable Use License. LangSmith is closed-source. Verify terms before commercial deployment .

- LLM orchestration frameworks manage API keys and sensitive data; ensure proper secret management and access controls when self-hosting.

- Framework churn is high: Microsoft merged AutoGen and Semantic Kernel into Microsoft Agent Framework (October 2025), AutoGen forked to AG2, and Flowise was acquired by Workday (August 2025). Evaluate long-term maintenance before committing .



---



**Made for AI engineers, application developers, platform teams, and open-source enthusiasts.**  

Let's make LLM orchestration more open, composable, and vendor-neutral.
