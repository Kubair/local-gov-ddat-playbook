# Sprint planning guide

**DDaT Ways of Working series**

---

## Why this exists

Sprint planning fails in two predictable ways in council DDaT programmes: the team pulls more than it can close, and blockers that were visible before the meeting are not resolved before the sprint starts.

The first failure produces a sprint that looks full and delivers little -- stories carry forward, capacity is invisible, and the pattern repeats. The second means the team starts a sprint already stalled, waiting for decisions that should have been made in the week before.

This guide fixes both. It separates the preparation from the meeting, and it makes the sprint goal concrete enough to evaluate at the end.

---

## Before the planning meeting

Sprint planning is the last step of a preparation sequence, not the first. Most of the work happens in the days before it.

**1 -- Pull a planning candidates list from the pipeline**

The Delivery Lead prepares a planning candidates document before the meeting. BAs contribute to it -- they are the ones who know which use cases are genuinely ready and which ones only look ready from the pipeline view. The document does not commit to anything yet -- it organises the information the team needs to make good decisions. The document covers:

- Confirmed commitments: anything stated at the last review. The team and stakeholders have heard these. They are the fixed point the plan builds around.
- Pipeline candidates by tier: what is close to ready, what needs one more step, what is not ready to pull.
- Carry-forwards: stories that started last sprint and are still open. Name the reason. If it has carried more than twice, that is the first thing to address.
- Do Not Pull list: use cases with unresolved blockers, external dependencies, or incomplete triage. Name the reason. This is not a failure list -- it is a capacity protection decision.
- Active blockers entering the sprint: who owns each one and what the resolution path is.

**2 -- Resolve blockers before the meeting**

Any blocker on the list needs a resolution path confirmed before the planning meeting opens. A blocker with no owner and no next step will not resolve itself during the sprint.

If a blocker cannot be resolved before planning, the use case does not enter the sprint. It stays on the Do Not Pull list with a named condition for re-entry.

**3 -- Capacity baseline**

Before the meeting, each team member states their available days for the sprint. Factor in: known leave, ceremonies, cross-programme commitments, and anything from the last retro that affects pace.

The capacity baseline is not an exact estimate. It is a check: how many stories is this team realistically able to close? That number sets the ceiling for what gets pulled.

*A sprint that pulled 42 stories and closed 5 is not a sprint -- it is a backlog with a deadline attached.*

---

## The planning meeting

**Duration:** 60 -- 90 minutes. Not longer.

**Who runs it:** Delivery Lead prepares; the team decides together what goes in.

**Who attends:** Full delivery team. Platform lead or solution architect where cross-lane stories are in scope.

---

### Step 1 -- Sprint goal: what does this sprint need to prove? (10 minutes)

Before pulling a single story, the team agrees what the sprint is for. Two or three outcomes that, if achieved, would make the sprint a clear success -- regardless of how many other stories moved. Write them down. Post them in the team channel.

The sprint goal is the filter. Everything pulled in Steps 2 -- 4 is tested against it: does this story serve the sprint goal? If the answer is no, it either waits or goes on the candidates list for next sprint.

*Watch: a sprint goal that is a list of stories is not a sprint goal. The sprint goal is the reason the plan exists -- not the plan itself.*

---

### Step 2 -- Confirmed commitments (10 minutes)

Open with the confirmed commitments from the last review. These are not up for debate -- they are already public. The team confirms each one is still achievable and names any conditions that have changed since the review.

If a confirmed commitment has become unachievable, say so now. Do not carry it silently into the sprint.

---

### Step 2 -- Carry-forwards (10 minutes)

Review any stories that are carrying forward from the previous sprint.

- What stopped them closing?
- Is the blocker resolved?
- If they carry a second time, is there a real path to closing them this sprint?

A story that has carried twice without a resolution path should be removed from active work and treated as a new story at the right point, not carried indefinitely.

---

### Step 3 -- Carry-forwards (10 minutes)

Review any stories carrying forward from the previous sprint.

- What stopped them closing?
- Is the blocker resolved?
- If they carry a second time, is there a real path to closing them this sprint?

A story that has carried twice without a resolution path should be removed from active work and treated as a new story at the right point, not carried indefinitely.

---

### Step 4 -- Pull from candidates (30 -- 40 minutes)

Work through the tiers in the candidates document. For each story the team is considering pulling:

- Is the BA who owns it present and available this sprint?
- Is the use case triage complete? Is it in the right step for BA work to start?
- Is there a blocker that is not yet resolved?
- Does pulling it serve the sprint goal -- or does it just fill the board?

Apply one discipline throughout: **pull to close, not pull to start.** A story that enters the sprint should have a realistic path to Done within the sprint timebox. If it does not, leave it on the candidates list.

*Watch: the planning meeting is not the place to discover that a use case was never triaged, or that the BA contact has not been confirmed. Those are pre-planning failures.*

---

### Step 5 -- CI experiments from the last retro (10 minutes)

Retro improvement experiments are first-class sprint work. Each one confirmed at the last retro goes on the board as a story. Name the owner and confirm the target date.

If a retro experiment from a previous sprint did not close, treat it the same as any carry-forward: name why, and decide whether it enters this sprint.

---

### Step 6 -- Active blockers register

Confirm the blockers entering the sprint, the owner for each, and the condition for resolution. Post this in the team channel alongside the sprint goal.

---

## Rules

**Do:**
- Prepare the candidates document before the meeting. The meeting decides -- it does not discover.
- Name a capacity ceiling and stay inside it.
- State the sprint goal in two or three concrete outcomes.
- Pull the Do Not Pull list explicitly -- name what is not coming in and why.

**Do not:**
- Pull stories with unresolved blockers. Name them, park them, resolve them before they enter.
- Pull to show activity. A full board is not the same as a productive sprint.
- Leave the meeting without a named sprint goal.

---

## Healthy signals

- The candidates document exists before the meeting starts.
- Capacity is named and the pull reflects it.
- The Do Not Pull list is longer than it feels comfortable to admit.
- The sprint goal fits in two sentences.
- The team can say, at the end of the sprint, whether they hit it.

**Watch:**
- Confirmed commitments from the last review that quietly dropped without being named. That is a trust problem.
- Stories carrying for a third sprint. That is a backlog problem wearing a sprint problem's clothes.
- A sprint goal that is a list of stories. The sprint goal is not the sprint plan -- it is the reason the plan exists.

---

*Authored by Kubair Shirazee*
*Digital, Data and Technology Delivery Lead*

*Part of the DDaT Ways of Working series. Feedback welcome -- raise an issue or open a pull request.*
