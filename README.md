# Awesome Genomic Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of repositories, skills, and MCP servers for working with AI coding agents (Claude Code, GitHub Copilot, Codex, Cursor, Gemini CLI, etc.) in genomics and bioinformatics.

## Contents

- [General AI Coding Agent Skill Collections](#general-ai-coding-agent-skill-collections)
- [Bioinformatics and Genomics Agent Skills](#bioinformatics-and-genomics-agent-skills)
- [MCP Servers for Life Sciences](#mcp-servers-for-life-sciences)
- [MCP Server Collections](#mcp-server-collections)
- [Other Resources](#other-resources)

## General AI Coding Agent Skill Collections

Popular repositories of reusable skills for AI coding agents. Each entry is useful for genomics and bioinformatics coding work; descriptions explain how.

- [superpowers](https://github.com/obra/superpowers) - Complete software development methodology and skills framework for coding agents; enforces TDD, spec-driven design, and subagent-driven development — practices that improve reproducibility and correctness in complex genomics pipelines.
- [anthropics/skills](https://github.com/anthropics/skills) - Official Anthropic reference implementation and specification for Claude agent skills; the canonical starting point for building custom skills that teach Claude how to handle bioinformatics tasks and lab workflows.
- [andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) - Single-file coding guidelines derived from Andrej Karpathy's observations on LLM pitfalls; instils simplicity, surgical changes, and goal-driven execution — critical disciplines when AI agents write or modify genomics analysis code.
- [awesome-copilot](https://github.com/github/awesome-copilot) - Community-curated instructions, agents, skills, and configurations for GitHub Copilot, including prompt templates applicable to scientific and data-analysis workflows.
- [agentskills](https://github.com/agentskills/agentskills) - Official specification and documentation for the Agent Skills standard; defines the cross-platform format used by skills in this list and on Claude Code, Copilot, Codex, Cursor, and Gemini CLI.
- [context-mode](https://github.com/mksglu/context-mode) - Context window optimization for AI coding agents; sandboxes verbose tool output — especially valuable in genomics where alignment reports, VCF logs, and quality control summaries can quickly exhaust context limits.
- [awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) - Curated list of LLM and AI agent skills, resources, and tools for customizing AI agent workflows across Claude Code, Codex, Gemini CLI, and custom agents.

## Bioinformatics and Genomics Agent Skills

Skill libraries and tool collections specifically targeting genomics, bioinformatics, and life sciences work with AI coding agents.

- [ClawBio](https://github.com/ClawBio/ClawBio) - The first bioinformatics-native AI agent skill library; provides reproducible, local-first skills for genomics tasks (variant calling, RNA-seq, population genetics) that work with Claude Code, Copilot, Codex, and other agents.
- [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) - Ecosystem for building AI scientist systems; integrates 1,000+ machine learning models, datasets, and scientific APIs for data analysis, knowledge retrieval, and experimental design in biomedicine, with 68 pre-built agent skills covering drug discovery, precision oncology, and rare-disease diagnosis.

## MCP Servers for Life Sciences

Model Context Protocol (MCP) servers that give AI coding agents direct access to bioinformatics databases, tools, and analysis pipelines.

- [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) - MCP server for spatial transcriptomics analysis through natural language; supports Scanpy, Squidpy, cell communication analysis, and spatial domain identification.

## MCP Server Collections

Curated collections of MCP servers to help you find additional servers relevant to your research domain.

- [awesome-mcp-servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers) - Comprehensive curated list of Model Context Protocol servers spanning all domains.
- [awesome-mcp-servers (wong2)](https://github.com/wong2/awesome-mcp-servers) - Community-maintained curated list of MCP servers.

## Other Resources

Benchmarks, evaluations, and other helpful repositories at the intersection of AI and genomics/bioinformatics.

- [BixBench](https://github.com/Future-House/BixBench) - Comprehensive benchmark for LLM-based agents on real-world computational biology tasks; tests agents' ability to explore biological datasets, perform multi-step analyses, and interpret results — useful for evaluating which agents and skills perform best on genomics work.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
