# Ethos

The principles that guide what we capture and how.

---

## The Purpose

This knowledge base exists to answer: **How does New Zealand Blood Service work?**

Not just the technical systems — the whole thing. How the systems fit together. How the suppliers works. Who the customers are. Why decisions were made.

The goal is informed decisions at every level. Iterating on ideas. Uunderstanding the blast radius of changes. Medical servies dynamics. Strategy seeing the full picture. New hires getting up to speed. Key people leaving without knowledge leaving.

Consumption is through AI agents. The knowledge here is structured for retrieval and reasoning, not for humans to browse files directly.

---

## The Hard Rules

These are non-negotiable. Violating them poisons the knowledge base.

### Capsule: VerifiedOnly

**Invariant**
Only record what you can verify. Wrong information is worse than missing information.

**Example**
Observed in operating manuals: high confidence. Stated in docs: medium confidence. Inferred from patterns: mark as low confidence.
//BOUNDARY: If you cannot verify it, omit it.

**Depth**
- Hierarchy: 📄 Manuals > 📚 Docs > 🧠 Synthesis > 👤 Expert > 💭 Intuition
- Wrong information causes bad decisions, wasted effort, broken trust
- Missing information prompts research; wrong information prevents it

---

### Capsule: OmitWhenUncertain

**Invariant**
When in doubt, leave it out. Missing is recoverable; wrong is destructive.

**Example**
Uncertain about a service's purpose? Write "see xyz" rather than guess.
//BOUNDARY: Do not fill gaps with plausible-sounding fabrication.

**Depth**
- Gaps invite questions; errors invite confidence in wrong answers
- Better to say nothing than to say something false
- Mark uncertainty explicitly when you must include unverified information

---

## The Guidance

Follow these unless you have good reason not to.

### Capsule: TemporalStability

**Invariant**
Capture what will still be true in six months. Avoid ephemeral details.

**Example**
Good: "Foundation services are single points of failure."
Bad: "We have 47 services" or "Planned for Q3."

**Depth**
- Patterns persist; counts change
- Constraints persist; configurations change
- Principles persist; implementations change
- Test: will this still be true? If not, is it worth the maintenance cost?

---

### Capsule: ShapeNotDetail

**Invariant**
Document conceptual structure, not implementation specifics. Point to details; do not duplicate them.

**Example**
Good: "Community Service does x from multiple sources."
Bad: "The xyz does x

**Depth**
- Implementation changes; conceptual structure persists
- Duplication creates maintenance burden and divergence risk
- This knowledge base is a map; repositories contain the territory

---

### Capsule: WhyNotWhat

**Invariant**
Capture why things work this way. The what becomes obvious once you understand why.

**Example**
Good: "Service requires thing because one process serves all x."
Bad: "Add techincial detail here."

**Depth**
- Why teaches principles; what teaches steps
- Principles transfer to new situations; steps do not
- Understanding why enables better decisions than knowing what

---

### Capsule: PatternsNotInstances

**Invariant**
Document patterns, not exhaustive lists. Lists rot; patterns endure.

**Example**
Good: "."
Bad: "."

**Depth**
- Patterns are stable; instance lists go stale immediately
- A pattern teaches recognition; a list teaches memorization
- When you need a list, put it in reference material that gets maintained

---

## The Values

### Capsule: BridgingSilos

**Invariant**
Connect knowledge across professional boundaries. Dissolve the walls between disciplines.

**Example**
Medical knows prodcut. Delivery knows customers. Services knows market. This knowledge base makes all of it available to all of them.

**Depth**
- Traditional silos: each profession knows their domain, not others
- Opportunity cost: decisions made without full context
- The Rosetta Stone translates between vocabularies and worldviews
- An agent with this knowledge can reason across boundaries

---

### Capsule: TrailsNotDestinations

**Invariant**
Point to detailed information; do not duplicate it. This is a map, not a transcript.

**Example**
Good: "For system flow details, see xyz.md"
Bad: Copying the payment flow documentation here

**Depth**
- Duplication creates two sources of truth that diverge
- Maintenance burden grows with duplication
- The map shows where things are; the territory contains the details

---

### Capsule: NonObviousTruths

**Invariant**
Capture what surprises people, wastes time when misunderstood, or explains why things are the way they are.

**Example**
- Saturday is 2x weekday traffic (architectural significance)

**Depth**
- Obvious truths do not need documentation
- Non-obvious truths burn people who do not know them
- Domain complexity deserves explanation; technical debt does not

---

## Success

After engaging with this knowledge base through an agent, someone should be able to:

- Understand what a system does and why it exists
- Know where new functionality belongs
- Predict blast radius of changes
- Make informed product decisions
- Understand competitive positioning
- Navigate denomination dynamics
- Investigate production issues with full context

The test: can they make good decisions without finding the right person to ask?

---

## Failure

- **False confidence** — wrong information leading to bad decisions
- **Maintenance burden** — information that rots faster than it's updated
- **Duplication divergence** — copies that contradict each other
- **Perpetuated silos** — knowledge still trapped in professional boundaries

---

## Hierarchy

1. **Hard Rules** — never violate
2. **Guidance** — follow unless you have good reason
3. **Values** — understand why we make these choices