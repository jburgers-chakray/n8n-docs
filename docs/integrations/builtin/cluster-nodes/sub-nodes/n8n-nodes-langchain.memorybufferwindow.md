---
title: Window Buffer Memory
description: Documentation for the Window Buffer Memory node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Window Buffer Memory

Use the Window Buffer Memory node to persist chat history in your workflow.

On this page, you'll find a list of operations the Window Buffer Memory node supports, and links to more resources.

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [Window Buffer Memory integrations](https://n8n.io/integrations/window-buffer-memory/){:target=_blank .external-link} page.
///	

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"

## Node parameters

* **Session Key**: the key to use to store the memory in the workflow data.
* **Context Window Length**: the number of previous messages to consider for context.


## Related resources

View [example workflows and related content](https://n8n.io/integrations/window-buffer-memory/){:target=_blank .external-link} on n8n's website.

Refer to [LangChain's Buffer Window Memory documentation](https://js.langchain.com/docs/modules/memory/how_to/buffer_window_memory){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
