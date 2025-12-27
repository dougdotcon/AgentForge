# Agent-Forge

[![GitHub - License](https://img.shields.io/github/license/DataBassGit/AgentForge?logo=github&style=plastic&color=green)](https://github.com/DataBassGit/AgentForge/blob/dev/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/agentforge?logo=pypi&style=plastic&color=blue)](https://pypi.org/project/agentforge/)
[![Documentation](https://img.shields.io/badge/Docs-GitHub-blue?logo=github&style=plastic&color=green)](https://github.com/DataBassGit/AgentForge/tree/dev/docs)
[![Python Version](https://img.shields.io/badge/Python-3.11-blue?style=plastic&logo=python)](https://www.python.org/)
[![Homepage](https://img.shields.io/badge/Homepage-agentforge.net-green?style=plastic&logo=google-chrome)](https://agentforge.net/)

![Agent-Forge Banner](./docs/images/AF-Banner.jpg)

## Overview

**Agent-Forge** is a low-code framework designed for the rapid development, testing, and iteration of AI-powered autonomous agents and cognitive architectures. It bridges the gap between simple prototyping and complex multi-agent orchestration through core concepts like flexible **Agents**, declarative **Cogs**, and integrated **Memory** systems.

The framework is fully model-agnostic, offering seamless compatibility with major LLM providers (OpenAI, Google's Gemini, Anthropic's Claude) and local model runners (Ollama, LMStudio). This allows developers to assign different models to different agents within the same workflow, optimizing for cost and performance as needed.

## Key Features

*   **Declarative Cogs**: Orchestrate complex multi-agent workflows, branching logic, and memory management using simple YAML files. Cogs serve as the primary method for building reusable and scalable agent compositions.
*   **Customizable Agents**: Define agent behaviors and roles using YAML prompt templates and configuration files, allowing for rapid adjustments without code changes.
*   **Integrated Memory**: Enable context-aware interactions by declaring memory nodes directly within Cogs. This ensures agents maintain coherent state and history across tasks.
*   **Persona Management**: Configure agent identity, tone, and style via dedicated Persona YAML files, ensuring consistent behavior and character.
*   **Dynamic Prompt Templates**: Utilize adaptable templates that automatically adjust to various contexts and memory inputs.
*   **LLM Agnostic**: Run different agents with different LLMs simultaneously within the same system.
*   **Live Prompt Editing**: Modify prompts and configurations on the fly without restarting the application.

## Architecture

Agent-Forge is built around three pillars:

1.  **Agents**: The atomic units of execution. They process inputs, interact with LLMs, and generate outputs based on their configuration.
2.  **Cogs**: The orchestration layer. YAML-defined workflows that chain agents, manage logic, and handle memory flow.
3.  **Memory**: The context layer. A system for storing and retrieving relevant information, accessible to agents and cogs.

## Installation

You can install Agent-Forge via pip:

bash
pip install agentforge


Ensure you have Python 3.11+ installed.

## Documentation

For detailed guides and API references, visit our [Documentation folder](https://github.com/DataBassGit/AgentForge/tree/dev/docs) or the [official homepage](https://agentforge.net/).

## Contributing

Contributions are welcome! Please check the repository for open issues and follow standard pull request protocols.

## License

This project is licensed under the terms of the [MIT License](https://github.com/DataBassGit/AgentForge/blob/dev/LICENSE).

---

*Note: As of the current release, Actions and Tools are deprecated and will be superseded by a new system based on the MCP standard.*