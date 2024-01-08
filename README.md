# langchainjs-0.1-guides

Heavily inspired by [Harrison Chase's](https://twitter.com/hwchase17) [LangChain PY 0.1.0 guide repo](https://github.com/hwchase17/langchain-0.1-guides)

These notebooks show off different functionality associated with LangChain.js 0.1.0.

## Setup

To setup, set required environment variables. We will use OpenAI for our language model, and Tavily for our search provider.

```bash
export OPENAI_API_KEY=...
export TAVILY_API_KEY=...
```

We will also use LangSmith for observability:

```bash
export LANGCHAIN_TRACING_V2="true"
export LANGCHAIN_API_KEY=...
export LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
```

Next, you'll need Deno installed, and their experimental Jupyter notebook support:

```bash
TODO: add instructions
```

## Notebooks
The following notebooks are provided:

- Observability
- Composition
- Streaming
- Output Parsing
- Retrieval
- [Agents]()