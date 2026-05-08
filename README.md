# Hi, I'm Xing

I'm building **Sonechka**, a proprietary AI agent runtime and service engine for reliable, inspectable, workflow-specific automation.

I'm also building **Culprit**, the first commercial product powered by this direction: a private-deployment AI RCA Workbench for Jira-based engineering teams.

Culprit turns Jira tickets, logs, attachments, domain-specific skills, and historical engineering knowledge into evidence-based RCA reports, expert diagnostic conversations, reviewed knowledge cards, and reusable incident knowledge.

The RCA workflow has already been validated in a real company environment through a company-specific **Python + Hermes** implementation. That internal RCAgent system can analyze Jira issues, inspect logs and evidence, answer expert diagnostic questions, and maintain a reviewed RCA knowledge base.

The current Python + Hermes version works best for early custom delivery and founder-led pilots.

I am now independently rebuilding and productizing the workflow in **Rust** as Culprit, while continuing to build **Sonechka** as a general-purpose agent runtime that can replace the earlier Hermes/OpenClaw-style execution layer and power multiple AI services beyond Culprit.

Website: https://culprit.novax.fun  
Contact: wxinxings@gmail.com

[](https://twitter.com/EthanWang999) [](https://www.linkedin.com/in/ethanwang999) [](https://github.com/ArtWalker)

---

## Sonechka

**Sonechka** is my self-developed AI agent runtime and service engine.

It is not a thin LLM wrapper.

It is also not just a rewrite of Hermes or OpenClaw.

Sonechka is being built to replace the earlier Hermes/OpenClaw-style execution layer with a more reliable, inspectable, customizable, and commercially deployable runtime.

Culprit is the first commercial product being built around this direction, but Sonechka is not limited to Culprit.

Sonechka is designed to power multiple kinds of AI workflow services, including:

- AI RCA and incident intelligence
- personal agents
- coding agents
- workflow automation
- tool orchestration
- evidence-based analysis
- private-deployment enterprise agents
- TUI / Telegram / CLI / future UI interaction surfaces

Its core principles are:

- evidence before conclusion
- review before irreversible action
- capability boundaries before tool use
- workflow recipes before one-off prompts
- auditability before autonomy
- runtime before model dependency

Sonechka is designed for:

- reliable long-running task execution
- evidence-first reasoning
- retrieval and evidence handling
- memory and continuity
- workflow automation
- auditability and traceability
- visible tool-use boundaries
- human review gates
- multi-provider model support
- multi-service runtime reuse

Culprit is the first vertical product.

Sonechka is the reusable runtime layer.

---

## Culprit

Engineering teams often investigate the same kinds of issues again and again.

The useful knowledge already exists, but it is scattered across:

- Jira issue summaries
- descriptions and comments
- logs and attachments
- historical RCA notes
- domain-specific debugging methods
- expert experience
- repeated failure patterns
- reviewed but hard-to-search knowledge

**Culprit turns this scattered context into an AI-powered RCA workbench.**

It helps teams:

- analyze Jira tickets
- inspect logs and evidence
- generate structured RCA reports
- identify symptoms and probable root causes
- surface key evidence and failure timelines
- run expert diagnostic conversations
- build company-specific skill packs
- promote reviewed findings into knowledge cards
- search and reuse historical RCA knowledge

The goal is simple:

**help engineering teams investigate issues faster, preserve expert knowledge, reduce repeated debugging work, and make RCA more evidence-based, reviewable, and reusable.**

Culprit is the first commercial vertical product built from the Sonechka direction, but the underlying runtime is designed to support many other agent-powered services.

---

## Validated Workflow

Culprit is not just a concept.

The underlying RCA workflow has already been validated in a real company environment through a company-specific Python + Hermes implementation.

That internal RCAgent system includes:

- Jira issue analysis
- automatic log and evidence retrieval
- domain-specific skill matching
- structured RCA generation
- confidence scoring
- key evidence extraction
- failure timeline reconstruction
- expert diagnostic chat
- reviewed knowledge-card generation
- knowledge-base search
- operational dashboard and skill management

The current working delivery path uses:

- Python
- Hermes as the agent engine
- company-specific Jira workflow customization
- self-hosted long-context Qwen model
- domain-specific RCA skill packs
- log and evidence analysis
- structured RCA report generation
- reviewed knowledge base

I am now rebuilding this validated workflow independently in Rust to turn it into a reusable commercial product.

The Python + Hermes version validates and delivers the workflow today.

The Rust version is the independent productization path.

---

## Company-Specific Skill Packs

Culprit is not a generic Jira summarizer.

The system becomes valuable when it understands a team's real modules, logs, failure patterns, debugging habits, and RCA vocabulary.

A company-specific RCA skill pack can include:

- Jira field mapping
- issue type and severity mapping
- module and subsystem taxonomy
- title and log pattern matching
- known failure modes
- debugging checklists
- evidence fetching rules
- RCA output structure
- review criteria
- knowledge-card taxonomy
- expert diagnostic playbooks
- private deployment requirements

Customers can provide their own Jira data, logs, RCA documents, SOPs, and domain materials, or work with me through a paid customization engagement to build a company-specific RCA skill pack.

This is where the product becomes useful:

**AI RCA only works well when it understands the team's real systems, logs, and failure patterns.**

---

## Rust Productization

I am rebuilding Culprit in Rust to make the system more reliable, deployable, and commercially scalable.

The Rust productization effort focuses on:

- private deployment
- Jira integration
- evidence fetching
- reviewable RCA output
- knowledge-card promotion
- configurable storage
- async worker topology
- product-kernel contracts
- future Sonechka runtime integration

The current Python + Hermes version is the early delivery engine.

The Rust version is the long-term product foundation.

---

## Model & Provider Layer

Sonechka is designed to be model-provider agnostic.

Current provider support includes:

- OpenAI / Codex login OAuth path
- DeepSeek API
- extensible provider adapters for future model backends

The current Python + Hermes delivery version can also work with company-specific model setups, including self-hosted long-context models when needed.

The core value is not locked inside a single LLM API.

The value is in the runtime and workflow layer:

- workflow execution
- evidence handling
- context continuity
- review boundaries
- tool orchestration
- task auditability
- domain-specific automation recipes
- company-specific RCA skill packs

---

## Commercial Pilots & Custom Deployments

I am looking for:

- engineering teams using Jira
- SRE / DevOps / platform engineering teams
- support engineering teams
- embedded / automotive / hardware-software teams
- CTOs and engineering managers
- teams with repeated incidents and hard-to-reuse RCA knowledge
- companies that need private deployment
- technical partners
- angel investors and pre-seed investors interested in AI agents for engineering operations

Available for:

- paid RCA diagnostics
- founder-led paid pilots
- custom Jira RCA workflow deployments
- company-specific RCA skill pack development
- incident knowledge-base automation
- evidence-based RCA analysis
- private deployment pilots
- internal AI agent systems
- technical partnerships
- investment conversations

If your team spends too much time reading Jira incidents, investigating repeated failures, writing RCA reports, or trying to preserve expert knowledge, I would like to talk.

---

## Tech

Rust · Python · TypeScript · LLMs · AI Agents · Jira · RCA · Incident Analysis · Retrieval · Evidence Handling · Hermes · Sonechka · Automation · TUI · Telegram Bots · Developer Tools · Workflow Intelligence

---

Building AI systems that turn engineering incidents into clear, reviewable, reusable knowledge.
