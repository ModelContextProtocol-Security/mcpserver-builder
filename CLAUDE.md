# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

**mcpserver-builder** is an expert-advisor / tutor system for *building* secure, well-architected Model Context Protocol (MCP) servers. Its role in the MCP Security ecosystem is the **"fix and build"** step: where `mcpserver-audit` finds vulnerabilities, this repo teaches users to write secure code and make sound architectural decisions in the first place.

Like its sibling repos, it is designed as an **expert guidance system**, not a code-generation product — a domain expert that teaches the development mindset (architecture, security-by-design, protocol compliance, testing) while offering enough hands-on scaffolding to be immediately useful.

## Current state

This repository is **early-stage: a vision/spec, not yet an implementation.** As of this writing it contains only `README.md` (a detailed statement of intent), `LICENSE`, and `CODE_OF_CONDUCT.md` — there are **no prompts, checks, templates, code, or build/test system yet**. Do not look for a build/lint/test workflow.

When building this out, follow the pattern established by the more mature sibling `mcpserver-audit`: a prompt-driven knowledge system (conversational tutoring prompts, modular guidance documents, templates), with content in Markdown rather than a traditional application. The README describes the intended capability areas — development education, practical scaffolding, and expert orchestration/tool recommendations — which is the natural structure for that content.

## Ecosystem role

Part of the **ModelContextProtocol-Security** three-stage workflow:

1. **mcpserver-audit** — finds vulnerabilities in existing servers
2. **mcpserver-builder** (this repo) — teaches building/fixing secure servers
3. **mcpserver-operator** — deploys and operates them securely

It also draws on `mcpserver-finder` (discoverability/quality), `vulnerability-db` (known vulnerabilities to prevent), and `audit-db` (community audit experience). Keep terminology, the expert-tutor voice, and security framing consistent with these siblings — especially `mcpserver-audit`, whose structure this repo should mirror as it grows.

## Contributing

`main` is protected and requires a code-owner-approved pull request. Changes are documentation/knowledge contributions; value is measured by how effectively they teach secure MCP server construction, not by passing tests.
