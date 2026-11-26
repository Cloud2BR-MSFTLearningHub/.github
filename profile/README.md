<div align="center">

<img src="https://github.com/Cloud2BR-MSFTLearningHub.png?size=128" width="128" alt="Cloud2BR Microsoft Cloud Sandbox Learning Hub logo" />

# Cloud2BR Microsoft Cloud Sandbox - Learning Hub

**Prototype in a sandbox. Build, experiment, and share practical Microsoft Cloud learning.**

<a href="https://github.com/Cloud2BR-MSFTLearningHub" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Hub-Microsoft%20Cloud%20Sandbox-0A66C2?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Hub"></a>
<a href="#learning-resources" target="_self"><img src="https://img.shields.io/badge/Format-Demos%20%7C%20PoCs%20%7C%20Study%20Guides-6A1B9A?style=for-the-badge" alt="Format"></a>
<a href="https://github.com/Cloud2BR-MSFTLearningHub" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Community-Open%20Learning-2E7D32?style=for-the-badge&logo=github&logoColor=white" alt="Community"></a>

</div>

----------

> **Mission:** Provide a safe place to test ideas, create educational materials, build proof-of-concepts, and share personal learning across Microsoft Cloud technologies.

## Organizations and initiatives

Explore the connected Cloud2BR initiatives:

| Organization | Focus | Explore |
| --- | --- | --- |
| <img src="https://github.com/Cloud2BR-MSFTLearningHub.png?size=80" width="28" height="28" alt=""> **[Cloud2BR Microsoft Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)** | Microsoft labs, guides, and examples | [Catalog](https://cloud2br-msftlearninghub.github.io/org-catalog/) |
| <img src="https://github.com/Cloud2BR.png?size=80" width="28" height="28" alt=""> **[Cloud2BR](https://github.com/Cloud2BR)** | Cloud consulting and enablement | [OSS hub](https://cloud2br.github.io/oss-hub/) |
| <img src="https://github.com/Cloud2BR-TEC.png?size=80" width="28" height="28" alt=""> **[Cloud2BR-TEC](https://github.com/Cloud2BR-TEC)** | Technology education and practice | [Education](https://cloud2br-tec.github.io/tec-hub/) |

## Learning resources

Choose a starting point for your next Microsoft Cloud learning journey. Browse
the [full catalog](https://cloud2br-msftlearninghub.github.io/org-catalog/)
to discover more projects.

| Category | What you will find | Start exploring |
| --- | --- | --- |
| **Demos and technical talks** | Practical scenarios, presentations, and examples across Microsoft Cloud technologies. | [Demos and scenarios](https://github.com/Cloud2BR-MSFTLearningHub/DemosScenarios-TechTalks) |
| **Sandbox experiments and PoCs** | Hands-on projects for testing ideas and building practical experience in an approved environment. | [AI agent infrastructure blueprint](https://github.com/Cloud2BR-MSFTLearningHub/AI-Agent-Infra-Blueprint) |
| **Study guides and certifications** | Structured learning resources to support Microsoft and GitHub certification preparation. | [AI-900](https://github.com/Cloud2BR-MSFTLearningHub/AI-900StudyGuide) · [GH-900](https://github.com/Cloud2BR-MSFTLearningHub/GH-900StudyGuide) |
| **Solutions and use cases** | Reference implementations and examples that connect concepts to real-world scenarios. | [Fabric enterprise framework](https://github.com/Cloud2BR-MSFTLearningHub/Fabric-EnterpriseFramework) |
| **Scripts and sample code** | Reusable technical assets for demonstrations, automation, and experimentation. | [Blob upload and summary tool](https://github.com/Cloud2BR-MSFTLearningHub/BlobFileUpload-SummaryTool) |

## Endorsements and certifications

<details>
<summary><strong>Endorsed for Microsoft TechWorkshops</strong></summary>

- <a href="https://partner.microsoft.com/id-id/marketing-center/assets/collection/migrate-and-modernize-your-estate#/" target="_blank" rel="noopener noreferrer">L200: Migrate and Modernize your Estate</a>
- <a href="https://microsoft.github.io/TWL200-Copilot-and-agents-at-work/" target="_blank" rel="noopener noreferrer">L200: Azure AI Apps and Agents</a>
- <a href="https://microsoft.github.io/TechWorkshop-L300-AI-Apps-and-agents/" target="_blank" rel="noopener noreferrer">L300: Azure AI Apps and Agents</a>
- <a href="https://github.com/microsoft/TechWorkshop-L300-GitHub-Copilot-and-platform" target="_blank" rel="noopener noreferrer">L300: GitHub Copilot and platform</a>

</details>

<details>
<summary><strong>Microsoft certification study guides</strong></summary>

- <a href="https://github.com/Cloud2BR-MSFTLearningHub/AI-900StudyGuide" target="_blank" rel="noopener noreferrer">AI-900: Azure AI Fundamentals</a>
- <a href="https://github.com/Cloud2BR-MSFTLearningHub/DP-900StudyGuide" target="_blank" rel="noopener noreferrer">DP-900: Azure Data Fundamentals</a>
- <a href="https://github.com/Cloud2BR-MSFTLearningHub/AI-102StudyGuide" target="_blank" rel="noopener noreferrer">AI-102: Azure AI Engineer Associate</a>
- <a href="https://github.com/Cloud2BR-MSFTLearningHub/DP-100StudyGuide" target="_blank" rel="noopener noreferrer">DP-100: Designing and Implementing a Data Science Solution on Azure</a>
- <a href="https://github.com/Cloud2BR-MSFTLearningHub/GH-900StudyGuide" target="_blank" rel="noopener noreferrer">GH-900: GitHub Foundations</a>

</details>

## Copilot services and tools

```mermaid
flowchart LR
  subgraph Personal_Productivity[Personal Productivity]
    CopilotChat[Copilot Chat] --> M365Copilot[M365 Copilot]
  end

  subgraph Business_Productivity[Business Productivity]
    MicrosoftAgents[Microsoft Agents]
  end

  subgraph Extensibility[Extensibility]
    CopilotStudio[Copilot Studio] --> AzureAIFoundry[Azure AI Foundry]
  end

  subgraph Customizability[Customizability]
    ThirdPartyCustomAgents[3rd Party and Custom Agents]
  end

  M365Copilot --> MicrosoftAgents
  MicrosoftAgents --> CopilotStudio
  AzureAIFoundry --> ThirdPartyCustomAgents

  classDef productivity fill:#0B6E99,stroke:#66D9EF,color:#FFFFFF
  classDef business fill:#397A3F,stroke:#9EE493,color:#FFFFFF
  classDef extensibility fill:#8A5A00,stroke:#F5C451,color:#FFFFFF
  classDef custom fill:#8B2E63,stroke:#F3A6CD,color:#FFFFFF
  class CopilotChat,M365Copilot productivity
  class MicrosoftAgents business
  class CopilotStudio,AzureAIFoundry extensibility
  class ThirdPartyCustomAgents custom
```

## Deployment lifecycle of software

```mermaid
flowchart LR
  subgraph Versioning[Semantic Versioning]
    Major[Major Version: X] --> Minor[Minor Version: X.X]
    Minor --> Patch[Patch Version: X.X.X]
  end

  subgraph Release_Types[Release Types]
    DevBuild[Development Build] --> Alpha[Alpha Release]
    Alpha --> Beta[Beta Release]
    Beta --> RC[Release Candidate]
    RC --> Stable[Stable Release]
  end

  subgraph Maintenance[Maintenance and Updates]
    Stable --> Hotfix[Hotfix Patch]
    Stable --> FeatureUpdate[Feature Update Minor]
    Stable --> BreakingChange[Breaking Change Major]
  end

  Major --> Minor
  Minor --> Patch
  Stable --> Versioning

  classDef build fill:#0B6E99,stroke:#66D9EF,color:#FFFFFF
  classDef preview fill:#8A5A00,stroke:#F5C451,color:#FFFFFF
  classDef release fill:#397A3F,stroke:#9EE493,color:#FFFFFF
  classDef maintenance fill:#8B2E63,stroke:#F3A6CD,color:#FFFFFF
  classDef versioning fill:#5B4B8A,stroke:#C4B5FD,color:#FFFFFF
  class DevBuild build
  class Alpha,Beta,RC preview
  class Stable release
  class Hotfix,FeatureUpdate,BreakingChange maintenance
  class Major,Minor,Patch versioning
```

<details>
<summary><strong>Lifecycle details</strong></summary>

- **Semantic Versioning (vX.X.X)**
  - **Major (X):** Introduces breaking changes. Example: `v2.0.0` is incompatible with `v1.x.x`.
  - **Minor (X.X):** Adds backward-compatible features. Example: `v1.3.0`.
  - **Patch (X.X.X):** Provides bug fixes or small improvements. Example: `v1.3.2`.
- **Release Types**
  - **Development Builds:** Internal and unstable builds, often produced nightly.
  - **Alpha:** Early testing with incomplete or unstable features, mainly for developers and a small internal QA group.
  - **Beta:** Feature-complete builds for limited external feedback, usability testing, and bug discovery.
  - **Release Candidate (RC):** A candidate for the final product; only critical fixes should be made.
  - **General Availability (GA):** Official public release that is stable, supported, and production-ready.
- **Maintenance and Updates**
  - **Hotfix (Patch):** Urgent bug or security fix that increments the patch version.
  - **Feature Update (Minor):** Adds functionality without breaking compatibility.
  - **Breaking Change (Major):** Requires a major version increment.

</details>

## Get involved

- **Explore** the organization repositories for demos, study guides, tools, and reference material.
- **Experiment** with the sandbox projects and adapt them to approved learning environments.
- **Contribute** through issues, pull requests, technical talks, and knowledge sharing.

> [!IMPORTANT]
> Materials, including scripts and sample code, are provided **AS-IS** and **WITH ALL FAULTS**. Pricing estimates are for demonstration purposes only and do not reflect final pricing. Cloud2BR assumes no liability for use of this information. For official guidance, support, or detailed information, refer to Microsoft's documentation or contact <a href="https://support.microsoft.com/contactus?ContactUsExperienceEntryPointAssetId=S.HP.SMC-HOME" target="_blank" rel="noopener noreferrer">Microsoft Sales and Support</a>.

> [!NOTE]
> Content is intended for learning, demonstrations, and practical experimentation. Review and validate materials before production use.
