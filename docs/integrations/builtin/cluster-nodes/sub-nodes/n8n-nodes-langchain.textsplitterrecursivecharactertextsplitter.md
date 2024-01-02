---
title: Recursive Character Text Splitter
description: Documentation for the Recursive Character Text Splitter node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Recursive Character Text Splitter

The Recursive Character Text Splitter node splits document data recursively to keep all paragraphs, sentences then words together as long as possible.

On this page, you'll find the node parameters for the Recursive Character Text Splitter node, and links to more resources.

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [Recursive Character Text Splitter integrations](https://n8n.io/integrations/recursive-character-text-splitter/){:target=_blank .external-link} page.
///	

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"

## Node parameters

* **Chunk Size**: number of characters in each chunk.
* **Chunk Overlap**: how much overlap to have between chunks.

## Related resources

View [example workflows and related content](https://n8n.io/integrations/recursive-character-text-splitter/){:target=_blank .external-link} on n8n's website.

Refer to [LangChain's recursively split by character documentation](https://js.langchain.com/docs/modules/data_connection/document_transformers/text_splitters/recursive_text_splitter){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
