# Awesome Genomic Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of repositories, skills, and MCP servers for working with AI coding agents (Claude Code, GitHub Copilot, Codex, Cursor, Gemini CLI, etc.) in genomics and bioinformatics.

AI coding agents can supercharge genomics and bioinformatics workflows — from writing analysis pipelines to querying databases. This list collects the best resources for getting the most out of these tools in a life-sciences context.

## Contents

- [General AI Coding Agent Skill Collections](#general-ai-coding-agent-skill-collections)
- [Bioinformatics and Genomics Agent Skills](#bioinformatics-and-genomics-agent-skills)
- [MCP Servers for Life Sciences](#mcp-servers-for-life-sciences)
- [Popular Bioinformatics Libraries and Frameworks](#popular-bioinformatics-libraries-and-frameworks)
- [Curated Bioinformatics Awesome Lists](#curated-bioinformatics-awesome-lists)
- [MCP Server Collections](#mcp-server-collections)

## General AI Coding Agent Skill Collections

Popular repositories of reusable skills for AI coding agents that are useful for any coding work, including bioinformatics analysis and pipeline development. Skills are small markdown files that teach AI agents conventions, best practices, and domain knowledge.

- [context-mode](https://github.com/mksglu/context-mode) - Context window optimization for AI coding agents; sandboxes tool output to significantly reduce token usage. Works across many platforms including Claude Code, Copilot, Codex, and Cursor.
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - Structured cybersecurity skills for AI agents mapped to MITRE ATT&CK, NIST CSF, and related frameworks. Compatible with Claude Code, GitHub Copilot, Codex CLI, Cursor, and Gemini CLI.
- [cc-sdd](https://github.com/gotalab/cc-sdd) - Spec-driven development harness with agent skills; turns approved specs into long-running autonomous implementation for Claude Code, Codex, Cursor, and others.
- [gsap-skills](https://github.com/greensock/gsap-skills) - Official AI skills for GSAP demonstrating the canonical format for teaching coding agents library-specific best practices. A reference example for authoring your own skills.
- [agent-skills](https://github.com/tech-leads-club/agent-skills) - Secure, validated skill registry for professional AI coding agents; extend Cursor, Claude Code, Copilot, and more with validated skills.
- [cc-skills-golang](https://github.com/samber/cc-skills-golang) - Collection of Golang agentic skills for Claude Code, Cursor, Copilot, and others. Golang is widely used in bioinformatics tooling.
- [awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) - Curated list of LLM and AI agent skills, resources, and tools for customizing AI agent workflows. Works with Claude Code, Codex, Gemini CLI, and custom agents.
- [skills-manager](https://github.com/xingkongliang/skills-manager) - Lightweight desktop application to manage, sync, and organize AI agent skills across 15+ coding tools.
- [skillkit](https://github.com/rohitg00/skillkit) - Install, translate, and share agent skills across Claude Code, Cursor, Codex, Copilot, and 40+ other tools from a single command-line interface.
- [agent-skill-creator](https://github.com/FrancyJGLisboa/agent-skill-creator) - Turn any workflow into reusable AI agent skills that install across 14+ tools using a single `SKILL.md` file.
- [kodustech/awesome-agent-skills](https://github.com/kodustech/awesome-agent-skills) - Curated list of agent skills for AI coding agents including Claude Code, Codex, and Cursor.

## Bioinformatics and Genomics Agent Skills

Skill files and knowledge bases specifically targeting bioinformatics, genomics, and life sciences work with AI coding agents.

- [encode-toolkit](https://github.com/ammawla/encode-toolkit) - Claude Plugin and MCP server for the ENCODE Project; provides AI agents with skills to search, download, track, and analyze functional genomics experiments including ChIP-seq, ATAC-seq, and RNA-seq data.

## MCP Servers for Life Sciences

Model Context Protocol (MCP) servers that give AI coding agents direct access to bioinformatics databases, tools, and analysis pipelines.

- [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) - MCP server for spatial transcriptomics analysis through natural language; supports Scanpy, Squidpy, cell communication tools, and spatial domain identification.
- [opentargets-mcp](https://github.com/nickzren/opentargets-mcp) - MCP server for Open Targets data; gives AI agents access to drug targets, disease–gene associations, and genomic evidence.
- [precision-medicine-mcp](https://github.com/lynnlangit/precision-medicine-mcp) - Production multiomics/genomics and spatial transcriptomics MCP platform with worked examples for cancer and cardiovascular research.
- [encode-toolkit](https://github.com/ammawla/encode-toolkit) - MCP server for the full ENCODE Project genomic data portal — search experiments, download files, and analyze functional genomics data.
- [genepattern-mcp](https://github.com/genepattern/genepattern-mcp) - MCP server enabling AI assistants (Claude, Cursor, Copilot) to run GenePattern bioinformatics modules, manage cloud jobs, and access genomic data through natural language.

## Popular Bioinformatics Libraries and Frameworks

Well-established bioinformatics libraries and workflow frameworks that coding agents should be aware of when working with genomic data.

- [biopython](https://github.com/biopython/biopython) - The standard Python library for bioinformatics; covers sequence analysis, structure, phylogenetics, and database interfaces for NCBI, UniProt, and others.
- [scanpy](https://github.com/scverse/scanpy) - Single-cell analysis in Python scaling to >100M cells; integrates with the scverse ecosystem of single-cell tools.
- [nf-core/rnaseq](https://github.com/nf-core/rnaseq) - Community-maintained, gold-standard RNA-seq analysis Nextflow pipeline using STAR, RSEM, HISAT2, or Salmon with extensive quality control.
- [nf-core/sarek](https://github.com/nf-core/sarek) - Nextflow pipeline for detecting germline and somatic variants from whole-genome or targeted sequencing data using GATK4 best practices.
- [nf-core/scrnaseq](https://github.com/nf-core/scrnaseq) - Single-cell RNA-seq Nextflow pipeline supporting 10x Genomics, DropSeq, and SmartSeq protocols with multiple aligner options.

## Curated Bioinformatics Awesome Lists

Other curated lists covering bioinformatics tools, workflows, and resources that complement this list.

- [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics) - Comprehensive curated list of bioinformatics software and libraries; a well-maintained starting point for any bioinformatics project.
- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell) - Community-curated list of software packages and data resources for single-cell analysis including scRNA-seq, ATAC-seq, and spatial transcriptomics.
- [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) - Curated list of AI tools, papers, datasets, and frameworks that accelerate scientific discovery across physics, chemistry, and biology.
- [awesome-cheminformatics](https://github.com/hsiaoyi0504/awesome-cheminformatics) - Curated list of cheminformatics libraries and software; relevant for drug discovery and molecular bioinformatics applications.
- [awesome-bioinformatics-benchmarks](https://github.com/j-andrews7/awesome-bioinformatics-benchmarks) - Curated and summarized list of bioinformatics benchmarking papers and resources for method evaluation.

## MCP Server Collections

Curated collections of MCP servers to help you find additional servers relevant to your research domain.

- [awesome-mcp-servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers) - Comprehensive curated list of Model Context Protocol servers spanning all domains.
- [awesome-mcp-servers (wong2)](https://github.com/wong2/awesome-mcp-servers) - Community-maintained curated list of MCP servers.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
