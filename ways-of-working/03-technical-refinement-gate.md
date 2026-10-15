# Use case discovery: technical refinement gate

**DDaT Ways of Working series**

---

## Why this exists

**The friction:** Solution Architect time is frequently wasted when BAs request technical input without sufficient preparation -- vague asks, folder dumps, and under-structured tickets that produce low-value conversations regardless of when they happen.

**The principle:** This gate fixes signal quality, not engagement timing. The BA structures the request to a clear standard before any conversation is requested. If the Solution Architect can add value earlier in discovery and the signals are ready, earlier is not a problem. The gate prevents wasted conversations, not early ones.

**The outcome:** With a clear, focused problem statement in hand, the Solution Architect can bring their full perspective -- exploring what is possible and how it might be achieved -- without time being lost to under-prepared conversations.

---

## The four-step workflow

**1 -- ADO baseline**
The BA ensures the ADO Epic satisfies the Definition of Ready (DoR). Update an existing Epic to the standard, or create a new one from the Epic template.

**2 -- Formal request**
The BA sends a structured Teams message to the Solution Architect, @mentioning the Delivery Lead and Platform Lead, with a direct link to the ADO Epic.

**3 -- Signal triage**
The Solution Architect spends a maximum of 5 minutes assessing whether the problem statement in the ADO ticket is clear and focused enough to make the conversation valuable.

Before reading the full DoR, one fast-fail question: *"Can I state the problem this BA is trying to solve in one sentence?"* If not, the DoR is not ready and the ticket goes back with that question as the note. This takes 30 seconds and protects the full 5 minutes for work that is close.

**4 -- The gate verdict**
- Ready: Solution Architect books the conversation.
- Not yet: Problem statement returned with clear notes on what to sharpen.

---

## Definition of Ready (DoR)

Before completing the DoR sections, establish which path applies:

**Existing use case:** Your existing Analysis User Stories should already contain this data -- the DoR is a pre-flight check, not a prompt to create something new.

**New use case:** Create a new Epic from the Epic template, add an Analysis Feature, then create an Analysis User Story and complete the five DoR sections on it.

---

### Business context and value
A clear, 2-3 sentence distillation explaining why this use case is being progressed now and the immediate business value of doing so.

### The specific ask for the Solution Architect
An unambiguous, localised question or validation requirement. Avoid generic phrases like "look at this use case." Use scoped definitions.

### Curated key signals -- no document dumps
Isolate exact data streams -- no generic folder links. Name the document and state the specific line, row, or schema block to read. No commentary required beyond that.

### System dependencies
A definitive mapping of upstream and downstream architecture constraints involved.

### Known unknowns and assumptions
Flag what is unclear, what has been assumed, and where the BA needs the Solution Architect's input most.

---

## The peer contract

The BA commits to structured, signal-quality requests.

The Solution Architect commits to a 5-minute triage and a clear, reasoned verdict: either booking the conversation or returning the ticket with specific notes.

Neither side lets the conversation happen without the standard being met.

---

*Authored by Kubair Shirazee*
*Digital, Data and Technology Delivery Lead*

*Part of the DDaT Ways of Working series. Feedback welcome -- raise an issue or open a pull request.*
