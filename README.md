<div align="center">

<!-- Two variants because the mark is a single colour: the white one vanishes
     on GitHub's light theme and the black one on dark. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img src="assets/logo-light.svg" alt="KageX" width="96">
</picture>

# KageX

**Offensive AI security: red teaming labs, free challenges, and open-source tools.**

We build the training and the tooling for testing AI systems the way an attacker would, before someone else does.

[![Website](https://img.shields.io/badge/kagex.ai-visit-fb2c36?style=flat-square)](https://kagex.ai)
[![Mirage](https://img.shields.io/github/stars/kagexai/mirage?style=flat-square&label=Mirage&color=fb2c36)](https://github.com/kagexai/mirage)
[![AgentBreaker](https://img.shields.io/github/stars/kagexai/agentbreaker?style=flat-square&label=AgentBreaker&color=fb2c36)](https://github.com/kagexai/agentbreaker)
[![License](https://img.shields.io/badge/license-MIT-fb2c36?style=flat-square)](https://github.com/kagexai/mirage/blob/main/LICENSE)

[kagex.ai](https://kagex.ai) · [Blog](https://kagex.ai/blog) · [Careers](https://kagex.ai/careers)

</div>

---

## What we build

| | | |
|---|---|---|
| **[FreakLabs](https://kagex.ai/products/freaklab)** | AI security training | A structured red teaming course with 20 hands-on labs where you attack real AI systems, ending in a verifiable certificate. Opening levels and labs are free. |
| **[SentinelGoat](https://kagex.ai/products/sentinelgoat)** | Free AI security CTF | Progressive prompt injection challenges across text, documents, images and audio. Six levels, three difficulty modes, free to play. |
| **[AgentBreaker](https://github.com/kagexai/agentbreaker)** | Open source | An AI security testing engine that surfaces prompt leaks, guardrail bypasses and unsafe agent behaviour. Point it at your system and see what breaks. |
| **[Mirage](https://github.com/kagexai/mirage)** | Open source | A browser extension that red-teams your AI like a real attacker: an autonomous recon, plan, test, judge and iterate agent with deterministic scoring. |

## Why deterministic scoring

An attack counts when it produces a verifiable marker, not when a model says it went well.

A model asked to grade its own success has an incentive structure, and 2026 has repeatedly shown what models do with one. Our tooling scores results deterministically so a finding you can act on is distinguishable from a transcript that reads convincingly.

## What we test for

Prompt injection, both direct and indirect. Jailbreaks and guardrail bypass. Data and system prompt leakage. Multi-modal payloads carried in documents, images and audio. Tool abuse and excessive agency in AI agents. Insecure output handling.

The labs and tooling map to the [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) and [MITRE ATLAS](https://atlas.mitre.org/).

## Start here

- **Never done this before?** [Play the free challenges](https://kagex.ai/products/sentinelgoat) and see how a real attacker thinks.
- **Want the discipline behind the tricks?** [Work through the labs](https://kagex.ai/products/freaklab).
- **Testing your own system?** Start with [AgentBreaker](https://github.com/kagexai/agentbreaker), or [Mirage](https://github.com/kagexai/mirage) if the target lives in a browser.
- **Want the theory first?** [What AI red teaming actually is](https://kagex.ai/blog/what-is-ai-red-teaming).

## Contributing

Offensive AI security is a young discipline. The techniques are unsettled, the tooling is immature, ours included, and we would much rather be corrected in public than confident in private.

Issues and pull requests are welcome on any of our open-source repositories, all MIT licensed. If you break one of our tools, tell us how.

## Responsible use

Our tools send adversarial input to whatever you point them at. **Only run them against systems you own or are explicitly authorised to test.**

---

<div align="center">

Built by operators, for operators.

</div>
