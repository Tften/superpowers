---
name: requesting-code-review
description: Use when completing tasks, implementing major features, or before merging to verify work meets requirements
---

# Requesting Code Review

Get a code review before issues cascade. The reviewer works from precisely
crafted context — the diff, the plan, the requirements — never your
session's history.

**Core principle:** Review early, review often.

## When to Request Review

**Mandatory:**
- After completing a major feature
- Before merge to main
- At the final review of superpowers:executing-plans

**Optional but valuable:**
- When stuck (fresh perspective)
- Before refactoring (baseline check)
- After fixing a complex bug

## How to Request

**1. Get git SHAs:**
```bash
BASE_SHA=$(git merge-base main HEAD)  # or: git rev-parse HEAD~1
HEAD_SHA=$(git rev-parse HEAD)
```

**2. Run the review:**

- **With a subagent tool:** dispatch a `general-purpose` subagent, filling
  the template at [code-reviewer.md](code-reviewer.md). Specify the model
  explicitly — the whole-branch review is a judgment task that earns the
  most capable model. The diff and the evaluation live in its context;
  only the findings come back to you.
- **Without a subagent tool:** read code-reviewer.md and perform that
  review yourself against the change, as a separate pass after the work.
  Say so in your final message: a self-review by the author is weaker than
  a fresh reviewer, and your human partner decides whether that is enough
  before merge.

**Placeholders for the template:**
- `{DESCRIPTION}` - Brief summary of what you built
- `{PLAN_OR_REQUIREMENTS}` - What it should do
- `{BASE_SHA}` - Starting commit
- `{HEAD_SHA}` - Ending commit

**3. Act on feedback:**
- Fix Critical issues immediately
- Fix Important issues before proceeding
- Note Minor issues for later
- Push back if reviewer is wrong (with reasoning)

## Common Rationalizations

| Excuse | Reality |
|--------|---------|
| "I'll skip review because I already ran the tests" | Tests prove the code does what you meant. Review asks whether what you meant is what the plan requires. Different question, different gate. |
| "The reviewer needs my whole session history to understand the change" | Hand it precisely crafted context, never your session's history. That keeps the review on the work product, not your thought process. |

## Red Flags

**Never:**
- Skip review because "it's simple"
- Ignore Critical issues
- Proceed with unfixed Important issues
- Argue with valid technical feedback

**If reviewer wrong:**
- Push back with technical reasoning
- Show code/tests that prove it works
- Request clarification

See template at: [code-reviewer.md](code-reviewer.md)
