<div align="center">

# Copilot, Past the Prompt

### An exploration of work that starts with the outcome, not the instructions.

Eight desktop and mobile concepts for delegating a task, following its progress, and reviewing the finished work.

[Open the portfolio](https://arunnandewal-happyvibes.github.io/Workshop-on-PRD-to-Github/) · [Browse the screens](index.html#prototypes) · [Read the product context](context.md)

</div>

<div align="center">

| Desktop workspace | Mobile live task |
|:---:|:---:|
| ![Copilot desktop workspace home](Prototype%20Screens/Website%20screens/Website%20Screens/copilot_workspace_home/screen.png) | ![Copilot mobile live task](Prototype%20Screens/Mobile/Mobile%20Screens/copilot_mobile_live_task/screen.png) |

</div>

> **Independent portfolio concept.** Based on the included PRD; not affiliated with, endorsed by, or an official Microsoft product. Screens are static prototypes and do not connect to Microsoft services or execute real tasks.

## The Idea

Agentic capability matters when it helps people finish meaningful work, not just when usage increases. This project explores a Copilot experience where people describe an outcome, see useful progress, and can review or recover work in their existing workflow.

| Product opportunity | Priority | Exploration |
| --- |:---:| --- |
| Say what, not how | P0 | Turn an outcome into an understandable plan and completed task. |
| Choose an execution path | P1 | Use the best available connector, browser, or computer capability. |
| Continue over time | P2 | Preserve state and explain progress on long-running work. |

## The Flow

| 01 · Start | 02 · Delegate | 03 · Follow | 04 · Review |
| --- | --- | --- | --- |
| Describe the outcome by text or voice. | See how the task is understood and planned. | Follow execution, app handoffs, and status. | Review the result and its activity history. |

The same four states are explored in desktop and mobile layouts. [Open the interactive gallery](https://arunnandewal-happyvibes.github.io/Workshop-on-PRD-to-Github/#prototypes) or launch a prototype directly:

| State | Desktop concept | Mobile concept |
| --- | --- | --- |
| Start | [Workspace home](Prototype%20Screens/Website%20screens/Website%20Screens/copilot_workspace_home/code.html) | [Mobile home](Prototype%20Screens/Mobile/Mobile%20Screens/copilot_mobile_home/code.html) |
| Delegate | [Task delegation](Prototype%20Screens/Website%20screens/Website%20Screens/task_delegation_plan_understanding/code.html) | [Mobile task delegation](Prototype%20Screens/Mobile/Mobile%20Screens/copilot_mobile_task_delegation/code.html) |
| Follow | [Live execution](Prototype%20Screens/Website%20screens/Website%20Screens/live_agent_execution_q3_review/code.html) | [Mobile live task](Prototype%20Screens/Mobile/Mobile%20Screens/copilot_mobile_live_task/code.html) |
| Review | [Completed work](Prototype%20Screens/Website%20screens/Website%20Screens/completed_work_q3_executive_review/code.html) | [Mobile completed work](Prototype%20Screens/Mobile/Mobile%20Screens/copilot_mobile_completed_work/code.html) |

## Project Notes

- [Product context](context.md): goals, requirements, success measures, and open questions.
- [Project plan](plan.md): a practical path for reviewing and extending the concepts.
- [Portfolio site](index.html): responsive gallery with device filters and screen previews.
- `Prototype Screens/`: supplied standalone HTML concepts and PNG previews.
- `PRD - Sunday Workshop - Copilot v2 for Microsoft.docx`: source requirements.

### Run Locally

No build step or package install is needed. Open `index.html`, or serve the root folder:

```sh
python3 -m http.server 8000
```

Visit `http://localhost:8000`. The standalone prototypes use Google Fonts and the Tailwind CDN, so they need internet access to render as intended.

### Publish the Portfolio

The root `index.html` is ready for GitHub Pages. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/(root)**. Once GitHub finishes deploying, the [live portfolio link](https://arunnandewal-happyvibes.github.io/Workshop-on-PRD-to-Github/) will be available.

### Scope

These are interface concepts, not a working agent. There is no backend, authentication, persistence, analytics, or real Microsoft 365 integration. The sample task data and execution statuses are illustrative.