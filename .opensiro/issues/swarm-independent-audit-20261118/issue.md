# jcode — independent swarm-result audit roadmap (Human issue)

**PLAN_ONLY / NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**  
**Original:** [1jehuang/jcode](https://github.com/1jehuang/jcode/commit/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745) (master f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745) · **Working fork:** [opensiro-contributions/jcode](https://github.com/opensiro-contributions/jcode) · **case:** `.opensiro/issues/swarm-independent-audit-20261118/` on `opensiro/meta`.  
**AI/developer companion:** [constructor-sufficiency.md](constructor-sufficiency.md).

## 1. Why Opensiro and central accepted VSM assessment

Opensiro investigates whether reusable, VSM-informed organizational specifications and source-native engineering can standardize and reduce the total cost of AI-agent harness development. These savings are **not measured**, and maintainers need not adopt VSM.

**Central HISTORICAL Index starting point, NOT proposed future grades or current master:** `S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—`. [Accepted assessment](https://github.com/opensiro/vsm-harness-index/blob/42dc230289bb5992bc3588fa5376b817b282a0fd/assessments/jc/jcode.md), file blob `26ab988dd6ef8fb1ddbab8e8fff8c3202781eed4`, reviewed 2026-09-17 at source `5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe`; Profile v0.2.2, Skills Methodology v0.3.1. Age: 62 days; recommend Index-owned re-review without blocking research.

| Function | Accepted | Meaning / decision |
| --- | --- | --- |
| S1 Operations | A | Existing coding agents, no mandatory C target |
| S2 Coordination | A | Shared-plan dependencies and conflicts, no mandatory C |
| S3 Current control | A | Coordinator assignment and recovery, no mandatory C |
| S3* Complementary independent audit | — | Conditional new independent review constructor research |
| S4 Outside/future adaptation | — | No independently justified additional work |
| S5 Identity/ultimate policy | — | Trust/permissions are not by themselves S5; no work justified |

A/C/P are ownership arrangements, not a grade ladder or software quality score.

## 2. Proposed user capability and decision

An operator with multiple coding agents wants a worker's completed status to match actual work on the **authoritative** files, not an absent artifact or a stale copy. [Original jcode #1403](https://github.com/1jehuang/jcode/issues/1403) reports 4/12 missing outputs and 1/12 written to the wrong location (author-reported, not independently reproduced). The original issue already proposes native verification options A/B/C; **do not file a duplicate**.

**Primary decision:** first confirm whether cheap native artifact validation (A or B) already solves this task. Only if a material residual need survives, consider a first-party **independently developer-composable S3* auditor** whose decision actually changes later coordinator task disposition.

## 3. Existing native work versus gap

| Current / proposed | Source | Gap / decision |
| --- | --- | --- |
| SHIPPED: swarm plan and coordinator roles | [Swarm Architecture](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/docs/SWARM_ARCHITECTURE.md), [jcode-plan](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/crates/jcode-plan/src/lib.rs) | Verify all current accepted-completion routes before asserting absence |
| SHIPPED: read-only reviewer sessions | [commands_review.rs](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/crates/jcode-tui/src/tui/app/commands_review.rs) | Separate reviewer != enforceable S3* task outcome |
| ISSUE: artifact verification A/B/C | [#1403](https://github.com/1jehuang/jcode/issues/1403) OPEN | Reuse it; reproduce the reported failure on current master |
| OPEN PRs, not shipped | [#2035](https://github.com/1jehuang/jcode/pull/2035) swarm hooks, [#2038](https://github.com/1jehuang/jcode/pull/2038) trust, [#2040](https://github.com/1jehuang/jcode/pull/2040) agent definitions, [#2041](https://github.com/1jehuang/jcode/pull/2041) policy | Avoid duplicating dependent unmerged changes |
| ISSUE: project sequencing | [#2208](https://github.com/1jehuang/jcode/issues/2208) OPEN | Maintainer is considering freezes; avoid speculative new lanes |

The older `swarm-deep` critique/verify mode was removed according to current Swarm Architecture. Simple artifact existence checks need not be mislabeled independent S3*.

## 4. Priorities and minimum sufficient result

- **P0 (conditional S3*=C hypothesis):** developer can install an independent, read-only task-result auditor, select lawful ACCEPT / REJECT / INCONCLUSIVE after inspecting real evidence, and reliably return a version-bound receipt to coordinator S3 that affects subsequent task acceptance.
- **P1:** reproduce #1403, identify the actual source-native completion owner/path and native alternative; check all competing PR heads/diffs, permissions, supported modes, stale-result behavior and negative/compatibility cases.
- **P2: NONE** (no speculative S4, S5 or C(P)/A(P) promotion).

A complete constructed path would need a genuine independent actor, function-specific decision interface, authority, state/options, enforcement, durable receipt, actual next-operation change and positive/negative native tests. All remain future work, not an accepted C.

## 5. Acceptance / stop gates

Positive: valid evidence and lawful independent ACCEPT releases the task only under its exact source revision. Negative: REJECT, stale receipt, missing auditor or unauthorized self-review does not release an audit-required task. Compatibility: an ordinary non-audited task still works. **Tests NOT RUN.** Stop on simpler adequate native solution, already-existing implementation, no material user outcome, denied rights, or inadequate independence.

## 6. Independent paths

Native jcode contribution in existing issue #1403; source-backed Profile/Skills specification feedback; separately authorized MIT-permitted experimental domain fork. None requires the project to adopt VSM.

## 7. Cost hypothesis

Compare matched #1403 missing/wrong-path cases using simplest jcode-native verification versus the proposed independent audit. Measure implementation, integration, review, testing, maintenance and runtime overhead. **NOT_MEASURED.**

## 8. Handoff and permissions

**Research status: PLAN_ONLY / NEEDS_EVIDENCE.** [AI contract](constructor-sufficiency.md) · [receipt](roadmap.md) · [optional original comment draft](maintainer-comment-draft.md). No public fork Issue, external comment/issue/PR, product changes, native tests, Index regrade or proven cost saving. Metadata initialized with `PAUSE / DORMANT` pending separate authorization for later effectful work.
