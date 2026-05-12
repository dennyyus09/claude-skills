# claude-skills

Custom skills for Claude Code.

## Skills

### `psd-framework`
A structured three-phase framework for building or evaluating product strategy.

**Phases:** Positioning (vision) → Segmentation (strategy) → Differentiation (execution)

**Trigger when:**
- Defining product strategy or market positioning
- Identifying target segments
- Building a competitive differentiation table
- Answering "who should we build for", "how do we differentiate", or "where do we play"
- Reviewing a positioning map, segmentation matrix, or competitive comparison

### `problem-validation`
A stress-test framework for product problem statements. Checks whether a stated problem is a real human motivation or a dressed-up mechanism.

**Tests:** Language → Body → Mechanism

**Trigger when:**
- Reviewing or stress-testing a problem statement
- Someone says "the problem we solve is..." and you want to pressure-test it
- Separating demand-side and supply-side problems
- Checking if a stated problem is actually just a solution wrapper

## Usage

Install a skill by pointing Claude Code to the raw file URL:

```
/skill add https://raw.githubusercontent.com/dennyyus09/claude-skills/main/psd-framework.md
```

```
/skill add https://raw.githubusercontent.com/dennyyus09/claude-skills/main/problem-validation.md
```
