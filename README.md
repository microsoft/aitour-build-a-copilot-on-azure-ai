# Build a Retail Copilot Code-First on Azure AI

Use Azure AI Studio to build, evaluate, and deploy a customer support chat app. This custom copilot uses a RAG architecture built with Azure AI Search, Azure CosmosDB and Azure OpenAI to return responses grounded in the product and customer data.

## Session Description

In this sample we build, evaluate and deploy a customer support chat AI for Contoso Outdoors, a fictitious retailer who sells hiking and camping equipment. The implementation uses a Retrieval Augmented Generation (RAG) architecture to implement a retail copilot solution that responds to customer queries with answers grounded in the company's product catalog and customer purchase history. The sample uses Azure AI Search to create and manage search indexes for product catalog data, Azure Cosmos DB to store and manage customer purchase history data, and Azure OpenAI to deploy and manage the core models required for our RAG-based architecture.
By exploring and deploying this sample, you will learn to: Build a retail copilot application using the RAG pattern, define and engineer prompts using the Prompty asset, design, run & evaluate a copilot using the Promptflow framework, provision and deploy the solution to Azure using the Azure Developer CLI, understand and apply Responsible AI practices like evaluation and content safety.

## Learning Outcomes

* Use Azure AI Studio as a code-first platform for building custom copilots​

* Prototype custom copilot on VS Code with powerful tools (Prompty, Promptflow, Codespaces)​

* Optimize your custom copilot with manual testing & AI-assisted evaluation (Quality, Safety)​

* Operationalize your custom copilot by deploying to Azure AI Studio (Monitoring, Filters, Logs)​

* Customize the sample to suit your application scenario (data, functions, frameworks, models)

## Technology Used

* Github Codespaces
* Azure AI Studio
* Azure AI Search
* Cosmos DB
* OpenAI GPT models

## Additional Resources and Continued Learning

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| contoso-chat  | https://github.com/Azure-Samples/contoso-chat | Complete sample repository from workshop |

## Repository Guide

1. The src folder has been created for all development tasks when creating this session.
1. The Lab folder is in-person and async participation with content.
1. The [session-delivery-resources folder](session-delivery-resources) is intended for workshop presenters and proctors. Here you will find slide decks, demo videos, and other content.

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://media.licdn.com/dms/image/C4D03AQGMiGWZFIRUKw/profile-displayphoto-shrink_400_400/0/1516235415849?e=1729123200&v=beta&t=VXALfEkkWIwxTqml7vzZX1wRh9NyZLg3H2Ln6RCsjjA" width="100px;" alt="David Smith"/><br />
        <sub><b>David Smith
</b></sub></a><br />
            <a href="https://www.linkedin.com/in/dmsmith/" title="linkedin">📢</a> 
    </td>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/nitya.png" width="100px;" alt="Nitya Narasimhan"/><br />
        <sub><b>Nitya Narasimhan
</b></sub></a><br />
            <a href="https://github.com/nitya" title="talk">📢</a> 
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
