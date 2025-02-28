# Theater DIS192 : Azure AI Agent Service Introduction

_Join Azure AI Discord community to engage with a global community of learners and practitioners._

[![Azure AI Community Discord](
https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.com/invite/QR3kaErCRx)

<br/>

The [Azure AI Agent Service](https://learn.microsoft.com/azure/ai-services/agents/) is a **fully-managed** service that helps developers build, deploy, and scale, AI agents in a secure and extensible manner on the Azure AI Foundry platform. _The service is currently in public preview_.

## Session Description 

In this 15-minute session, we'll explore the Azure AI Agents Service from concepts to capabilities to code, using a real-world application scenario to set the context. By the end of this session, the audience should be able to:

1. Describe what the Azure AI Agent Service is, and its core benefits.
1. Build and use their first agent with the Azure AI Agent Service.
1. Integrate _knowledge tools_ to ground agent responses in their data.
1. Integrate _action tools_ to execute and orchestrate complex agent flows.

## Additional Resources

Check out the table below for additional resources for speakers and learners.

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| For Instructors | [Session Delivery Resources](./session-delivery-resources/README.md) | Resources for the session, including slides, demos, and deployment instructions. |
| For Learners | [WRK552: Build your first agent with Azure AI Agent Service](https://aka.ms/aitour/wrk552) | Hands-on workshop used in demo format for this session. Learners can follow the self-guided version here. |
| | |

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="https://github.com/nitya">
        <img src="https://github.com/nitya.png" width="100px;" alt="Nitya Narasimhan, PhD"/><br />
        <sub><b>Nitya Narasimhan, PhD</b></sub></a><br />
    </td>
    <td align="center"><a href="https://github.com/gloveboxes">
        <img src="https://github.com/gloveboxes.png" width="100px;" alt="Dave Glover"/><br />
        <sub><b>Dave Glover</b></sub></a><br />
    </td>
    <td align="center"><a href="https://github.com/revodavid">
        <img src="https://github.com/revodavid.png" width="100px;" alt="David Smith"/><br />
        <sub><b>David Smith</b></sub></a><br />
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Foundry, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Foundry](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
