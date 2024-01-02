---
title: Redis Chat Memory
description: Documentation for the Redis Chat Memory node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Redis Chat Memory

Use the Redis Chat Memory node to use Redis as a memory server.

On this page, you'll find a list of operations the Redis Chat Memory node supports, and links to more resources.

/// note | Credentials
You can find authentication information for this node [here](/integrations/builtin/credentials/redis/).
///

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [Redis Chat Memory integrations](https://n8n.io/integrations/redis-chat-memory/){:target=_blank .external-link} page.
///	

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"

## Node parameters

* **Session Key**: the key to use to store the memory in the workflow data.
* **Session Time To Live**: make the session expire after a given number of seconds.

## Related resources

View [example workflows and related content](https://n8n.io/integrations/redis-chat-memory/){:target=_blank .external-link} on n8n's website.

Refer to [LangChain's Redis Chat Memory documentation](https://js.langchain.com/docs/modules/memory/integrations/redis){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
