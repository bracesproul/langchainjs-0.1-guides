# langchainjs-0.1-guides

Heavily inspired by [Harrison Chase's](https://twitter.com/hwchase17) [LangChain PY 0.1.0 guide repo](https://github.com/hwchase17/langchain-0.1-guides)

These notebooks show off different functionality associated with LangChain.js 0.1.0.

To see the LangChain.js documentation, [click here](https://js.langchain.com/docs/get_started/introduction).

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

Next, you'll need Deno installed, and their experimental Jupyter notebook support.
Follow the instructions [here](https://docs.deno.com/runtime/manual/tools/jupyter).

## Notebooks
The following notebooks are provided:

- [Observability](observability.ipynb)
- [Composition](/composability.ipynb)
- [Streaming](/streaming.ipynb)
- [Output Parsing](/output_parsers.ipynb)
- [Retrieval](/retrieval.ipynb)
- [Agents](/agents.ipynb)