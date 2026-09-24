# Awesome-AI-Guardrails

## Top AI Guardrails Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Guardrails, Policy Rails, Input/Output Validation, Prompt Injection Defense, Safe Agent Behavior & Runtime AI Controls*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Guardrails**. These systems constrain model and agent behavior—validating inputs and outputs, blocking jailbreaks and injections, enforcing topic and safety policies, and reducing harmful or off-policy responses at runtime.



**Examples** include Guardrails AI, Lakera, NVIDIA NeMo Guardrails, Arthur Shield, Protect AI, HiddenLayer, Fiddler AI, Aporia, Patronus AI, and Credo AI (the category leaders and adjacent platforms).



**Open-source emphasis**: Guardrails are one of the strongest open areas in AI safety. **NeMo Guardrails**, **Guardrails AI**, **LLM Guard**, **LlamaFirewall**, and related projects provide production-usable controls. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Guardrails AI](https://www.guardrailsai.com/)**  

  Framework and platform for structured validation, corrective actions, and safety checks around LLM outputs and application flows.



- **[NVIDIA NeMo Guardrails](https://www.nvidia.com/en-us/ai-data-science/)**  

  Programmable guardrails for input, dialog, retrieval, execution, and output rails—widely used open core with enterprise support paths.



- **[Lakera](https://www.lakera.ai/)**  

  Runtime LLM security focused on prompt injection and application-level guardrails for production AI apps.



- **[Arthur Shield, Protect AI, HiddenLayer](https://www.arthur.ai/)**  

  Platforms offering runtime controls, model/application security, and policy enforcement for AI systems.



- **[Fiddler AI, Aporia, Patronus AI, Credo AI](https://www.fiddler.ai/)**  

  Observability, evaluation, and governance platforms that include guardrail, monitoring, and policy capabilities for responsible AI.



- **[Other commercial AI guardrail platforms](https://www.guardrailsai.com/)**  

  Additional solutions for content filtering, agent safety, and enterprise AI risk controls.



## Open-Source GitHub Projects



- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Leading open-source programmable guardrails framework—Colang-based policies for dialog control, topical rails, and safety constraints around LLMs and agents.



- **[Guardrails AI (open library)](https://github.com/guardrails-ai/guardrails)**  

  Open framework for declarative validation of LLM outputs (and inputs), with retries, fixes, and structured safety/quality checks.



- **[LLM Guard](https://github.com/protectai/llm-guard)**  

  Open toolkit for scanning and sanitizing LLM inputs and outputs—prompt injection, PII, toxicity, secrets, and related filters.



- **[LlamaFirewall (Meta)](https://ai.meta.com/research/publications/llamafirewall-an-open-source-guardrail-system-for-building-secure-ai-agents/)**  

  Open guardrail system for agents: jailbreak detection, alignment checks on reasoning, and code safety scanning as a final defense layer.



- **[AISafeGuard & safety proxies](https://github.com/akshaymagapu/aisafeguard)**  

  Open safety layers with injection/jailbreak detection, PII redaction, toxicity filtering, and OpenAI-compatible proxy modes.



- **[Agent / MCP guard projects](https://github.com/search?q=AI+agent+guardrail+OR+MCP+security+open+source)**  

  Open controls that inspect agent tool calls and egress for unsafe actions and injection-driven behavior.



- **[Promptfoo & evaluation-driven rails](https://github.com/promptfoo/promptfoo)**  

  Open evaluation and red-teaming tools used to design and regress-test guardrail policies before and after deployment.



- **[Community moderation & injection detectors](https://github.com/search?q=prompt+injection+detection+OR+toxicity+classifier+open+source)**  

  Classifiers and rule libraries that plug into custom guardrail pipelines.



### Additional Strong Open-Source Options



- **Programmable rails**: NeMo Guardrails for policy-driven dialog and topic control.

- **Structured validation**: Guardrails AI library for output schemas and corrective flows.

- **Scan-and-filter**: LLM Guard and AISafeGuard for proxy-style input/output protection.

- **Agent defense**: LlamaFirewall and MCP/agent guards for tool-use safety.

- **Composable stacks**: Open proxy + NeMo/Guardrails config + logging for a full self-hosted guardrail layer.

- Commercial platforms still lead in managed policy packs, multi-app coverage, and enterprise governance UX.



**Frameworks for building custom systems**:  

**NeMo Guardrails**, **Guardrails AI**, **LLM Guard**, and **LlamaFirewall** are the primary open building blocks.  

Combine them with red-team suites (Promptfoo, garak) to validate effectiveness.  

Commercial platforms (Lakera, Arthur, Protect AI, HiddenLayer, Fiddler, Aporia, Patronus, Credo, etc.) add scale, threat updates, and organizational policy management.  

Many teams deploy open guardrails in front of self-hosted or API models and use commercial AI safety products for broader governance. Fully open guardrail stacks are production-viable when you own policy design and monitoring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Guardrails reduce risk but do not eliminate prompt injection, jailbreaks, or harmful outputs. No single layer is complete; combine with least-privilege tools, human approval for high-impact actions, and continuous evaluation.

- Open-source tools offer transparency and control but require ongoing tuning. Commercial platforms shift detector updates and support to the vendor. Validate effectiveness against your threat model before production use.



---



**Made for AI engineers, safety teams, and builders shipping constrained LLM and agent applications.**  

Let's expand open AI guardrails while recognizing the coverage and operational maturity that leading commercial platforms deliver.
