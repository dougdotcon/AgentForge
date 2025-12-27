# Agent-Forge

[![Licença no GitHub](https://img.shields.io/github/license/DataBassGit/AgentForge?logo=github&style=plastic&color=green)](https://github.com/DataBassGit/AgentForge/blob/dev/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/agentforge?logo=pypi&style=plastic&color=blue)](https://pypi.org/project/agentforge/)
[![Documentação](https://img.shields.io/badge/Docs-GitHub-blue?logo=github&style=plastic&color=green)](https://github.com/DataBassGit/AgentForge/tree/dev/docs)
[![Versão Python](https://img.shields.io/badge/Python-3.11-blue?style=plastic&logo=python)](https://www.python.org/)
[![Site Oficial](https://img.shields.io/badge/Homepage-agentforge.net-green?style=plastic&logo=google-chrome)](https://agentforge.net/)

![Banner do Agent-Forge](./docs/images/AF-Banner.jpg)

## Visão Geral

**Agent-Forge** é um framework de baixo código projetado para o desenvolvimento rápido, teste e iteração de agentes autônomos baseados em IA e arquiteturas cognitivas. Ele une a simplicidade do protótipo à complexidade da orquestração de multiagentes através de conceitos fundamentais: **Agentes** flexíveis, **Cogs** (Engrenagens) declarativas e um sistema integrado de **Memória**.

O framework é agnóstico quanto ao modelo de linguagem (LLM), oferecendo compatibilidade total com os principais provedores (OpenAI, Google Gemini, Anthropic Claude) e executores locais (Ollama, LMStudio). Isso permite que diferentes agentes utilizem modelos distintos dentro do mesmo fluxo de trabalho, otimizando custos e desempenho.

## Principais Recursos

*   **Cogs Declarativos**: Orchestre fluxos de trabalho complexos de multiagentes, lógica de ramificação e gerenciamento de memória usando arquivos YAML simples. Os Cogs são o método principal para construir composições de agentes reutilizáveis e escaláveis.
*   **Agentes Customizáveis**: Defina o comportamento e a função dos agentes usando modelos de prompt (templates) e configurações em YAML, permitindo ajustes rápidos sem alterar o código.
*   **Memória Integrada**: Habilite interações conscientes de contexto declarando nós de memória diretamente nos Cogs. Isso garante que os agentes mantenham estado e histórico coerentes.
*   **Gerenciamento de Personalidades (Personas)**: Configure a identidade, o tom e o estilo do agente via arquivos YAML de Persona, garantindo comportamento e caráter consistentes.
*   **Templates de Prompt Dinâmicos**: Utilize modelos adaptáveis que se ajustam automaticamente a diferentes contextos e entradas de memória.
*   **Agnóstico de LLM**: Execute diferentes agentes com diferentes LLMs simultaneamente dentro do mesmo sistema.
*   **Edição de Prompts em Tempo Real**: Modifique prompts e configurações em pleno funcionamento (on-the-fly) sem reiniciar a aplicação.

## Arquitetura

O Agent-Forge é construído em torno de três pilares:

1.  **Agentes**: As unidades atômicas de execução. Eles processam entradas, interagem com LLMs e geram saídas baseadas em sua configuração.
2.  **Cogs**: A camada de orquestração. Fluxos de trabalho definidos em YAML que encadeiam agentes, gerenciam lógica e controlam o fluxo de memória.
3.  **Memória**: A camada de contexto. Um sistema para armazenar e recuperar informações relevantes, acessível aos agentes e cogs.

## Instalação

Você pode instalar o Agent-Forge via pip:

bash
pip install agentforge


Certifique-se de ter o Python 3.11+ instalado.

## Documentação

Para guias detalhados e referências de API, visite nossa [Pasta de Documentação](https://github.com/DataBassGit/AgentForge/tree/dev/docs) ou o [site oficial](https://agentforge.net/).

## Contribuições

Contribuições são bem-vindas! Por favor, verifique as issues abertas no repositório e siga os protocolos padrão de *pull requests*.

## Licença

Este projeto está licenciado sob os termos da [Licença MIT](https://github.com/DataBassGit/AgentForge/blob/dev/LICENSE).

---

*Nota: A partir da versão atual, as ferramentas (Tools) e ações (Actions) estão obsoletas e serão substituídas por um novo sistema baseado no padrão MCP.*