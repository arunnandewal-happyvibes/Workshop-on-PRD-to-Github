# Project Context

## Working Title

Copilot Agentic Tasks

## Product Summary

Microsoft Copilot is evolving from an assistant that answers prompts into an agentic system that can plan and complete multi-step tasks across Microsoft applications. This project explores how to make those capabilities useful enough to earn sustained adoption, while keeping people informed and in control.

The intended experience lets a user describe an outcome in text or voice. Copilot determines the steps, uses the appropriate available capabilities, and returns a useful result with minimal user intervention. It should fit into the user's existing workflow rather than send them to a separate destination.

## Problem

More agentic capability does not automatically create lasting value. Users need to trust that Copilot understands the requested outcome, can make progress across a task, and can recover gracefully when something goes wrong. Measuring usage alone could reward experimentation without proving that tasks were completed successfully.

## Product Goals

- Increase the number of tasks completed by Copilot across Microsoft applications.
- Improve task success rate for requests made to Copilot.
- Grow Copilot commercial adoption and month-over-month usage.
- Make common task completion feel outcome-oriented: users say what they need, not how to do it.

## Non-Goals

- Building a standalone application or destination for agentic capabilities.
- Requiring users to leave their current application or workflow to complete a task.
- Focusing on video creation in this project phase.

## Intended User Experience

1. The user submits a desired outcome through text or voice.
2. Copilot plans and performs the necessary steps, asking for user input only when needed.
3. The user can understand progress, review what happened, and recover or retry without losing chat context.
4. The completed result meets the requested outcome with little correction or rework.

## Prioritized Opportunities

| Priority | Opportunity | Reach | Impact | Confidence | Effort |
| --- | --- | --- | --- | --- | --- |
| P0 | Say what, not how: infer and execute the steps behind a requested outcome. | Medium | High | Medium | Medium |
| P1 | Connector, browser, and computer execution: use the best available access path, including when a native integration is unavailable. | High | High | High | Medium |
| P2 | Long-running work with state: maintain context and return with an outcome for complex tasks over time. | Medium | Medium | High | High |

## Success Measures

- **North star:** month-over-month growth in Copilot commercial adoption and usage.
- **Leading indicators:** number of adoptions and tasks per user.
- **Counter metrics:** task drop rate, day-30 inactivation rate, and the share of agentic tasks requiring substantial user intervention before completion.
- **Quality signal:** task success rate and the amount of correction or rework needed.

## Product Requirements

- Accept task requests through text or voice.
- Autonomously plan and execute the required steps while minimizing user intervention.
- Complete simple tasks within 45 seconds.
- For long-running tasks, provide progress updates and an estimated completion time.
- Let users recover, restore, and retrigger chats without losing context.
- Protect user data with encryption in transit and at rest, and restrict access to authorized users and services.
- Provide a clear, recoverable execution log. Explain actions and decisions in user-facing terms; do not expose private internal reasoning.
- Aim to complete actions within three to four prompt interactions.

## Prototype Materials

The repository includes eight standalone screen concepts with PNG previews: four desktop screens and four mobile screens covering task entry, delegation, live execution, and completed work. Open the portfolio gallery in [index.html](index.html) to browse them. The supplied screens are visual prototypes, not a connected product implementation.

The PRD references [Google Stitch](https://stitch.withgoogle.com/) as a mockup tool. The included prototype artifacts are provided as HTML and PNG files.

## Assumptions and Open Questions

- This repository is an independent portfolio exploration of the product direction, not an official Microsoft product implementation.
- The target user segments, supported applications, task taxonomy, and initial pilot scenario still need definition; the sample screens use illustrative enterprise scenarios.
- Technical architecture, model and tool access, authorization boundaries, and supported execution paths have not been specified.
- The success-rate definition, measurement instrumentation, and baseline values need to be agreed before evaluating outcomes.
- The approval model for consequential actions and the precise meaning of "substantial user intervention" need validation.
- The included HTML screens depend on external font and Tailwind CDN resources and do not connect to Microsoft services or perform real tasks.