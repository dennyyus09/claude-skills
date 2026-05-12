---
name: dy-pm-skills
description: "Denny's PM skill suite. Routes to one of two frameworks based on the argument passed. Use 'validation' to stress-test a product problem statement (checks if it's a real human motivation or a dressed-up mechanism). Use 'strategy' to build or evaluate a product strategy using the Positioning-Segmentation-Differentiation framework. Trigger when the user invokes /dy-pm-skills validation or /dy-pm-skills strategy, or when context clearly matches one of the two frameworks."
---

# dy-pm-skills

Denny's PM skill suite. Two frameworks, one skill.

## Routing

Read the argument passed:

- `validation` → run the **Problem Validation** framework below
- `strategy` → run the **PSD Strategy** framework below
- If no argument or ambiguous → ask: "Which framework? `validation` to stress-test a problem statement, `strategy` to build a product strategy."

---

---

# FRAMEWORK 1: Problem Validation (`validation`)

A Socratic stress-test for product problem statements. The goal is not to hand over the answer — it's to ask questions that make the user feel the gap themselves and arrive at the true problem on their own.

**Core principle:** A real problem is felt, not theorized. If a user wouldn't use your words to describe what they're experiencing, you haven't found the problem yet — you've found the mechanism between the problem and the solution.

**Method:** Never state the answer mid-conversation. Ask, listen, probe one level deeper, then confirm what the user has surfaced. People believe answers they arrive at more than answers they're given.

---

## The Three Tests

Run each test as a question directed at the user — not as a verdict you declare.

### Test 1 — The Language Test
> "Would someone say that out loud if they were frustrated or struggling?"

If the problem statement uses words that sound like a pitch deck or a product review, it's a rationalization — not a felt problem. Probe: *"How would a real user describe this if they were venting to a friend?"*

- "I want self-directed access to on-demand content" → probe further
- "I'm bored" → pass

---

### Test 2 — The Body Test
> "What are they actually feeling in that moment — can you name the emotion?"

Real problems live in the body: boredom, anxiety, fear, embarrassment, desperation, restlessness. If the answer is abstract or cognitive, it's still one layer too high. Probe: *"Is it closer to frustration, fear, or something else?"*

---

### Test 3 — The Mechanism Test
> "If this product never existed, would they still have this problem?"

If yes — what you have is a mechanism, not the problem. Probe: *"What were people feeling before this product category existed? What raw need or pain was already there?"*

---

## Two-Layer Demand-Side Probe

After the three tests, always ask:

> "Is this only how they feel when something triggers it — or do they come back even when things are fine? Why?"

Most products have two demand-side layers:
- **Crisis layer** — activates when the problem is acute (job hunting, boredom spike, medical emergency). This is what users would tell you if you asked them why they signed up.
- **Baseline layer** — always-on, keeps engagement between crises (status, validation, FOMO). This is what keeps them coming back when the crisis is gone.

Both layers matter. A product that only solves the crisis layer loses users the moment the crisis passes.

---

## Status and Validation Pattern

If the product has any social or visibility component, probe explicitly:

> "Is part of the value being *seen* by others — knowing that other people can see what you've done or where you are?"

Status and recognition are among the most common masked demand-side problems. They appear in products that look purely functional on the surface: LinkedIn (career progress), Twitter (relevance), YouTube for creators (fame). If this pattern is present, name it — it explains retention and engagement far better than the functional framing.

---

## Conversation Flow

1. Ask the user for their current problem statement — don't assume.
2. Run the three tests as questions. Wait for answers before probing deeper.
3. Run the two-layer probe on demand-side.
4. If the product has social features, run the status probe.
5. Separate demand-side and supply-side — they almost always have different root problems.
6. At the end, synthesize: reflect the user's own words back as the restated problem. Do not introduce new framing at this stage.
7. End with a one-line verdict: real problem or mechanism?

Do not hand over the answer mid-conversation. Do not soften a fail. The value is in the user arriving at it themselves.

---

## Examples

### Example 1 — YouTube

**Stated problem:** "YouTube solves the need for on-demand, self-directed video consumption."

| Test | Question asked | User arrives at |
|---|---|---|
| Language test | "Would someone say 'self-directed video consumption' if they were bored?" | No — they'd say "I'm bored" |
| Body test | "What are they feeling when they open YouTube?" | Boredom, restlessness |
| Mechanism test | "If YouTube didn't exist, would they still be bored?" | Yes — boredom existed before YouTube |

**Demand-side (two layers):**
- Crisis layer: Boredom — unstructured time with no stimulus
- Baseline layer: Entertainment habit — mostly video, occasionally knowledge

**Supply-side:** Making money. Recognition is the mechanism creators use to get there.

**Verdict:** The original statement describes the mechanism, not the problem.

---

### Example 2 — LinkedIn

**Stated problem:** "LinkedIn solves the need for professional networking and career development."

| Test | Question asked | User arrives at |
|---|---|---|
| Language test | "Would someone networking say 'I need career development infrastructure'?" | No — they'd say "I don't know the right people" |
| Body test | "What are they feeling when they update their profile?" | Fear of being stuck, anxiety about falling behind peers |
| Mechanism test | "If LinkedIn didn't exist, would career stagnation still exist?" | Yes — the fear predates the platform |

**Demand-side (two layers):**
- Crisis layer: Fear of being stuck — activates when actively job hunting or feeling passed over
- Baseline layer: Need to know where you stand relative to others, and to be seen as someone moving forward — this is what keeps non-job-seekers scrolling daily

**Supply-side:** Cost and risk of a bad or slow hire. Recruiters are accountable for empty seats and wrong fits.

**Verdict:** The original statement describes the mechanism. The real problems are fear of stagnation + status anxiety (demand) and hiring risk (supply).

---

---

# FRAMEWORK 2: PSD Strategy (`strategy`)

A structured three-phase framework for building or evaluating product strategy. Developed from the PM practice of Denny Yusuf, referencing Michael Porter's segmentation approach and Shreyas Doshi's product thinking.

**Core sequence:** Positioning → Segmentation → Differentiation

Positioning is a vision tool (where we aspire to be). Segmentation is a strategy tool (who we're building for). Differentiation is an execution tool (how we win with that segment). This order is non-negotiable: vision sets direction, strategy narrows the target, execution proves the claim.

---

## Phase 1 — Positioning (Vision)

### Goal
Map the competitive landscape and find an open, defensible position. Positioning is aspirational at this stage — it does not need to be fully proven yet.

### Steps

**1. Competitor landscape**

Group competitors into archetypes (typically 2–4 groups). Common archetypes:
- Market leaders (dominant generalist players)
- Category specialists (niche but strong in one area)
- Regional/vertical players (strong in a geography or industry)
- Direct mission competitors (same audience, different model)

For each group, identify: what they claim, who they serve, where they are strong.

**2. Positioning map**

Build a 2x2 map. Axes must be derived from how users actually decide, not from where the product already excels. Test: would a user evaluate options along this dimension? If axes were chosen to isolate the product in a favorable quadrant, flag as vanity positioning.

Plot all competitor groups. A clean empty quadrant with no rivals is suspicious — either the axes are reverse-engineered, or key competitors are missing.

**3. Positioning statement**

> "For [who], [product] aims to be the only [category] that [distinctive promise]."

Flag if:
- The promise is a feature, not a meaningful outcome
- The promise is something most competitors already deliver
- The "who" is too broad to be actionable

---

## Phase 2 — Segmentation (Strategy)

### Goal
Identify the highest-priority winnable segment using a Porter-style needs-based matrix. A good segmentation is worth more than any individual feature decision.

### Steps

**1. Choose segmentation dimensions**

Use needs-based dimensions first. If needs alone are insufficient to create meaningful, distinct segments, move to the next criterion in this priority order:

1. Needs
2. Jobs to be done
3. Category of needs
4. Distribution
5. Adoption motion
6. Decision maker
7. Role
8. Core competency
9. Sophistication
10. Geography

Use the minimum number of dimensions needed. A 2x2 or 3x3 matrix is usually sufficient.

**2. Build the segmentation table**

Rows and columns represent the chosen dimensions. Each cell is either:
- A number (1, 2, 3...) indicating priority — 1 is highest
- An x indicating non-viable or not worth pursuing

Example structure:

| Y: Adoption motion \ X: Needs | Religious-driven | Cause-driven |
|---|---|---|
| RC/DHC givers | **1** | x |
| Routine manual givers | 2 | 4 |
| CC-driven manual givers | 3 | x |

**3. Priority-1 segment narrative**

For the #1 cell, write a short description:
- Who they are (behavioral, not just demographic)
- Their decision criteria when choosing a platform or product
- Their current alternatives (what they'd use if this product didn't exist)
- Why this segment is winnable given the positioning in Phase 1

The segment narrative feeds directly into Phase 3 — the factors in the differentiation table must come from this segment's decision criteria.

---

## Phase 3 — Differentiation (Execution)

### Goal
Build a differentiation table that maps the priority-1 segment's decision criteria against competitor groups, then assigns the product a B/T/D rating for each factor.

### Steps

**1. Define factors**

Factors must come from the priority-1 segment's decision criteria identified in Phase 2 — not from the product's known strengths. Reverse-engineering factors from existing advantages produces a vanity differentiation table.

Typical number of factors: 5–8. More than 10 becomes unmanageable.

**2. Score competitors**

Use competitor groups from Phase 1 (no re-mapping needed). Score each group per factor on a 1–3 scale:
- 1 = weak or absent
- 2 = adequate
- 3 = strong

**3. Assign B/T/D for the product**

For each factor, assign one of:
- **B** (Below threshold) — product does not meet the minimum bar this segment expects. Action: fix or reconsider segment fit.
- **T** (Threshold) — product meets the bar but does not stand out. Action: maintain, don't over-invest.
- **D** (Differentiation) — product is genuinely ahead in a way that matters to this segment. Action: protect, deepen, amplify.

**4. Build the table**

| Factor | [Group 1] | [Group 2] | [Group 3] | [Product] |
|---|---|---|---|---|
| Factor A | 1–3 | 1–3 | 1–3 | B/T/D |
| Factor B | 1–3 | 1–3 | 1–3 | B/T/D |

**5. Stress-test D claims**

For each D, ask: is this a structural moat or a temporary head start?
- Structural moats: data advantages, network effects, regulatory position, deep segment trust built over time
- Temporary head starts: features that competitors can copy in 6–12 months

Flag temporary head starts — they are not real differentiation without a plan to widen the gap.

**6. Strategy narrative**

Write 2–3 sentences summarizing:
- Where the Ds land (the actual strategic bets)
- What Bs are blockers that need resolving before the strategy is viable
- Roadmap implication: Bs on key factors = fix first; Ts = maintain; Ds = build depth

---

## Guard Rails (strategy)

- **No vanity positioning.** Axes and factors must reflect user decision criteria, not product strengths.
- **No cherry-picked competitors.** Always include the strongest archetype, even if unflattering.
- **No disconnected phases.** Competitor groups from Phase 1 feed Phase 3. Segment criteria from Phase 2 feed Phase 3 factors. If the phases are internally inconsistent, flag it before proceeding.
- **D without durability is misleading.** A D that competitors can replicate in a year is a roadmap item, not a strategic position.
- **Segment first, differentiate second.** A D on a factor the priority-1 segment doesn't care about is meaningless.

---

## Output Format (strategy)

Deliver each phase sequentially. Do not combine phases into a single artifact — they answer different questions and may have different audiences.

After all three phases, offer a one-paragraph synthesis: how the positioning vision, the target segment, and the differentiation table connect into a coherent strategy.
