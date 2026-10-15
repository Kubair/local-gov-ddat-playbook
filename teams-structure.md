# DDaT Programme - MS Teams Structure

**Local Council Digital, Data and Technology Programme**
October 2026

---

## Purpose

Most DDaT teams in local councils are not short of communication. They are short of the right communication landing in the right place.

This document defines an MS Teams structure designed for a multi-lane DDaT programme operating a use case pipeline from idea through to live service. It exists so that teams can communicate at the right level, with the right people, without duplicating information or burying decisions in email chains that half the team never sees.

The structure is built around four programme layers: Programme Leadership, Transformation Delivery, Platform Delivery, and Comms & Change Enablement. Each layer has its own Team. Each Team has named channels with a specific job. The goal is not more communication -- it is better-placed communication, so the team spends time moving use cases forward rather than working out where things stand.

This file is a reference point for anyone setting up, joining, or maintaining the Teams environment. It covers channel descriptions, membership by role, and welcome messages ready to post on day one.

---

## What problem this solves

In a typical council DDaT programme, coordination breaks down in predictable ways:

- Stand-ups become management check-ins rather than blockers boards
- Decisions get made in meetings that clashed with something else and never get written down
- BAs work in parallel across directorates with no shared operating space
- Platform and transformation lanes talk past each other at the handoff point
- Comms and change functions sit outside the delivery horizon until it is too late

This structure makes those seams visible and gives each one a named place to resolve.

---

## Structure overview

| Layer | Team name | Purpose |
|---|---|---|
| 1 - Programme leadership | DDaT Programme Core | Governance, decisions, cross-programme visibility |
| 2 - Transformation delivery | DDaT Transformation Delivery | Use case pipeline, BA domain work, sprint ceremonies |
| 2 - Cross-lane seam | Delivery Coordination (private channel) | Step 3 handoff between transformation and platform lanes |
| 3 - Platform delivery | Platform Delivery | Engineering, cloud, data, infrastructure |
| 4 - Comms & change | Comms & Change Enablement | Adoption, communications, L&D, HR coordination |

---

## Layer 1 - Programme leadership

### Team: DDaT Programme Core

**Description:**
Programme-level space for governance, decisions, and cross-programme visibility. Low volume, high signal. Not a working space -- a record of what has been decided and what is moving.

**Membership:**
Programme Director, DDaT Delivery Lead, Platform Delivery Lead, Head of Transformation, Head of Digital, Programme Manager, Senior Responsible Owner

**Channels:**

| Channel | Purpose |
|---|---|
| `General` | Announcements only. One post per sprint. No chat. |
| `Programme governance` | Risks, decisions log, reporting packs. Source of record for board updates. |
| `Sprint rhythm` | Fortnightly ceremony calendar. Automated sprint start/end posts via Power Automate. |
| `What is moving` | Async sprint progress summaries. Replaces slide decks and management check-in stand-ups. |
| `Stakeholder comms` | Outward narrative and council-wide messaging. Programme Director-owned. |

---

## Layer 2 - Transformation delivery

### Team: DDaT Transformation Delivery

**Description:**
Home base for the transformation lane -- use case pipeline, BA domain work, sprint ceremonies, and ways of working. If it is about moving a use case from idea to ready-for-build, it lives here.

**Membership:**
DDaT Delivery Lead, Head of Transformation, Programme Manager, Delivery Manager, BA cohort (one BA per directorate: e.g. Adults & Health, Housing, Children's, Resources, SCRER)

**Channels:**

| Channel | Purpose |
|---|---|
| `General - team comms, ways of working` | Team updates and announcements. If you are not sure where something goes, start here. |
| `BAs Huddle` | BA cohort space. Sharing context across domains, sense-checking, practical coordination. |
| `Use Case Pipeline` | Step tracking (Steps 0-5), triage log, weekly digest of pipeline movement. |
| `Refinement Corner` | Working space for use case refinement before Step 3 handoff. |
| `Sprint-events` | Planning artefacts, review notes, retro SMART experiments and actions. The retrospective is the named place for what is not working -- if it does not go here, it does not get fixed. |
| `Delivery Coordination` | Private channel. Cross-lane coordination between transformation and platform leads. Step 3 readiness and blockers. |
| `Ways of Working` | Guides, Definitions of Done, facilitation reference. Pinned, not discussed. |

---

### Channel: BAs Huddle - welcome message

> Welcome to BAs Huddle
>
> This channel belongs to the BA cohort. It is your space to stay connected across directorates, share what you are working through, and ask questions without them getting lost in the wider team feed.
>
> **What this channel is for**
>
> - Sharing context across domains -- if something you have found in Adults & Health or Housing is likely to affect another directorate, this is where you flag it
> - Questions about the pipeline -- if you are unsure which step a use case is at, or what is needed to move it forward, ask here
> - Sense-checking with each other before something goes into the wider team or gets escalated
> - Practical coordination -- who is doing what, who needs cover, what is blocking progress
> - Anything you would normally put in an email to the group
>
> **What it is not for**
>
> - Formal pipeline updates -- those go in Use Case Pipeline so the whole team has visibility
> - Sprint artefacts or ceremony notes -- those live in Sprint-events
> - Ways of working questions -- check Ways of Working first; if the answer is not there, ask here and we will make sure it gets added
>
> You are working across some of the most complex parts of this programme. Adults & Health, Housing, Children's, Resources -- these directorates do not always talk to each other, but you do. Use this space to make that connection visible.
>
> *DDaT Delivery Lead*

---

### Channel: Delivery Coordination - purpose note

This channel is private within the Transformation Delivery Team. It is the named seam between the transformation lane and the platform lane. Conversations about decomposition and cross-lane dependencies happen here, not in either lane's own channels.

It exists because the Step 3 handoff -- where a use case moves from transformation-ready to platform-ready -- is the point where programmes most commonly lose time. A dedicated channel with the right people in it means that loss is visible before it becomes a delay.

**Members:** DDaT Delivery Lead, Platform Delivery Lead, Solution Architect, Programme Manager, Platform Engineer Lead

---

### Team: DDaT Transformation Delivery - welcome message

> Welcome to DDaT Transformation Delivery
>
> This is our permanent home for the transformation lane -- the place where use cases move from idea to ready-for-build, and where the team stays connected between ceremonies.
>
> Having a dedicated space here means we are not relying on email threads, forwarded messages, or trying to remember what was said in a meeting three weeks ago. Everything lives in one place, and anyone joining the team can get up to speed without having to ask.
>
> **How this space is set up**
>
> - **General** -- Team comms and ways of working updates. Home base for the transformation lane.
> - **BAs Huddle** -- A dedicated space for the BA cohort to share context, flag questions, and work through anything domain-specific.
> - **Use Case Pipeline** -- Where we track movement through the six-step pipeline. When a use case moves from one step to the next, a note goes here.
> - **Refinement Corner** -- Working space for use case refinement before Step 3 handoff.
> - **Sprint-events** -- Planning artefacts, review notes, and actions from retrospectives.
> - **Delivery Coordination** -- Private channel for cross-lane coordination. Step 3 conversations happen here.
> - **Ways of Working** -- Our guides, Definitions of Done, facilitation reference. Pinned here so they are always findable.
>
> **Why this works better**
>
> Most teams lose time not because the work is hard, but because the coordination is fragmented -- decisions made in emails that BAs never saw, updates shared in meetings that clashed with something else, questions asked and answered three times over because there was no shared record.
>
> This space changes that. Updates land once. Everyone sees the same thing. And when something needs a conversation, we can have it in the right channel rather than chasing it across inboxes.
>
> If anything about this setup does not work for how you are operating, say so in General. This space should serve the team -- so let us shape it together as we go.
>
> *DDaT Delivery Lead*

---

## Layer 3 - Platform delivery

### Team: Platform Delivery

**Description:**
The platform lane. Transformation Delivery has a member here for visibility, not direction. Step 3 conversations happen in Delivery Coordination, not here.

**Membership:**
Platform Delivery Lead, Data Engineers, Cloud/AI Engineers, BI Analysts, Data Scientist, M365/Power Platform Engineers, Data/AI Solution Architect, Quality Analyst, UI Designer, Infrastructure/DevOps Engineer

**Channels:**

| Channel | Purpose |
|---|---|
| `Data platform engineering` | Data engineering workstream -- ingestion, pipelines, storage. |
| `Cloud platform AI` | Cloud infrastructure, AI/ML tooling, BI and data science. |
| `MS365 Power Platform` | M365 tooling, Power Platform development and governance. |
| `Architecture design quality` | Solution architecture, quality assurance, UI/UX design. |
| `Infrastructure DevOps` | Platform infrastructure, DevOps, environment management. |

---

## Layer 4 - Comms & change enablement

### Team: Comms & Change Enablement

**Description:**
The team that makes adoption visible. Connects delivery outputs to communication, change readiness, learning, and workforce impact. This Team should be created at programme start, not at go-live -- if it does not exist until the product is ready, it is already too late.

**Status:** Create skeleton at programme start with available members. Add functional leads as confirmed.

**Membership (by role):**
Corporate Comms Lead, Change Manager, Service Comms Lead (TBC), L&D Lead (TBC), HR Coordination Lead (TBC)

**Channels:**

| Channel | Purpose |
|---|---|
| `General` | Owned by DDaT Delivery Lead until functional leads are confirmed and onboarded. |
| `Corporate comms` | Programme narrative and council-wide story. |
| `Service comms` | Per-service release communications. |
| `Change management` | Use case change readiness -- impact assessments, change plans, readiness gates. |
| `Learning and development` | Training readiness and L&D planning per release. |
| `HR coordination` | Role impact and job design downstream of delivery. |
| `Release comms log` | Shared record of what has been communicated, when, and to whom. |

---

### Team: Comms & Change Enablement - welcome message

> Welcome to Comms & Change Enablement
>
> This Team exists because adoption is not a go-live problem. It is a delivery problem, and it belongs inside the delivery horizon -- not waiting at the end of it.
>
> The DDaT programme is producing change. Real change: services redesigned, workflows replaced, roles shifted. None of that lands without communication, without people being prepared for it, and without someone thinking about the workforce implications before they become complaints. That is what this Team is for.
>
> **How this space is set up**
>
> - **General** -- Owned by DDaT Delivery Lead until functional leads are confirmed and onboarded. Start here.
> - **Corporate comms** -- The programme narrative. Council-wide story about what this transformation means and why it is happening.
> - **Service comms** -- Per-service release communications. Drafted here, agreed with the service, and sent.
> - **Change management** -- Use case change readiness: impact assessments, change plans, readiness gates before a use case goes live.
> - **Learning and development** -- Training readiness per release. If a service is changing, someone needs to know how to use what replaces it.
> - **HR coordination** -- Role impact and job design. The downstream effects of delivery that HR needs to plan for.
> - **Release comms log** -- Shared record of what has been communicated, when, and to whom. Stops the same message going twice, and means nothing gets missed.
>
> **Why this has to start now**
>
> Most comms and change functions get stood up when a product is nearly ready. By then, the decisions have been made, the service design is fixed, and comms is in the position of packaging something it had no input into. That is not how this programme runs.
>
> If you have landed here and your function's channels are not fully staffed yet -- that is expected. Use General, flag what you need, and we will build the rest as the team arrives.
>
> *DDaT Delivery Lead*

---

> This Team makes the adoption gap structurally visible. Creating it at programme start is the argument that change management belongs inside the delivery horizon -- not after it.

---

## Programme leadership channel

Within the DDaT Transformation Delivery Team there is a private channel for programme leadership only.

**Channel name:** `Programme LT`

**Description:**
Private space for programme leadership. For decisions, escalations, and cross-lane conversations that need senior visibility before they go wider.

**Members:** Senior Responsible Owner, Programme Director, DDaT Delivery Lead, Platform Delivery Lead, Head of Transformation, Programme Manager

### Welcome message

> Welcome to Programme LT
>
> This is our private space. It sits alongside the wider team channels but it is not a leadership version of General. It has a specific job.
>
> **What this channel is for**
>
> - Decisions that need senior sign-off before they go wider
> - Risks or blockers that have cross-lane impact and need more than one of us to resolve
> - Anything that should land with the LT first -- before it reaches the full team or external stakeholders
> - Sense-checking between us when the right next step is not obvious
>
> **What it is not for**
>
> - Day-to-day programme updates -- those live in General and Use Case Pipeline
> - Sprint ceremony content -- that is in Sprint-events
> - Cross-lane coordination between transformation and platform leads -- that is Delivery Coordination
>
> If something belongs here, post it here. If it does not, post it in the right place so the rest of the team has visibility too. The goal is that this channel stays low volume and high signal -- easy to check, easy to act on.
>
> *DDaT Delivery Lead*

---

## Conventions

**Async first.** Post updates as they happen; do not hold them for the next meeting.

**Right channel, right level.** A question in the wrong channel is information the wrong people see and the right people miss.

**Pin, do not repeat.** Reference documents, ways of working guides, and standing instructions go pinned at the top of the relevant channel. They are not re-posted each sprint.

**Sprint rhythm.** A Power Automate post marks sprint start and end in `Sprint rhythm` (Programme Core). All teams operate to the same sprint boundary.

---

## Using this structure

This file is designed to be adapted. The layer names, channel names, and welcome messages are a starting point -- the underlying principle is that every channel has a named job and a named audience, and the two should match.

If you are setting up a DDaT programme Teams environment from scratch, the fastest path is:

1. Create the Teams in the order listed -- Programme Core first, then Transformation Delivery, then the others as they become relevant
2. Copy the channel descriptions and welcome messages directly; edit role names to match your team
3. Pin your ways of working documents in the relevant channels before you invite anyone
4. Post welcome messages before the first ceremonies -- channel discipline is much easier to establish early than to retrofit

Common mistakes: creating too many channels before the team exists to fill them; using General as a catch-all until it becomes unreadable; leaving Comms & Change Enablement until near go-live.

---

*Authored by Kubair Shirazee*
*Digital, Data and Technology Delivery Lead*

*Feedback welcome -- raise an issue or open a pull request.*
