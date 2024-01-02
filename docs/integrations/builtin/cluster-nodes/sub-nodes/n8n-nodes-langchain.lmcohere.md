---
title: Cohere Model
description: Documentation for the Cohere Model node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Cohere Model

Use the Cohere Model node to use Cohere's models.

On this page, you'll find the node parameters for the Cohere Model node, and links to more resources.

/// note | Credentials
You can find authentication information for this node [here](/integrations/builtin/credentials/cohere/).
///

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [Cohere Model integrations](https://n8n.io/integrations/cohere-model/){:target=_blank .external-link} page.
///

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"

## Node Options

* **Maximum Number of Tokens**: the completion length, in characters.
* **Sampling Temperature**: controls the randomness of the sampling process. A higher temperature creates more diverse sampling, but increases the risk of hallucinations.


## Related resources

View [example workflows and related content](https://n8n.io/integrations/cohere-model/){:target=_blank .external-link} on n8n's website.

Refer to [LangChains's Cohere documentation](https://js.langchain.com/docs/modules/model_io/models/llms/integrations/cohere){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
