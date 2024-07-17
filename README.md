# Azure OpenAI function calling a ServiceNow endpoint for incident details

This is sample code to illustrate how function calling may be used to all an LLM to call specific functions. In the case of this repo, ServiceNow REST API calls to find, create and update incidents.

ServiceNow has a REST API and some details of this can be found [here](https://docs.servicenow.com/bundle/utah-api-reference/page/integrate/inbound-rest/task/t_GetStartedCreateInt.html)

This repo will use this together with a ServiceNow demo instance to show how an OpenAI chat application can directly interact with ServiceNow APIs.

Later on this will be refactored to use [LangChain](https://python.langchain.com/v0.1/docs/get_started/introduction) and/or [Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/).

## Sample Code
In this repo, the [sample code](./openai-function-calling.ipynb) will be presented as a [Jupyter notebook](https://jupyter.org/) so this can be tried interactively.
