---
layout: Conceptual
title: 'Study guide for Exam GH-300: GitHub Copilot | Microsoft Learn'
canonicalUrl: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-300
breadcrumb_path: /breadcrumb/toc.json
feedback_system: None
uhfHeaderId: MSDocsHeader-Certifications
description: 'Study guide for Exam GH-300: GitHub Copilot | Microsoft Docs'
documentationcenter: NA
author: Micsullivan
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: NA
ms.date: 2026-02-04T00:00:00.0000000Z
ms.author: msulliv
ms.service: learn
locale: en-us
document_id: 59042360-ced3-8b56-c219-dfc8c29476f4
document_version_independent_id: 59042360-ced3-8b56-c219-dfc8c29476f4
updated_at: 2026-02-19T18:28:00.0000000Z
original_content_git_url: https://github.com/MicrosoftDocs/learn-certs-pr/blob/live/learn-certs-pr/certifications/resources/study-guides/gh-300.md
gitcommit: https://github.com/MicrosoftDocs/learn-certs-pr/blob/05eeaec301a39274faca3aa17a1bbc272825537f/learn-certs-pr/certifications/resources/study-guides/gh-300.md
git_commit_id: 05eeaec301a39274faca3aa17a1bbc272825537f
site_name: Docs
depot_name: MSDN.learn-certs-pr
page_type: conceptual
toc_rel: ../../../toc.json
feedback_product_url: ''
feedback_help_link_type: ''
feedback_help_link_url: ''
word_count: 984
asset_id: certifications/resources/study-guides/gh-300
moniker_range_name: 
monikers: []
item_type: Content
source_path: learn-certs-pr/certifications/resources/study-guides/gh-300.md
cmProducts:
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/46e3c7c4-fe77-4a6e-b40a-44c569819fa5
- https://authoring-docs-microsoft.poolparty.biz/devrel/9bdc1705-9b40-49d6-8377-caa0b71fda66
- https://authoring-docs-microsoft.poolparty.biz/devrel/a3955c7b-f5ee-420d-aff5-d7119738f38b
spProducts:
- https://microsoft-devrel.poolparty.biz/DevRelOfferingOntology/d0c6fab8-2d7d-4bb0-bf40-589e08d7c132
- https://authoring-docs-microsoft.poolparty.biz/devrel/686ed158-d915-41e9-9760-efa46ba88f6d
- https://authoring-docs-microsoft.poolparty.biz/devrel/b31948f4-2f38-404b-ac93-c3c8c5b3ae33
platformId: 9780027f-895c-16a2-be00-c55d2ee8bb1c
---

# Study guide for Exam GH-300: GitHub Copilot | Microsoft Learn

## Purpose of this document

This study guide should help you understand what to expect on the exam and includes a summary of the topics the exam might cover and links to additional resources. The information and materials in this document should help you focus your studies as you prepare for the exam.

| Useful links | Description |
| --- | --- |
| [How to earn the certification](/en-us/credentials/certifications/github-copilot/?practice-assessment-type=certification) | Some certifications only require passing one exam, while others require passing multiple exams. |
| [Certification renewal](/en-us/credentials/certifications/renew-your-microsoft-certification) | Microsoft associate, expert, and specialty certifications expire annually. You can renew by passing a free online assessment on Microsoft Learn. |
| [Your Microsoft Learn profile](/en-us/users/) | Connecting your certification profile to Microsoft Learn allows you to schedule and renew exams and share and print certificates. |
| [Exam scoring and score reports](/en-us/credentials/certifications/exam-scoring-reports) | A score of 700 or greater is required to pass. |
| [Exam sandbox](https://aka.ms/GHExamDemo-enu) | You can explore the exam environment by visiting our exam sandbox. |
| [Request accommodations](/en-us/credentials/certifications/request-accommodations) | If you use assistive devices, require extra time, or need modification to any part of the exam experience, you can request an accommodation. |

## About the exam

Some exams are localized into other languages, and those are updated approximately eight weeks after the English version is updated. While Microsoft makes every effort to update localized versions as noted, there may be times when the localized versions of an exam are not updated on this schedule. Other available languages are listed in the **Schedule Exam** section of the **Exam Details** webpage. If the exam isn't available in your preferred language, you can request an additional 30 minutes to complete the exam.

#### Note

The bullets that follow each of the skills measured are intended to illustrate how we are assessing that skill. Related topics may be covered in the exam.

#### Note

Most questions cover features that are general availability (GA). The exam may contain questions on Preview features if those features are commonly used.

## Skills measured as of January 2026

### Audience profile

Candidates for this exam should possess expertise in using GitHub Copilot to improve software development productivity, quality, and security. This includes responsible AI use, prompt engineering, Copilot features across various plans, and privacy safeguards. Candidates should also be familiar with GitHub fundamentals and have experience with one or more programming languages.

### Skills at a glance

- Use GitHub Copilot responsibly (15–20%)
- Use GitHub Copilot features (25–30%)
- GitHub Copilot features (25–30%)
- Understand GitHub Copilot data and architecture (10–15%)
- Apply prompt engineering and context crafting (10–15%)
- Improve developer productivity with GitHub Copilot (10–15%)
- Configure privacy, content exclusions, and safeguards (10–15%)

### Use GitHub Copilot responsibly (15–20%)

#### Understand responsible AI principles

- Describe risks and limitations of Generative AI tools
- Describe ethical and responsible AI usage
- Identify potential harms and mitigation strategies of AI usage

#### Validate and operate AI tools

- Explain the need to validate AI output
- Identify how to operate GitHub Copilot responsibly

### Use GitHub Copilot features (25–30%)

#### Use GitHub Copilot in the IDE

- Enable Copilot in the IDE
- Trigger Copilot through inline suggestions, chat, CLI, and Plan Mode
- Exclude specific files or repositories (app knowledge)

#### Use GitHub Copilot CLI

- Define GitHub Copilot CLI and how it benefits developers
- Identify the steps for installing GitHub Copilot CLI
- Describe key GitHub Copilot CLI features and commands
- Use GitHub Copilot CLI interactively and in sessions
- Generate scripts and manage files with GitHub Copilot CLI

#### Use GitHub Copilot features and capabilities

- Use Agent Mode, Edit Mode, and MCP for enhanced development and workflows; manage Agent Sessions and delegate tasks to Sub‑Agents for optimized context usage
- Use Copilot for code review and coding assistance
- Utilize Spaces, Spark, Pull Request summaries, and customizable review standards via instructions files
- Understand the limits, options, feedback, and commands of GitHub Copilot Chat; include prompt file reuse for consistent responses

#### Manage organization-wide settings and policies

- Configure organization-wide policy management; enable Copilot Code Review policies and manage feature availability across IDEs and github.com
- Utilize audit log events
- Manage subscriptions using the REST API

# Understand GitHub Copilot data and architecture (10–15%)

### Describe data handling and flow

- Explain data usage, flow, and sharing
- Describe input processing and prompt building
- Explain proxy filtering and post-processing

#### Understand lifecycle and limitations

- Visualize code suggestion lifecycle
- Describe limitations of LLMs and Copilot

### Apply prompt engineering and context crafting (10–15%)

#### Craft effective prompts

- Describe prompt structure and context
- Understand how context is determined
- Use zero-shot and few-shot prompting
- Apply best practices for prompt crafting

#### Engineer prompts for performance

- Explain prompt engineering principles
- Describe prompt process flow and chat history usage

### Improve developer productivity with GitHub Copilot (10–15%)

#### Enhance productivity and code quality

- Use Copilot for code generation, refactoring, and documentation
- Accelerate learning and reduce context switching
- Generate sample data and modernize legacy code

#### Support testing and security

- Generate unit and integration tests
- Identify edge cases and write assertions
- Suggest security improvements and performance optimizations

### Configure privacy, content exclusions, and safeguards (10–15%)

#### Manage privacy settings and exclusions

- Configure content exclusions and editor settings
- Describe ownership and limitations of outputs

#### Apply safeguards and troubleshoot

- Enable duplication detection and security warnings
- Resolve issues with suggestions and exclusions

## Study resources

We recommend that you train and get hands-on experience before you take the exam. We offer self-study options and classroom training as well as links to documentation, community sites, and videos.

| Study resources | Links to learning and documentation |
| --- | --- |
| Get trained | Choose from self-paced learning paths and modules or take an instructor-led course on Microsoft Learn – [GitHub Copilot Fundamentals Part 1](/en-us/training/paths/copilot/) and [GitHub Copilot Fundamentals Part 2](/en-us/training/paths/gh-copilot-2/) |
| Find documentation | [Responsible AI](/en-us/training/modules/responsible-ai-with-github-copilot/)[GitHub Copilot plans and features](https://docs.github.com/copilot/about-github-copilot/plans-for-github-copilot)[How GitHub Copilot works and handles data](https://github.com/trust-center)[Prompt crafting and prompt engineering](https://docs.github.com/copilot/using-github-copilot/copilot-chat/prompt-engineering-for-copilot-chat)[Developer use cases for AI](/en-us/training/modules/developer-use-cases-for-ai-with-github-copilot/)[Testing with GitHub Copilot](/en-us/training/modules/develop-unit-tests-using-github-copilot-tools/)[Privacy fundamentals and content exclusions](https://docs.github.com/copilot/managing-copilot/configuring-and-auditing-content-exclusion) |
| Ask a question | [GitHub Community Discussions](https://github.community/) |
| Get community support | [GitHub Blog](https://github.blog/) |
| Follow GitHub | [Twitter](https://twitter.com/github)[LinkedIn](https://www.linkedin.com/company/github)[Instagram](https://www.instagram.com/github/) |
| Find a video | [YouTube](https://www.youtube.com/github) |

## Change log

This exam has changed significantly (e.g., new objectives were added, some were removed, existing objectives may have moved to different functional groups, and all were reworded) on January, 2026.