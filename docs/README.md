# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management docs hub. This folder contains the processes, templates, and guidance the team uses to plan, deliver, and iterate on work. The documentation emphasizes clear ownership, measurable outcomes, and repeatable artifacts so new teammates and stakeholders can quickly understand how projects are run and how decisions are tracked.

OctoAcme follows a five-stage project lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Work starts with a Project One-pager to capture the problem, goal, success metrics, stakeholders, timeline, and initial risks. Approved initiatives move into planning where the team breaks work into shippable increments, defines acceptance criteria, and maps milestones. During execution the team uses a prioritized backlog and a project board (Backlog → Ready → In Progress → In Review → QA → Done), enforces small PRs with CI checks, and follows a defined escalation path for blockers. Releases follow a checklist-driven approach (pre-release checks, staging verification, production deploy, post-deploy validation) and include rollback plans for incidents. After delivery, retrospectives capture learnings and convert them into tracked action items.

Key workflows and practices:
- Backlog and Delivery: Prioritized backlog items with acceptance criteria, timeboxed sprint/iteration planning, and Definition of Done enforced before pulling work into a sprint.
- Pull Request & Code Quality: Small PRs when possible, include issue link and acceptance criteria, run automated tests, linting, and security scans in CI before requesting review.
- Roles & Communication: Clear roles (Project Manager, Product Manager, Developers, QA) and a communication cadence of daily standups, weekly delivery syncs, PM/PdM alignments, and monthly stakeholder updates. Escalation path: Team → PM → Product Lead → Sponsor.
- Quality & Risk: Unit/integration tests, smoke tests for critical flows, manual QA when needed, and a Risk Register capturing impact, likelihood, owner, and mitigation. Retrospectives prioritize 2–3 action items and feed improvements back into the backlog.

Quick start
1. New to OctoAcme? Start with the Project Management Overview.
2. Starting a new project? Complete the Project One-pager in the Initiation guide.
3. In planning? Use the Project Planning doc for backlog, estimates, and release planning.
4. In execution? Follow the Execution & Tracking doc for day-to-day workflows and PR guidelines.
5. Preparing a release? See Release & Deployment for pre-release checks and rollback guidance.
6. After delivery? Run a Retrospective and track action items.

Core process documents in this folder:
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

How to use these docs
- New team members: Read the Overview and Roles & Personas first.
- Project leads: Keep the Project One-pager and Risk Register up to date in the project repo.
- Everyone: Add updates or improvement suggestions via the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE.
