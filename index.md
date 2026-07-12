# Knowledge Base Index

## llm-workflows

Patterns and practices for using LLMs to build, maintain, and query personal or team knowledge bases.

| Article | Summary | Updated |
|---------|---------|---------|
| [LLM Wiki Pattern](llm-workflows/llm-wiki-pattern.md) | LLM-maintained persistent wiki as an alternative to query-time RAG, with raw/wiki/schema architecture and ingest/query/lint operations | 2026-07-11 |

## ai-agent-harnesses

Frameworks and essays on the scaffolding (tools, state control, orchestration) around AI coding agents.

| Article | Summary | Updated |
|---------|---------|---------|
| [Awesome Harness Engineering](ai-agent-harnesses/awesome-harness-engineering.md) | Curated resource list defining harness engineering as the primary lever for agent success | 2026-07-11 |
| [Harness Design Principles](ai-agent-harnesses/harness-design-principles.md) | Five-component harness model: rules, skills, hooks, MCP, memory | 2026-07-11 |
| [oh-my-claudecode](ai-agent-harnesses/oh-my-claudecode.md) | Zero-config Claude Code plugin adding 32 specialized agents and parallel execution modes | 2026-07-11 |
| [Superpowers](ai-agent-harnesses/superpowers.md) | Skills framework enforcing brainstorm-plan-TDD-review workflow before coding | 2026-07-11 |
| [Life-Harness](ai-agent-harnesses/life-harness.md) | Training-free runtime harness adaptation improving frozen-model agent performance | 2026-07-11 |
| [Statewright](ai-agent-harnesses/statewright.md) | State-machine tool restriction per workflow phase, enforced via Rust engine and MCP gateway | 2026-07-11 |
| [Firstmate](ai-agent-harnesses/firstmate.md) | Single-agent-to-many-crewmate orchestration in isolated git worktrees | 2026-07-11 |
| [Multica](ai-agent-harnesses/multica.md) | Managed agents platform treating AI coding agents as team members | 2026-07-11 |
| [ECC](ai-agent-harnesses/ecc.md) | Cross-harness "operating system" bundling skills, memory optimization, and security scanning | 2026-07-11 |

## claude-code-ecosystem

Skills, plugins, and workflow integrations built on or around Claude Code.

| Article | Summary | Updated |
|---------|---------|---------|
| [Anthropic Agent Skills](claude-code-ecosystem/anthropics-skills.md) | Anthropic's reference spec and examples for dynamically-loaded Claude skills | 2026-07-11 |
| [Academic Research Skills](claude-code-ecosystem/academic-research-skills.md) | Multi-agent research-to-publication pipeline with non-bypassable human oversight gates | 2026-07-11 |
| [UI UX Pro Max Skill](claude-code-ecosystem/ui-ux-pro-max-skill.md) | BM25-ranked design intelligence skill covering styles, palettes, typography, and full design-system generation | 2026-07-11 |
| [article-writing-skills](claude-code-ecosystem/article-writing-skills.md) | System prompts emulating engineers' explanatory thinking patterns, not their prose style | 2026-07-11 |
| [Claude How To](claude-code-ecosystem/claude-howto.md) | Ten-module practical guide to Claude Code features and workflows | 2026-07-11 |
| [Claude Design](claude-code-ecosystem/claude-design.md) | Conversational design canvas integrated with org design systems and Claude Code | 2026-07-11 |
| [Claude Code GitHub CI Integration](claude-code-ecosystem/claude-code-github-ci-integration.md) | Two real-world setups wiring the Claude GitHub App into PR/issue workflows | 2026-07-11 |

## agent-memory-systems

Persistent memory and retrieval architectures for AI agents.

| Article | Summary | Updated |
|---------|---------|---------|
| [RightMemory](agent-memory-systems/rightmemory.md) | Deterministic, file-based tree+graph memory for agent teams, explicitly non-embedding | 2026-07-11 |
| [Open Brain (OB1)](agent-memory-systems/ob1.md) | Self-hosted unified vector memory layer shared across AI tools via pgvector and MCP | 2026-07-11 |
| [HybridRAG System](agent-memory-systems/hybridrag-system.md) | Combines vector similarity search with knowledge-graph retrieval in one RAG pipeline | 2026-07-11 |

## browser-and-mcp-tooling

Browser automation and the Model Context Protocol ecosystem.

| Article | Summary | Updated |
|---------|---------|---------|
| [Playwright](browser-and-mcp-tooling/playwright.md) | Cross-browser automation library from Microsoft, increasingly used by AI agents | 2026-07-11 |
| [Playwright MCP](browser-and-mcp-tooling/playwright-mcp.md) | MCP server exposing Playwright via accessibility snapshots instead of screenshots | 2026-07-11 |
| [Model Context Protocol Overview](browser-and-mcp-tooling/model-context-protocol-overview.md) | Open standard connecting AI apps to external data, tools, and workflows | 2026-07-11 |
| [MCP Reference Servers](browser-and-mcp-tooling/mcp-reference-servers.md) | Steering-group-maintained reference MCP server implementations | 2026-07-11 |

## deepfake-detection

Facial-manipulation datasets, detection benchmarks, and related public research communication.

| Article | Summary | Updated |
|---------|---------|---------|
| [FaceForensics++](deepfake-detection/faceforensics-plusplus.md) | ICCV 2019 facial-manipulation detection benchmark with 1.8M+ manipulated images, incl. FaceShifter subset | 2026-07-11 |
| [Justus Thies: Tutorials & Demos](deepfake-detection/justus-thies-tutorials.md) | 2016-2023 catalog tracking the arc from reenactment demos to detection research to policy briefings | 2026-07-11 |

## osint-tools

Open-source investigation and archival tooling.

| Article | Summary | Updated |
|---------|---------|---------|
| [Bellingcat Tool Suite](osint-tools/bellingcat-tools.md) | Investigative collective's tools for verifiable web archiving, geolocation, and OSINT | 2026-07-11 |

## document-processing

Tools for converting documents into structured, LLM-usable formats.

| Article | Summary | Updated |
|---------|---------|---------|
| [marker-pdf](document-processing/marker-pdf.md) | Fast PDF/DOCX/PPTX-to-Markdown/JSON converter with optional LLM-boosted accuracy | 2026-07-11 |

## research-and-training

Autonomous research systems and speculative/fringe LLM technique proposals.

| Article | Summary | Updated |
|---------|---------|---------|
| [Autoresearch](research-and-training/autoresearch.md) | Overnight autonomous LLM-training experimentation on a single GPU with narrow agent write-access | 2026-07-11 |
| [The Guanyin Protocol: Semantic Anchoring](research-and-training/guanyin-protocol-semantic-anchoring.md) | [Quality-flagged] Self-published preprint proposing a coherence-improving prompt technique | 2026-07-11 |

## model-routing

Multi-model orchestration and routing services.

| Article | Summary | Updated |
|---------|---------|---------|
| [Model Fusion (OpenRouter)](model-routing/openrouter-fusion.md) | [Thin source] OpenRouter feature for running multiple models and fusing the best answer | 2026-07-11 |
