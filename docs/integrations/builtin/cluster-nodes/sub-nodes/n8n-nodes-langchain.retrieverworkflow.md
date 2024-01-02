---
title: Workflow Retriever
description: Documentation for the Workflow Retriever node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Workflow Retriever

Use the Workflow Retriever node to retrieve data from an n8n workflow for use in a Retrieval QA Chain or another Retriever node.

On this page, you'll find the node parameters for the Workflow Retriever node, and links to more resources.

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [LangChain integrations](https://n8n.io/integrations/workflow-retriever/){:target=_blank .external-link} page.
///	

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"

## Node parameters

### Source

Tell n8n which workflow to call. You can choose either:

* **Database**, then enter a workflow ID.
* **Parameter**, then copy in a complete [workflow JSON](/workflows/export-import/).

### Workflow values

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-sub-nodes/workflow-values.md"


## Related resources

View [example workflows and related content](https://n8n.io/integrations/workflow-retriever/){:target=_blank .external-link} on n8n's website.

Refer to [LangChain's general retriever documentation](https://js.langchain.com/docs/modules/data_connection/retrievers/){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
