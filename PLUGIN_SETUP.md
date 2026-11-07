# Cognigenesis v6 — installation and compatibility

The repository includes a portable `SKILL.md` instruction entry point for skill-compatible AI agents. This does not itself register a ChatGPT plugin, deploy an MCP server, or expose a model API.

## Installation
For skill-aware agents, copy or reference `SKILL.md` through the platform's supported skill installation mechanism. Skill name: `cognigenesis-v6`.

For other models, give the model access to the raw `SKILL.md` URL and request that it apply the workflow. Models that cannot retrieve files or load external instructions still require manual integration.

## Evaluation
Run the same task with identical model settings under:
1. Baseline (no skill).
2. ACOSTA v3 skill.
3. Cognigenesis v6 skill.

Score task success, factual accuracy, token usage, latency, and cost. Repeat trials and report failures. These files do not prove an improvement by themselves.

## Smoke test
Ask: "Using Cognigenesis v6, design a test for an AI receptionist with incomplete booking details. Show verification, refinement, and measurable success criteria." Check that the model distinguishes facts from assumptions and does not promise zero hallucinations.

## IP and scope
Author: Fernando Acosta. All rights reserved unless separately licensed. The original historical source remains intact; this file adds an operational integration guide.
