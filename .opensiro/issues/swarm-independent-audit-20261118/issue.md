# jcode — independent swarm-result audit (Human issue)

**Target transition:** S3*=— -> S3*=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

**Scope:** source-pinned independent Upstream #58 rerun on 2026-11-19. The historical 2026-11-18 PLAN_ONLY case remains in Git history. **DRAFT — NOT PUBLISHED**: this is an internal fork-local decision, not an issue or PR to original maintainers.

[constructor-sufficiency.md](constructor-sufficiency.md) · [roadmap.md](roadmap.md) · [Original jcode](https://github.com/1jehuang/jcode)

## Why OpenSiro and accepted historical VSM assessment

OpenSiro investigates whether reusable VSM-informed, source-native organizational capabilities can reduce harness engineering and integration cost. No savings are demonstrated; the jcode project has no obligation to adopt VSM.

**Historical Index baseline (not current code or proposed grades):** S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—. Accepted [Index assessment](https://github.com/opensiro/vsm-harness-index/blob/b6318e9fb855c20a0a48dfd0ea03f78aaafbb320/assessments/jc/jcode.md), blob 26ab988dd6ef8fb1ddbab8e8fff8c3202781eed4, reviewed 2026-09-17 against original 5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe, Profile 0.2.2 / Skills Methodology 0.3.1. The assessment is 63 calendar days old; source drift warrants an Index-owned re-review, not an automatic regrade or mandatory pause.

| Function | Accepted state | Current evidence and why selected/not selected |
| --- | --- | --- |
| **S1 · Operations** | A | Running coding workers own code decisions; no extra C constructor justified |
| **S2 · Coordination** | A | Native plan dependencies, member messaging and conflict handling; no extra C constructor justified |
| **S3 · Current control** | A | Root coordinator owns assignments and requeue/recovery; independent audit must report to, not replace, it |
| **S3* · Independent audit** | — | Current reviewer sessions are not wired into swarm-plan acceptance; qualified on-top C hypothesis |
| **S4 · Future adaptation** | — | Ambient/memory material does not prove a missing developer-composable future/strategy decision at this swarm boundary |
| **S5 · Identity and policy** | — | Ultimate authorization remains with user/project owner; not a local autonomy deficit or desired new control plane |

These states describe historical decision ownership, not software quality.

## Operator outcome and new bounded decision

A worker may claim that coding work is complete while the authoritative source was not updated or an obsolete copy was changed. Original [Issue #1403](https://github.com/1jehuang/jcode/issues/1403) reports four missing outputs and one wrong-location write among 12 spawns; these are reporter claims, **not independently reproduced here**. Original [Issue #2239](https://github.com/1jehuang/jcode/issues/2239) and open [PR #2240](https://github.com/1jehuang/jcode/pull/2240) address unfinished lane work/acceptance. They are relevant native work, not proof that a separate independent auditor is already installed.

**P0 — GO to an S3* construction proposal, not to coding:** provide an opt-in, developer-installable read-only reviewer that examines version-pinned worker output, real authoritative artifacts and acceptance evidence before an audit-required swarm task is accepted. Its independent PASS / RECHECK / UNKNOWN opinion returns to the existing S3 coordinator, which decides accept, hold or retry. This is a proposed first-party interface and guarded feedback loop; it does not exist as a demonstrated installed C.

## Existing native work and missing on-top capability

| Track A: cheapest existing/native route | What it covers | Track B: only additional function-specific effect |
| --- | --- | --- |
| Worker/coordinator artifact checks in [#1403](https://github.com/1jehuang/jcode/issues/1403) | Presence, relevant path and commit checks; may solve the entire operator task cheaply | Independent judgment only if a different outcome remains after native checks |
| [Swarm architecture](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/docs/SWARM_ARCHITECTURE.md) and [server control](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-app-core/src/server/comm_control.rs) | Shared assignments, state, terminal status and coordinator action | Version-bound audit-required pending outcome, then return findings to S3 |
| [Review command](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-tui/src/tui/app/commands_review.rs) | Read-only separate reviewer of a session; not itself an admission rule for a worker lane | Reuse reviewer mode as actor, but add first-party swarm evidence/decision wiring |
| [#2239](https://github.com/1jehuang/jcode/issues/2239) and [#2240](https://github.com/1jehuang/jcode/pull/2240) | Proposed or pending worker completion/verification behavior | Distinguish independent scrutiny of a semantically wrong artifact even when lane checks pass |

A worker with all tasks marked complete but a stale or incorrect production artifact is the discriminator. The simple/native comparator is artifact validation plus an ordinary coordinator review, not a fictional absence of checks.

## Priorities, acceptance and stopping rules

**P1**: reproduce #1403 on pinned jcode; examine #2239/#2240 and existing [#2035](https://github.com/1jehuang/jcode/pull/2035), [#2038](https://github.com/1jehuang/jcode/pull/2038), [#2040](https://github.com/1jehuang/jcode/pull/2040), [#2041](https://github.com/1jehuang/jcode/pull/2041) by live head and diff; compare simplest native checks; establish lawful reviewer registration/authorization and deterministic version/timeout behavior. **P2: NONE**.

Positive future test: separate auditor discovers a real source mismatch and S3 holds/reassigns the exact task; a correct artifact gets accepted. Negative tests: self-review forbidden, stale task/revision or revoked reviewer cannot approve, missing required auditor stays pending without unsafe release; unconfigured baseline continues working. Tests **NOT_RUN** and cost **NOT_MEASURED**.

Falsifier: an existing shipped/native issue solution produces equivalent correct acceptance without an independent model-owned S3* decision, or no independent auditor can lawfully change downstream S3 behavior. If so, stop the C construction and use native verification. Do not create a competing product PR while [#2208](https://github.com/1jehuang/jcode/issues/2208) discusses PR/branch churn.

## Comparison after independent decision and handoff

The historical [2026-11-18 case](https://github.com/opensiro-contributions/jcode/blob/c98f41c73818ed7bdeed32d8ab76129a342a91fa/.opensiro/issues/swarm-independent-audit-20261118/roadmap.md) was **PLAN_ONLY / NEEDS_EVIDENCE**, with a conditional S3* hypothesis but **no terminal GO/NO_GO/BLOCKED**. The 2026-11-19 independent source pass reaches scoped **GO / NEEDS_EVIDENCE**, now against new #2239/#2240 evidence. This does not replace historical provenance or assert a current Index change.

Implementation, original Issue/PR/comment, public fork Issue/PR, native tests and cost measurement: **NOT DONE / NOT PUBLISHED**. Any outward publication still needs exact current-conversation approval. [Canonical receipt](roadmap.md).
