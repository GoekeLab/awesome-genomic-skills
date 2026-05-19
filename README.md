# Awesome Genomic Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of repositories, skills, and MCP servers for working with AI coding agents (Claude Code, GitHub Copilot, Codex, Cursor, Gemini CLI, etc.) in genomics and bioinformatics.

## Contents

- [General AI Coding Agent Skill Collections](#general-ai-coding-agent-skill-collections)
- [Bioinformatics and Genomics Agent Skills](#bioinformatics-and-genomics-agent-skills)
- [MCP Servers for Life Sciences](#mcp-servers-for-life-sciences)
- [Other Resources](#other-resources)

## General AI Coding Agent Skill Collections

Popular repositories of reusable skills for AI coding agents. Each entry is useful for genomics and bioinformatics coding work; descriptions explain how.

- [superpowers](https://github.com/obra/superpowers) - Complete software development methodology and skills framework for coding agents; enforces TDD, spec-driven design, and subagent-driven development — practices that improve reproducibility and correctness in complex genomics pipelines.
- [anthropics/skills](https://github.com/anthropics/skills) - Official Anthropic reference implementation and specification for Claude agent skills; the canonical starting point for building custom skills that teach Claude how to handle bioinformatics tasks and lab workflows.
- [andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) - Single-file coding guidelines derived from Andrej Karpathy's observations on LLM pitfalls; instils simplicity, surgical changes, and goal-driven execution — critical disciplines when AI agents write or modify genomics analysis code.
- [awesome-copilot](https://github.com/github/awesome-copilot) - Community-curated instructions, agents, skills, and configurations for GitHub Copilot, including prompt templates applicable to scientific and data-analysis workflows.
- [agentskills](https://github.com/agentskills/agentskills) - Official specification and documentation for the Agent Skills standard; defines the cross-platform format used by skills in this list and on Claude Code, Copilot, Codex, Cursor, and Gemini CLI.
- [awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) - Curated list of LLM and AI agent skills, resources, and tools for customizing AI agent workflows across Claude Code, Codex, Gemini CLI, and custom agents.

## Bioinformatics and Genomics Agent Skills

Skill libraries and tool collections specifically targeting genomics, bioinformatics, and life sciences work with AI coding agents.

- [ClawBio](https://github.com/ClawBio/ClawBio) - The first bioinformatics-native AI agent skill library; provides reproducible, local-first skills for genomics tasks (variant calling, RNA-seq, population genetics) that work with Claude Code, Copilot, Codex, and other agents.
- [SciAgent-skills](https://github.com/jaechang-hits/SciAgent-Skills) - 197 open-source skills for Claude Code, Cursor, Codex, and Windsurf, covering genomics-bioinformatics, proteomics-protein engineering, structural biology, drug discovery, systems biology, biostatistics, and scientific writing; achieves 92% accuracy on BixBench-Verified-50 (+26.7 pts over Claude Code baseline). A hosted web platform, OmicsHorizon, is also available.
- [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - Currently 135 skills covering various scientific areas including genomics, but also broader scientific areas like geospatial science etc. 
- [bioSkills](https://github.com/GPTomics/bioSkills) -  SKILL.md files for bioinformatics with Claude Code, covering end-to-end pipelines like RNA-seq, variants, ChIP-seq, scRNA-seq, spatial, Hi-C, proteomics, microbiome, CRISPR, metabolomics, multi-omics, immunotherapy, outbreak analysis, and Mendelian randomization tools
- [Clair-skills](https://github.com/HKU-BAL/Clair-skills) - Agent skill for the Clair suite of variant callers (Clair3, ClairS, Clair3-RNA, Clair-Mosaic); provides intelligent model selection, command generation, and troubleshooting for germline, somatic, mosaic, and RNA-seq variant calling from long-read and short-read sequencing data.
- [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) - Ecosystem for building AI scientist systems; integrates 1,000+ machine learning models, datasets, and scientific APIs for data analysis, knowledge retrieval, and experimental design in biomedicine, with 68 pre-built agent skills covering drug discovery, precision oncology, and rare-disease diagnosis.
- [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) - Meta-aggregation of 872 skills curated from 12+ upstream repositories, including ClawBio, ToolUniverse, GPTomics bioSkills, BioOS, and others; spans clinical workflows, genomics, drug discovery, bioinformatics pipelines, and medical device regulatory frameworks. Expect overlap with the upstream repos listed separately.

## MCP Servers for Life Sciences

Model Context Protocol (MCP) servers that give AI agents direct access to bioinformatics databases, tools, and analysis pipelines.

- [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) - MCP server for spatial transcriptomics analysis through natural language; supports Scanpy, Squidpy, cell communication analysis, and spatial domain identification.
- [biomcp](https://github.com/genomoncology/biomcp) - Single MCP server able to query multiple information sources, including clinical trials, genetic data & published medical literature. 
- [gget-mcp](https://github.com/longevity-genie/gget-mcp) -  MCP server wrapping the Pachter Lab [gget](https://github.com/pachterlab/gget) bioinformatics toolkit. Exposes 13 tools covering gene search and metadata (Ensembl), sequence retrieval, BLAST/BLAT/MUSCLE alignment, expression data (ARCHS4), functional enrichment (Enrichr), protein structure (PDB, AlphaFold), cancer mutations (COSMIC), and single-cell queries (CellxGene).
- [Seqera MCP](https://docs.seqera.io/platform-cloud/seqera-mcp/overview) - Hosted MCP server from Seqera Labs (the developers of nextflow) exposing the Seqera Platform (workflow launch/management), Wave (container provisioning), nf-core modules, and SRA/ENA/GEO retrieval. 
- [knowledgebase-mcp](https://github.com/biocontext-ai/knowledgebase-mcp) - BioContextAI Knowledgebase MCP server, included in the BioContextAI registry (below), one of the most comprehensive single MCP packages (wraps STRINGDb, Open Targets, Reactome, UniProt, HPA, KEGG, AlphaFold, Ensembl, ClinicalTrials.gov, bioRxiv, etc.)

Existing registries and lists of MCP servers: 
- [BioContextAI Registry](https://github.com/biocontext-ai/registry/) - Community-curated catalogue of biomedical MCP servers, with submission criteria requiring biomedical focus, free academic access, OSI-approved open-source licenses, and MCP specification compliance. Ships a [cookiecutter template](https://github.com/biocontext-ai/mcp-server-cookiecutter) for new servers and follows Schema.org ontologies for metadata.[A community hub for agentic biomedical systems](https://www.nature.com/articles/s41587-025-02900-9)
- [MCPmed](https://github.com/MCPmed) -  Reference MCP implementations (GEO, STRING, UCSC Cell Browser, PLSDB) plus a cookiecutter template and HTML "breadcrumbs" discovery mechanism for transitioning legacy services to MCP. Published as a call paper in Briefings in Bioinformatics. [MCPmed: a call for Model Context Protocol-enabled bioinformatics web services for LLM-driven discovery](https://academic.oup.com/bib/article/27/1/bbag076/8495038)
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers#bio) - General-purpose MCP server list with a Biology, Medicine, and Bioinformatics subsection.

MCP related tools: 
- [BioinfoMCP](https://github.com/florensiawidjaja/BioinfoMCP) - Not strictly an MCP, a converter that auto-generates MCP servers from existing tool documentation, plus a benchmark of the converted tools. Preprint available [here](https://arxiv.org/abs/2510.02139)

## Other Resources

Benchmarks, evaluations, and other helpful repositories at the intersection of AI and genomics/bioinformatics.

- [BixBench](https://github.com/Future-House/BixBench) - Comprehensive benchmark for LLM-based agents on real-world computational biology tasks; tests agents' ability to explore biological datasets, perform multi-step analyses, and interpret results — useful for evaluating which agents and skills perform best on genomics work.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
