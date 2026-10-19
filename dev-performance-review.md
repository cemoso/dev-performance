# Developer Performance Review Framework

## Overview
This framework evaluates software developers across five core competencies. Each criterion is scored 1-5 against written anchors; a category score is the sum of its criteria, then normalized by the category weight. Reviews are conducted quarterly with a comprehensive annual summary.

**Developer:** ___________________ **Role / Level:** ___________________ **Period:** ___________

**Scoring Scale**
- 1 = Does not meet expectations
- 2 = Partially meets expectations
- 3 = Meets expectations
- 4 = Exceeds expectations
- 5 = Exceptional performance

**How to score**
- Score against expectations for the developer's **current level**. A 3 is what a solid engineer at that level does. A junior scoring 5 on mentoring looks different from a staff engineer scoring 5.
- Each criterion has anchors for 1, 3 and 5. Use 2 and 4 for in-between cases.
- Every score of 1, 2, 4 or 5 needs at least one concrete example from this period in the Evidence column.
- **Raw activity counts are never scored.** Commit counts, lines changed, number of PRs, review turnaround minutes, and automated or AI review pass rates may appear in Evidence as context but are not criteria. Scoring them produces the behaviour they measure, not the outcome they stand for.
- **Risk is judged on how it was handled, not on whether it bit.** Defects from agreed high-risk work (a necessary migration, a rewrite) count against the developer only if the risk was not flagged, staged, or recovered from well.
- Mark a criterion **N/A** when it genuinely cannot apply this period (for example, mentoring on a team with no less experienced members). Reduce the category max by 5 for each N/A.

---

## Category 1: Technical Growth & Problem Solving (20%)

| Criterion | 1 | 3 | 5 | Score | Evidence |
|-----------|---|---|---|-------|----------|
| Learns technologies relevant to the company stack | Skills are the same as last period | Picked up what the work required | Learned ahead of need and others now rely on that knowledge | | |
| Applies new knowledge to solve real problems | Learning stays theoretical | Used new skills on at least one real problem | New approach measurably improved a system or process | | |
| Reduces technical debt | Adds debt without flagging it | Pays down debt in code they touch | Retired a significant source of debt the team had been living with | | |
| Proposes improvements to existing systems | None, or proposals ignore constraints | Sensible proposals, some adopted | Proposals shaped team or system direction this period | | |

**Category Score:** ___ / 20

---

## Category 2: Knowledge Distribution & Bus Factor (25%)

| Criterion | 1 | 3 | 5 | Score | Evidence |
|-----------|---|---|---|-------|----------|
| Documentation for owned systems | Knowledge lives only in their head | Owned systems have current docs and runbooks a teammate has used at least once | Docs are the reference others reach for; kept current without prompting | | |
| API contracts defined and maintained | Interfaces undocumented or change without notice | Contracts documented; no unannounced breaking change this period | Contracts versioned and tested; consumers upgrade without coordination | | |
| Handoff readiness | A handoff would stall the team | Owned systems have an onboarding path a new developer could follow in about 2 weeks | A handoff, vacation or on-call rotation this period ran without them and nothing stalled | | |
| Cross-training participation | Neither teaches nor learns others' areas | Took part in sessions; covered one area beyond their own this period | Runs sessions; measurably reduced the team's bus factor | | |

**Category Score:** ___ / 20

---

## Category 3: Output & Code Quality (25%)

| Criterion | 1 | 3 | 5 | Score | Evidence |
|-----------|---|---|---|-------|----------|
| Delivery predictability | Commitments regularly slip without warning | Delivers what was committed, or re-scopes early and visibly | Consistently accurate estimates; absorbs surprises without missing commitments | | |
| Changes are scoped so reviewers can reason about them | Changes routinely mix unrelated concerns or are too large to review meaningfully | Changes are coherent units a reviewer can follow; large changes are explained | Hard problems arrive as a clear sequence of reviewable steps | | |
| Risk-adjusted defect rate | Changes frequently cause bugs, rollbacks or incidents, and risk is not flagged in advance | Defects in line with the team for comparable work; risk flagged up front; own bugs fixed promptly | Takes on the team's riskiest changes with staged rollouts and rollback plans, and still ships at or below the team defect rate | | |
| Testing and verification | Ships untested changes | Changes carry tests appropriate to the risk | Improves the team's test coverage or tooling beyond own changes | | |
| Follows coding standards and delivery process | Repeatedly needs the same corrections, or skips process steps causing rework or incidents | Meets standards and follows the process without reminders | Improves the standards or the process where they were wrong | | |

**Category Score:** ___ / 25

---

## Category 4: Continuous Improvement (Kaizen) (15%)

| Criterion | 1 | 3 | 5 | Score | Evidence |
|-----------|---|---|---|-------|----------|
| Improves how the team works | No contribution, or suggestions with no follow-through | At least one improvement adopted by the team | Drove a change that measurably reduced waste or friction | | |
| Retrospective participation | Absent or passive | Contributes honest, specific input | Surfaces root causes others missed; follows actions through | | |
| Progress on self-identified growth areas | No goals, or no progress | Visible progress on goals from last review (first period: goals set and started) | Goals met and new ones set independently | | |

**Category Score:** ___ / 15

---

## Category 5: Collaboration & Communication (15%)

| Criterion | 1 | 3 | 5 | Score | Evidence |
|-----------|---|---|---|-------|----------|
| Code reviews for teammates | Rubber-stamps, doesn't review, or reviews wait days without explanation | Turnaround matches urgency; catches real issues; feedback is actionable | Reviews are timely and teach; teammates seek them out | | |
| Unblocks teammates | Holds information or decisions others need | Responds to requests; shares what's needed | Anticipates blockers and clears them before being asked | | |
| Clear and timely status updates | Status must be chased | Tickets and updates reflect reality | Updates let stakeholders act without asking questions | | |
| Appropriate escalation | Sits on problems, or escalates everything | Escalates the right issues at the right time | Escalates with options and a recommendation | | |
| Mentoring contribution | Unavailable to less experienced teammates | Helps when asked; mentees make progress | Mentees' growth is visible in their own reviews; scales to level | | |
| Reduces team friction | Source of recurring friction | Handles disagreements constructively | Resolved a specific conflict between others this period | | |

**Category Score:** ___ / 30

---

## Summary

**Weighted Score = (Category Score ÷ Category Max) × Weight**

Example: 24/30 in Collaboration → 24 ÷ 30 × 15 = 12.0

| Category | Weight | Score | Max | Weighted Score |
|----------|--------|-------|-----|----------------|
| Technical Growth & Problem Solving | 20 | | 20 | |
| Knowledge Distribution & Bus Factor | 25 | | 20 | |
| Output & Code Quality | 25 | | 25 | |
| Continuous Improvement (Kaizen) | 15 | | 15 | |
| Collaboration & Communication | 15 | | 30 | |
| **Total** | **100** | | | **/100** |

Criteria counts differ per category, so raw scores are not comparable across categories; only weighted scores are. Reduce a category's Max by 5 for each N/A criterion.

---

## Performance Rating

| Total Score | Rating |
|-------------|--------|
| 90 to 100 | Exceptional |
| 70 to below 90 | Exceeds Expectations |
| 50 to below 70 | Meets Expectations |
| 30 to below 50 | Needs Improvement |
| Below 30 | Does Not Meet Expectations |

Bands are centered on the 1-5 scale: a uniform 3 on every criterion totals 60, the middle of Meets Expectations; a uniform 4 totals 80, the middle of Exceeds. For mixed profiles only the weighted total matters.

The score is an input to the review conversation, not the conclusion. The written evidence and the comments below carry more weight than the number.

**Final Rating:** _______________

---

## Goals for Next Review Period

1. 
2. 
3. 

---

## Employee Comments



---

## Reviewer Comments



---

**Employee Signature:** ___________________ **Date:** ___________

**Reviewer Signature:** ___________________ **Date:** ___________
