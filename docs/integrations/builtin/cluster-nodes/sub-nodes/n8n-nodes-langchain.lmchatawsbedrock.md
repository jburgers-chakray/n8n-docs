---
title: AWS Bedrock Chat Model
description: Documentation for the AWS Bedrock Chat Model node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# AWS Bedrock Chat Model

The AWS Bedrock Chat Model node allows you use LLM models utilising AWS Bedrock platform.

On this page, you'll find the node parameters for the AWS Bedrock Chat Model node, and links to more resources.

/// note | Credentials
You can find authentication information for this node [here](/integrations/builtin/credentials/aws/).
///

/// note | Examples and templates
For usage examples and templates to help you get started, refer to n8n's [Amazon Bedrock Model integrations](https://n8n.io/integrations/bedrock-model/){:target=_blank .external-link} page.
///

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"
	
## Node parameters

* **Model**: the model that generates the completion. Learn more about available models in the [Amazon Bedrock model documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html){:target=_blank .external-link}.

## Node options

* **Maximum Number of Tokens**: the completion length.
* **Sampling Temperature**: controls the randomness of the sampling process. A higher temperature creates more diverse sampling, but increases the risk of hallucinations.


## Related resources

View [example workflows and related content](https://n8n.io/integrations/bedrock-model/){:target=_blank .external-link} on n8n's website.

Refer to [LangChains's AWS Bedrock Chat Model documentation](https://js.langchain.com/docs/modules/model_io/models/chat/integrations/bedrock){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
