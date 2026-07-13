1. Model abstractions for interfacing with language models
2. Prompt Template for designing and generating standard prompts
3. Vector store adapters for storing and retrieving contextual information for prompts
4. Tooling framework for working with external services

*Without LangChain*: pain points of building without the framework — 
1. Needing to learn each LLM provider's API individually
2. Handle each provider's API changes yourself, using different workflows for tool calling, RAG, structured outputs, etc., 3. Need a complete rewrite of your application to switch providers.

*With LangChain*: Working with different LLM providers in a single project through one unified interface
1. LangChain handling underlying API changes for each provider
2. Uniform workflows across tool calling, RAG, structured outputs, etc.
3. Able to easily swap LLM providers without changing the application's logic.

Overall, LangChain abstracts away provider-specific complexity and makes switching or supporting multiple LLM providers much simpler.
