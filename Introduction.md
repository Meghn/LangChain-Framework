# Introduction

## Overview

LangChain is an opensource development framework for LLM applications

There are Python and JavaScript (TypeScript) packages

They're focused on composition and modularity
Key value adds:
 1. Modular components: lots of individual components that can be used in conjunction with each other
 2. Use cases: Common ways to combine the modular components into more end-to-end applications

## Common Components of LangChain

- **Models**
    - LLMs: 20+ integrations
    - Chat Models
    - Text Embedding Models: 10+ integrations
- **Prompts**
    - Prompt Templates
    - Output Parsers: 5+ implementations
        - Retry/fixing logic
    - Example Selectore: 5+ implementations
- **Indexes** _(Ways of Ingesting data)_
    - Document Loaders: 50+ implementations
    - Text Splitters: 10+ implementations
    - Vector Stores: 10+ integrations
    - Retrievers: 5+ integrations/implementations
- **Chains**
    - Prompt + LLM + Output parsing
    - Can be used as building blocks for longer chains
    - More application specific chains: 20+ types
- **Agents**
    - Agent Types: 5+ types
        - Algorithms for getting LLMs to use tools
    - Agent Toolkits: 10+ implementations
        - Agents armed with specific tools for a specific application
