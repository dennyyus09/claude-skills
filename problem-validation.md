---
name: problem-validation
description: "Validate whether a stated product problem is real or a dressed-up solution. Use this skill when the user wants to stress-test a problem statement, check if they've identified the true user motivation, or pressure-test the difference between a problem and a mechanism. Trigger when the user says things like 'the problem we solve is', 'our users need', 'we help people', or presents a problem statement for review."
---

# Problem Validation Skill

A stress-test framework for product problem statements. The goal is not to find a better-sounding answer — it's to find the true one.

**Core principle:** A real problem is felt, not theorized. If a user wouldn't use your words to describe what they're experiencing, you haven't found the problem yet — you've found the mechanism between the problem and the solution.

---

## How to Use This Skill

The user provides a problem statement, either demand-side or supply-side (or both). Run each through the three tests below. Flag failures clearly. Do not soften findings.

---

## The Three Tests

### Test 1 — The Language Test
> Would a real user say this out loud, unprompted?

Ask: if you stopped a user on the street and asked "what's wrong?", would they use these words?

- "I want self-directed access to on-demand content" → fail
- "I'm bored" → pass

If the language is analytical, abstract, or sounds like a product review, it's a mechanism or a rationalization — not the problem.

**Flag:** rewrite in plain, felt language. One sentence. No jargon.

---

### Test 2 — The Body Test
> Can you feel this problem physically or emotionally?

Boredom: yes. Frustration: yes. "Asymmetric access to broadcast": no.

Real problems live in the body — restlessness, anxiety, embarrassment, desire, fear, hunger. If the problem statement produces no felt response, it's sitting at the wrong level.

**Flag:** ask what emotion or physical state the user is in when they experience this problem. That state is closer to the real problem than any analytical framing.

---

### Test 3 — The Mechanism Test
> Is this the problem, or the path between the problem and the solution?

Entertainment is not the problem — it's the mechanism YouTube uses to solve boredom.
Distribution is not the problem — it's the mechanism creators use to solve for money and fame.

Ask: if this "problem" disappeared, would users still have the underlying issue? If yes, what you have is a mechanism.

**Flag:** strip the mechanism. What raw need or pain existed before this product category existed?

---

## Output Format

For each problem statement provided:

1. **Run all three tests.** Pass or fail each, with one sentence of reasoning.
2. **If any test fails**, restate the problem in truer language — felt, plain, pre-solution.
3. **Separate demand-side and supply-side** if the product serves both. They almost always have different real problems.
4. **End with a one-line verdict:** is this a real problem statement or a mechanism?

Do not offer encouragement. Do not soften a fail into a partial pass. The value of this framework is precision.

---

## Example

**Stated problem:** "YouTube solves the need for on-demand, self-directed video consumption."

| Test | Result |
|---|---|
| Language test | Fail — no user says "self-directed video consumption" |
| Body test | Fail — no felt state, purely analytical |
| Mechanism test | Fail — on-demand video is the solution, not the problem |

**Restated (demand-side):** Boredom. Users open YouTube because they have unstructured time and no stimulus.

**Restated (supply-side):** Money and recognition. Creators upload because they want income or an audience.

**Verdict:** The original statement describes the mechanism, not the problem.
