# Microsoft Copilot and ChatGPT Enterprise: A Practical Selection Guide

Both tools can contribute to the same workflow. Choose according to where the approved source material lives, where the work will be completed, what result is required, and who must review it.

This is a selection guide rather than a product scorecard. The appropriate starting point depends on the user’s license, enabled features, source permissions, task, and organizational policy.

> **Start with the tool closest to the work and the approved source. Add the second tool only when it contributes a specific capability.**

## TL;DR

- Start with **Microsoft Copilot** when the task is centered on Microsoft 365 work, such as an Outlook thread, Teams meeting, Word document, PowerPoint presentation, or Excel workbook.
- Start with **ChatGPT Enterprise** when selected files, web sources, projects, plugins, reusable workflows, or Codex are the appropriate working context for the task.
- Use both when Microsoft Copilot can locate or summarize approved Microsoft 365 context and ChatGPT Enterprise can perform the next approved analysis or production step.
- Confirm that transferring content between the two environments is allowed. Access in one system does not automatically authorize copying information into another.
- Review sources, facts, names, dates, numbers, recommendations, and consequential actions before using the result.

## Product-name and access note

**Microsoft 365 Copilot is now named Microsoft Copilot.** Some experiences and licenses may retain the earlier name during the transition. Copilot capabilities differ by license, tenant configuration, application, and administrator settings. For example, automatic grounding in Microsoft 365 work data depends on the licensed experience; some Copilot Chat experiences require the user to provide or open the relevant content. See the current [Microsoft Copilot overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-overview).

ChatGPT Enterprise capabilities also depend on workspace settings, enabled plugins, approved connections, platform, region, and rollout. The [official OpenAI selection guide](https://learn.chatgpt.com/docs/use-chatgpt) describes Chat for conversation, ChatGPT Work for a finished and reviewable result, and Codex for technical work.

ChatGPT Work cloud does not automatically inherit local files, desktop sessions, or private-network access. Local files and repositories must be intentionally attached, selected, connected, or made available through an enabled local ChatGPT Work or Codex environment.

This guide compares Microsoft Copilot, including app-based experiences and **Copilot Cowork** when available, with the Chat, ChatGPT Work, and Codex experiences enabled in a ChatGPT Enterprise workspace.

## When to use Microsoft Copilot vs. ChatGPT Enterprise

| Decision factor | Microsoft Copilot | ChatGPT Enterprise |
|---|---|---|
| Where the work already lives | Word, Excel, PowerPoint, Outlook, Teams, OneDrive, SharePoint, and other configured Microsoft 365 services | Intentionally attached or selected files, projects, chats, web sources, configured plugins, approved connected apps, and local folders or repositories explicitly made available to local ChatGPT Work or Codex |
| Primary advantage | Works across Microsoft 365 applications and, in applicable licensed experiences, can use permitted work context; Cowork can carry out connected tasks across Microsoft 365 | Works across user-selected files, projects, web sources, approved plugins, artifacts, and Codex environments |
| Strong first tasks | Summarize an email thread or meeting, edit a document, analyze a workbook, prepare a presentation, or complete a connected Cowork assignment | Compare selected sources, create an artifact, apply a reusable ChatGPT workflow, analyze files, or complete technical work through Codex |
| Source grounding | Microsoft 365 work data, open content, attached files, agents, or the web, depending on license and configuration | User-provided sources, project context, web research, Library content, memories, and connected tools when enabled |
| Output location | Microsoft 365 applications plus Word, Excel, PowerPoint, PDF, email, Teams, and file actions through Cowork when enabled | Chat plus documents, spreadsheets, presentations, PDFs, visualizations, Sites, code, and repository changes when enabled |
| Reusable setup | Agents, templates, prompt examples, Cowork Skills and plugins, and scheduled or event-driven tasks when enabled | Projects, GPTs, Skills, plugins, scheduled tasks, and Codex workflows |
| Technical delivery | Microsoft 365 application work, Cowork tasks, and configured agents or plugins | Codex is designed for codebases, scripts, tests, repositories, validation, and technical implementation |
| Main check before starting | Confirm the Copilot license, current application context, data permissions, and expected output | Confirm the workspace, approved inputs, plugin permissions, execution environment, and review point |

### Where the products overlap

Both products can analyze information, research across sources, create documents and other artifacts, use plugins or Skills, and run recurring work when the required features are available. Microsoft [documents these capabilities for Copilot Cowork](https://learn.microsoft.com/en-us/microsoft-365/copilot/cowork/), while OpenAI [documents them across ChatGPT Work and Codex](https://learn.chatgpt.com/docs/use-chatgpt).

Choose from the actual source, connection, destination, and review requirements. Feature overlap alone does not create a reason to move a task between systems.

### Start with Microsoft Copilot when

- The source is an Outlook conversation, Teams meeting, SharePoint or OneDrive file, Word document, PowerPoint deck, or Excel workbook that the user is permitted to access.
- The result should remain inside a Microsoft 365 application for editing, collaboration, or distribution.
- The task is tied closely to the content currently open in an application.
- The licensed experience can retrieve the required work context through Microsoft Graph or another approved source.
- Cowork has the approved Microsoft 365 access and actions required to complete a connected assignment.

Microsoft states that Copilot works with Microsoft 365 applications and only surfaces organizational data the user is permitted to access. The exact grounding behavior depends on the license and configuration, so users should verify the source citations and confirm which content was actually used. See the [Microsoft Copilot overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-overview) and [data, privacy, and security guidance](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-privacy).

### Start with ChatGPT Enterprise when

- The approved sources are already attached, stored in a ChatGPT Project, or available through configured ChatGPT plugins.
- The assignment will use a ChatGPT-specific Project, GPT, Skill, visualization, Site, or other enabled workflow.
- A recurring role or procedure should be preserved in a Project, GPT, or Skill.
- The work requires code, scripts, testing, file processing, repository changes, or a technical implementation through Codex.
- Approved plugins or connected tools are needed to extend the task beyond uploaded files.

OpenAI documents that ChatGPT Work can gather context, use tools, analyze information, create finished files, and carry a larger assignment through to a result for review. Available tools and connections depend on workspace configuration. See [Use ChatGPT](https://learn.chatgpt.com/docs/use-chatgpt) and [plugin controls](https://learn.chatgpt.com/docs/enterprise/apps-and-connectors).

### Use both when

- The approved source material lives in Microsoft 365 and the next approved step belongs in a configured ChatGPT project, plugin, artifact workflow, or Codex environment.
- Microsoft Copilot can provide approved Microsoft 365 evidence, while ChatGPT Enterprise can combine that evidence with other permitted sources or a ChatGPT-specific workflow.
- ChatGPT Enterprise or Codex produces a technical or analytical result that must be explained, edited, or distributed through Microsoft 365.
- Each handoff has an identified owner, permitted source set, review point, and destination.

## Best practice when using both: Define a controlled handoff

Treat the handoff as a controlled workflow:

1. **Retrieve close to the source.** Use Microsoft Copilot to locate permitted Microsoft 365 information when the license and application support it.
2. **Preserve the evidence.** Prefer approved original files, relevant extracts, or an approved direct ChatGPT connection to the source. A summary alone can remove details needed for reliable analysis.
3. **Select the minimum necessary content.** Remove unrelated, sensitive, duplicated, or outdated material before any transfer.
4. **Confirm transfer permission.** Check organizational policy before copying, uploading, connecting, or reproducing content in another system.
5. **Use the second environment for a named contribution.** State which source, workflow, artifact, or technical capability requires ChatGPT Enterprise.
6. **Validate against the originals.** Recheck important claims, numbers, names, dates, citations, and omissions in the source system.
7. **Return the reviewed result.** Move only the approved final material into Word, PowerPoint, Excel, Outlook, Teams, or another authorized destination.
8. **Set an approval rule.** As an organizational practice, require a person to approve consequential external actions even when product configuration permits execution without another prompt.

### Example combined workflow: leadership meeting brief

| Stage | Tool | Task | Required check |
|---|---|---|---|
| 1 | Microsoft Copilot | Locate the permitted meeting transcript, related email thread, and named Microsoft 365 files; prepare a source manifest and relevant extracts | Confirm every source was included and the user had access |
| 2 | Reviewer | Approve the original files or extracts needed for the next step and remove unrelated or restricted information | Confirm transfer or direct connection is permitted |
| 3 | ChatGPT Enterprise | Compare the approved evidence, identify decisions, risks, conflicting evidence, and open questions, then draft the brief | Separate source facts from interpretation and recommendations |
| 4 | Reviewer | Verify names, dates, numbers, citations, and requested decisions against the originals | Correct unsupported or overstated claims |
| 5 | Microsoft 365 | Edit, collaborate, and distribute the approved brief through the designated application | Obtain approval before sending or publishing |

## Prompting tips and examples

Microsoft recommends four prompt ingredients: **goal, context, expectations, and source**. OpenAI recommends **goal, context, output, and boundaries** for larger tasks. This guide combines them into one practical formula: **goal + context + approved sources + expected output + boundaries + review point**. See Microsoft’s [prompting guide](https://support.microsoft.com/en-us/microsoft-365-copilot/get-started-writing-prompts-in-microsoft-365-copilot) and OpenAI’s [prompting guide](https://learn.chatgpt.com/docs/prompting).

### Prompt 1: Microsoft Copilot meeting catch-up

```text
Using only the transcript and meeting chat from [meeting name and date], prepare:

1. Decisions made
2. Open questions
3. Commitments with owners and dates
4. Risks or dependencies discussed
5. Items that require follow-up

Provide a source citation for each important point. Write "Not provided" when an owner, date, or decision is missing. Do not send or publish anything.
```

### Prompt 2: Microsoft Copilot email-thread review

```text
Review this email thread and summarize the request, decisions already made, unresolved issues, deadlines, and named owners.

Then draft a concise reply that confirms the agreed actions and asks only for information that is still missing. Keep the message as a draft and identify any statement that needs verification before sending.
```

### Prompt 3: ChatGPT Enterprise cross-source comparison

```text
Compare the attached [documents, proposals, or reports] for [audience and decision].

Use only the supplied sources. Evaluate them against [criteria]. Produce:

- A five-line summary
- A comparison table
- Areas of agreement and conflict
- Missing evidence
- Major risks and tradeoffs
- A recommendation with stated assumptions

Cite the supporting source for each important claim. Separate verified facts, interpretation, and recommendation. Pause before any external action.
```

### Prompt 4: Controlled two-tool handoff

Use this first in Microsoft Copilot:

```text
Using only [named Microsoft 365 sources] from [period], extract the facts, decisions, dates, owners, and unresolved questions relevant to [assignment].

Include a source manifest with each source title, date, stable reference or link, and the supporting extract. Keep the original Microsoft 365 citations where available. Do not add recommendations. Flag conflicting or missing information and prepare the result for reviewer approval before it is used in another system.
```

After review and transfer approval, use this in ChatGPT Enterprise:

```text
Using only the approved source extract and source manifest attached here, prepare [deliverable] for [audience] to support [decision].

Preserve the source references from the manifest. A protected link may remain accessible only in the source system, so do not claim direct access unless you can open it. Identify any conclusion that is not directly supported. Use [format and length]. Pause before sending, publishing, or changing information in another system.
```

### Prompt 5: Validate either tool’s output

```text
Cross-check this result against the named sources.

List:
1. Supported claims
2. Unsupported or overstated claims
3. Missing qualifications
4. Conflicting evidence
5. Names, dates, or numbers that require confirmation
6. Actions that require approval

List any source you cannot access as unverified, and do not describe its claims as cross-checked. Do not rewrite the result until the verification findings are complete.
```

## Expectations for responsible and effective AI usage

1. **Use the approved enterprise account and workspace.** Personal accounts can have different data terms, controls, and access.
2. **Use only the information required for the task.** Follow data classification, confidentiality, retention, and regional requirements.
3. **Respect source permissions.** Tool access reflects configured permissions; it does not establish that every downstream use is authorized.
4. **Check cross-system transfers.** Confirm that copying, uploading, connecting, or exporting information from one platform to another is permitted.
5. **Name the required sources.** Ask the tool to identify missing, conflicting, inaccessible, or outdated material.
6. **Verify before use.** Check important facts, citations, names, dates, numbers, formulas, recommendations, and generated files.
7. **Keep consequential actions behind approval.** As an organizational practice, require review of messages, publications, transactions, external updates, and decisions affecting people before execution.
8. **Protect credentials and restricted information.** Never place passwords, secrets, access tokens, or prohibited data in a prompt.
9. **Record corrections.** Repeated corrections belong in a template, prompt, Skill, agent instruction, or review checklist.
10. **Measure a real result.** Usage and prompt volume show adoption. A value claim needs a baseline, denominator, owner, period, evidence date, and stated value stage.

OpenAI states that Business, Enterprise, and Edu workspace data is encrypted in transit and at rest and is not used to train OpenAI models by default. For Microsoft Copilot used with an organization’s Microsoft Entra account and applicable enterprise protections, Microsoft states that prompts, responses, and data accessed through Microsoft Graph are not used to train its foundation models. These commitments do not replace organizational data-handling rules or the controls of connected services. See [ChatGPT Work cloud security](https://learn.chatgpt.com/docs/enterprise/chatgpt-work-cloud-security) and [Microsoft Copilot data, privacy, and security](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-privacy).

## Current use cases

The following examples reflect currently documented product capabilities. Availability still depends on the organization’s licenses, configuration, connections, and policies.

| Task | Microsoft Copilot first | ChatGPT Enterprise first | Combined approach |
|---|---|---|---|
| Catch up on communications | Summarize a permitted Teams meeting or Outlook thread | Analyze an approved export across multiple conversations or files | Copilot extracts source-grounded updates; ChatGPT prepares an approved briefing |
| Draft in an office application | Draft or revise in Word, PowerPoint, Outlook, or another supported application | Create a new document, presentation, spreadsheet, or PDF from supplied sources | ChatGPT prepares the artifact; Microsoft 365 supports final editing and collaboration |
| Analyze a workbook | Work inside the open Excel workbook and ask for formulas, charts, or insights | Compare multiple approved files, clean data, run code, or produce a separate analysis | Copilot works in the workbook; ChatGPT or Codex performs approved cross-file processing and validation |
| Prepare a decision brief | Gather permitted Microsoft 365 context | Compare evidence, identify tradeoffs, and produce a sourced memo | Copilot gathers approved context; ChatGPT drafts the sourced decision brief |
| Create a recurring update | Retrieve current Microsoft 365 updates | Apply a reusable Project, GPT, Skill, or scheduled workflow | Copilot supplies current source material; ChatGPT applies the approved reporting method |
| Complete technical work | Draft supporting documents or summarize project communications | Use Codex for repositories, scripts, tests, validation, and implementation | Codex completes reviewed technical work; Microsoft 365 carries the approved communication and documentation |

For more examples, see the [OpenAI use-case library](https://learn.chatgpt.com/use-cases) and Microsoft’s current [Copilot feature overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-overview).

## How to validate a success story

**Organization-specific success stories: Not provided.** This guide does not convert access, licenses, usage, pilots, generated content, or team enthusiasm into a result claim.

Use the following record before sharing a success story:

| Required field | What to record |
|---|---|
| Business problem | The recurring task or decision that needed improvement |
| Baseline | Time, quality, cost, volume, or outcome before the AI-assisted workflow |
| Tool and workflow | Which tool performed each step and where review occurred |
| Evidence set | The sources, sample, time period, and denominator used |
| Result | The observed difference compared with the baseline |
| Value stage | Reported, estimated, validated, or realized |
| Reviewer effort | Corrections, verification, and rework required |
| Owner | Person accountable for the claim and next decision |
| Evidence date | Date the result was last checked |
| Limits | Conditions, exceptions, or risks that restrict reuse |
| Reusable asset | Approved prompt, template, checklist, Skill, or agent instruction |

Microsoft’s own validation guidance asks users to check the source, verification, context, and resilience of Copilot output before acting. The same discipline is useful for results produced with either tool. See [Validate Copilot output before you act](https://support.microsoft.com/en-us/microsoft-365-copilot/validate-copilot-output).

## Questions on when to use each tool

Ask these questions before choosing:

1. Where does the approved source material currently live?
2. Does the proposed tool have approved access to that source?
3. Which license and features are available to the user?
4. Should the result remain inside a Microsoft 365 application?
5. Does the task require selected sources, a reusable ChatGPT workflow, code, or an artifact produced outside a Microsoft 365 application?
6. Is transferring information between systems permitted?
7. What exact result, audience, and decision are expected?
8. Which facts or actions require a reviewer?
9. How will missing or conflicting evidence be reported?
10. What baseline and evidence would justify repeating or expanding the workflow?

## Challenges or barriers teams may encounter

| Barrier | What it looks like | Practical response |
|---|---|---|
| License or feature mismatch | Two users see different capabilities or source access | Record the license, application, platform, and tenant or workspace setting before troubleshooting |
| Permission and data-quality problems | The tool misses files, returns stale content, or exposes overshared material the user can already access | Correct permissions, ownership, metadata, retention, and source quality before expanding use |
| Unclear tool choice | Teams repeat the same task in both products without a reason | Name the source location, desired output, and specific contribution expected from each tool |
| Weak task definition | The output is generic or solves the wrong problem | State the audience, decision, sources, deliverable, boundaries, and review point |
| Cross-system transfer risk | Users copy material between platforms without checking policy | Add an explicit transfer-approval step and use the minimum amount of information needed |
| Low trust in results | Reviewers cannot trace important claims | Require citations, source lists, uncertainty labels, and a verification pass |
| Prompt duplication | Everyone rewrites the same request and gets inconsistent results | Store approved prompts with an owner, tool, source assumptions, version, and review date |
| Premature automation | A fragile manual process becomes a scheduled or agent-driven process | Complete and review several dependable runs before adding recurrence or actions |
| Activity presented as value | Usage counts or generated outputs are reported as business impact | Compare a defined unit of work with a baseline and label the value stage |
| No feedback owner | Errors recur because corrections are never incorporated | Assign an owner to review corrections and update the reusable asset |

## Best practices and prompts to share across the organization

Share only material that the content owner and organization have authorized for distribution. The repository’s [restricted-use notice](LICENSE.md) continues to apply.

Use a small, governed set of assets:

1. A one-page selection table for Microsoft Copilot, ChatGPT Enterprise, and combined workflows.
2. Two or three approved prompts for each common role or recurring task.
3. A source and transfer checklist for work that crosses systems.
4. A validation prompt that checks citations, assumptions, numbers, missing evidence, and approval points.
5. A success-story record containing the baseline, denominator, owner, period, evidence date, and value stage.
6. A named owner and review date for every shared prompt, agent, GPT, Skill, or template.

### Reusable prompt card

```text
Tool:
[Microsoft Copilot, ChatGPT Enterprise, or both]

Goal:
[What should be completed?]

Audience and decision:
[Who will use the result, and what should it help them decide or do?]

Approved sources:
[Name the files, meetings, messages, sites, or data.]

Expected output:
[Format, length, sections, and level of detail.]

Boundaries:
[What must remain unchanged? What data or actions are prohibited?]

Review point:
[What must a person verify or approve?]

Source and transfer check:
[Where does the source live, and is movement between systems approved?]
```

## Suggested team discussion

Use a 45-minute session to convert the comparison into working agreements:

1. **Five minutes:** List the recurring work people are already trying in each tool.
2. **Ten minutes:** Select two tasks that fit Microsoft Copilot, two that fit ChatGPT Enterprise, and one that may use both.
3. **Ten minutes:** Identify access, source, permission, transfer, review, and measurement barriers.
4. **Ten minutes:** Review the strongest prompts and corrections already available.
5. **Ten minutes:** Assign an owner, next test, evidence requirement, and review date for each selected task.

The session should produce a short task register, approved prompt cards, named owners, and a date to review evidence. Keep reported, estimated, validated, and realized results separate.

## Next step

Choose one recurring task and complete the ten-question selection check. Run it in the tool closest to the approved source, record the corrections, and add the second tool only if its contribution and transfer path are explicit.

## Related resources

- [ChatGPT Enterprise and Codex Practical Guide](Practical%20Guide.md)
- [Reusable weekly leadership-update Skill](skills/weekly-leadership-update/SKILL.md)
- [Official sources](SOURCES.md)
