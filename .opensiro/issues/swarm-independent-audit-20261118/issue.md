# jcode — S3*=— -> S3*=C (OpenSiro fork-local Human roadmap)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**One-sentence proposal:** A developer-composed independent read-only verifier evaluates the exact candidate task result against authoritative artifacts and plan version, returns PASS / RECHECK / UNKNOWN, and makes coordinator hold, requeue or accept before later dispatch.

**Canonical decision receipt:** [roadmap.md](roadmap.md) — source of truth for historical assessment, canonical target, P0/P1/P2, decision and research state.
**Technical companion:** [constructor-sufficiency.md](constructor-sufficiency.md) — source-native controls and future test contract.
**Working fork:** opensiro-contributions/jcode on opensiro/meta.
**Case:** .opensiro/issues/swarm-independent-audit-20261118/.

## 1. Why Opensiro and central accepted VSM assessment

OpenSiro explores whether VSM-informed organizational construction helps agent harness engineering. It is a **research hypothesis**, not product certification, cost savings or a maintainer adoption request.

### Central starting point — accepted Index, not the target

> **ACCEPTED HISTORICAL INDEX — not current-HEAD grades or proposed after-states**
>
> **S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—**
>
> [Pinned accepted Index assessment](https://github.com/opensiro/vsm-harness-index/blob/b6318e9fb855c20a0a48dfd0ea03f78aaafbb320/assessments/jc/jcode.md); blob SHA 26ab988dd6ef8fb1ddbab8e8fff8c3202781eed4; historical review ref 5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe; reviewed 2026-09-17; historical Profile/Skills versions retained in the canonical [roadmap.md](roadmap.md).

**Repository-wide audit:** The present same-case v0.18.2 follow-up used 1jehuang/jcode original HEAD 553db90882164c47a986f13e79541bddc7a9b723, checked first-party source at [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs), original repository https://github.com/1jehuang/jcode/issues/1403 (OPEN, reported wrong/missing output); prior case also references #2239 and unfinished #2240, whose current head requires fresh verification., prior accepted assessment and published protocol. The system in focus is the installed first-party agent harness and its supported components; separate host provider, original maintainer policy, repo CI and external services are not automatically in-boundary autonomous owners. Prior fork-case evidence was opened only after the source-first #58 [checkpoint](https://github.com/opensiro/upstream/issues/58#issuecomment-7047329680). This was a bounded source review, not exhaustive source classification or a fresh accepted Index grade.

| Function / plain-language role | Historical Index state | Current source-backed owner/closure | Candidate / justified no-target / uncertainty and rank |
| --- | --- | --- | --- |
| **S1 · Operations** | A | First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. | ALREADY_A — named coding agents execute work; additional C has no demonstrated independent need. |
| **S2 · Coordination** | A | First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. | ALREADY_A — server plan dependencies, messaging and file-change notification coordinate writers; no justified second C. |
| **S3 · Current management** | A | First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. | ALREADY_A — root coordinator steers assignment/retry and current plan; preserve decisive S3 rights. |
| **S3* · Independent review** | — | S1/S2/S3 are already historically agent-owned. Only independent complementary outcome review is a conditional candidate; S4 remains unproven, S5 parent-reserved. | P0 conditional: A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. |
| **S4 · Future adaptation** | — | S1/S2/S3 are already historically agent-owned. Only independent complementary outcome review is a conditional candidate; S4 remains unproven, S5 parent-reserved. | UNKNOWN/NO_TARGET — ambient/memory examples do not prove a separately required in-boundary prospective strategic C; revisit on environmental-change counterexample. |
| **S5 · Identity/policy** | — | Legitimate parent/user controls ultimate policy, approval and publication, not the proposed auditor or controller. | PARENT_RESERVED/NO_TARGET — mission, identity and ultimate policy remain with user/project owner; cannot invent local autonomous authority. |

**Interpretation:** A, C, P and — denote ownership categories, **not quality ranks**; a historical dash is not proof work is necessary and A is not inferior to C. Unsupported current-HEAD functions stay UNKNOWN rather than silently regraded.

**Priority rationale:** S1/S2/S3 are already historically agent-owned. Only independent complementary outcome review is a conditional candidate; S4 remains unproven, S5 parent-reserved. The selected S3* target is the only conditional P0 in this existing case. Utility and actual independent operation remain unmeasured.

**Deliberate exclusions / methodology challenge:** No first-party independent actor has been shown to ship the complete optional link. Do not promote the historical grade or treat a proposed design as installed. No new S5 delegation or additional automatically generated Sx. Separate Profile/Skills review is required for any real classification counterexample.

**Contributor / maintainer interests:** NOT_STATED as approval for this construction. An original Issue is not maintainer acceptance.

## 2. Selected construction hypothesis and operator outcome

**Target transition:** S3*=— -> S3*=C

**Function-specific disturbance:** A worker reports done while source artifacts are absent, stale or not at the claimed location; this is an original reporter scenario, not an independently reproduced defect.

**Proposed C capability (P0):** A developer-composed independent read-only verifier evaluates the exact candidate task result against authoritative artifacts and plan version, returns PASS / RECHECK / UNKNOWN, and makes coordinator hold, requeue or accept before later dispatch.

**Best native operator alternative:** Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error. Native source: [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs).

**Expected user benefit:** HYPOTHETICAL. Detect wrong authoritative outcome even when worker checks and marked tasks pass, giving S3 different lawful task disposition; hypothetical benefit beyond reported #1403 failure, not measured. No native implementation or matched benefit test has occurred.

**Architectural sufficiency argument:** The first-party baseline already provides part of the path: First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. The proposed developer-installed decision owner adds the strictly scoped capability: PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. A lawful effect and later feedback are required: A version-matched hold/requeue or acceptance changes the next runnable plan item and reaches the coordinator; a later plan observation reflects that outcome. This is a conditional complete design, not a shipped C witness.

## 3. Existing native work versus missing construction

**Track A — native coverage:** SHIPPED first-party source: [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs). Existing original evidence: https://github.com/1jehuang/jcode/issues/1403 (OPEN, reported wrong/missing output); prior case also references #2239 and unfinished #2240, whose current head requires fresh verification.. Issue or PR is never treated as deployed simply by title.

**Track B — independent on-top C construction:** A developer-composed independent read-only verifier evaluates the exact candidate task result against authoritative artifacts and plan version, returns PASS / RECHECK / UNKNOWN, and makes coordinator hold, requeue or accept before later dispatch. Keep the original's native terminology, identities, state and permission checks.

| C-sufficiency requirement | Already present / original status (A) | Smallest conditional first-party delta (B) |
| --- | --- | --- |
| Scoped independent owner choice | First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. | PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. |
| Enforced effect and later observation | crates/jcode-app-core/src/server/comm_plan.rs, crates/jcode-plan/src/lib.rs provide candidate entrypoints, not a proven new C | A version-matched hold/requeue or acceptance changes the next runnable plan item and reaches the coordinator; a later plan observation reflects that outcome. |

**Distinctness and falsifier:** A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. Shipped native verification already changes the same lawful outcome without independent audit, or no genuinely independent actor can affect later S3 decisions. Historic prior decision remains the canonical baseline; no new unrelated function is implied.

## 4. Priorities and minimum sufficient result

- **P0:** Opt-in first-party version-bound independent audit actor on an authoritative worker-result candidate, with read-only independent judgment PASS/RECHECK/UNKNOWN, explicit S3 reconciliation and later task-control feedback.
- **P1:** Reproduce #1403 and compare native cheapest A/B/C; review #2239/#2240 and overlapping hook/trust/agent PR diffs; verify supported runtime, authorization, stale-version controls and native acceptance.
- **P2:** NONE

**Proposed C-sufficiency verdict:** PROPOSED_C_SUFFICIENT at a conditional architectural proposal stage only. No native build, cost proof, Index regrade or external consent.

## 5. Proposed acceptance and stop gates

**Future positive test:** Construct two identical candidate results with different independently observed artifact facts; verify only the genuine one can close audit-required plan work and subsequent worker scheduling follows the decision.

**Future negative test:** Missing, stale, self-authored, revoked or mismatched reviewer evidence cannot mark an audit-required plan task completed; no-audit deployments retain the current plan workflow.

**Proposed falsifier:** Existing simpler first-party path achieves the same operator outcome, no distinct reviewer decision is possible or audit cannot return to S3.

**Validation state:** NOT_RUN; only document structural validation will be performed on fork-local artifacts, not native tests.

## 6. Independent paths

**Original-native contribution:** Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error. Third-party code PR, Issue or comment requires separate owner approval and normal project rules.

**Profile / Skills:** No forced methodology change; raise an independent correction only for a reproducible semantics/ownership conflict.

**Domain fork:** Optional licensed and permission-checked test only, not performed or authorized here.

## 7. Cost hypothesis

Matched native A versus optional new B would measure actual engineering, review, integration, runtime and maintenance effort alongside the named operator outcome. **Cost status: NOT_MEASURED.** Cost reduction is not asserted.

## 8. Decision / handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Decision reason / next permitted step:** Canonical proposal remains GO / NEEDS_EVIDENCE based on the earlier source-pinned receipt. This v0.18.2 source-first follow-up found A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. and does not claim newly shipped capabilities or five independent isolated chat contexts. Compare the cheapest native alternative, source drift and lawful C feedback before product implementation.

**Agent/developer handoff:** [constructor-sufficiency.md](constructor-sufficiency.md) and [roadmap.md](roadmap.md), with reservations and prior-independent checkpoint at [Upstream #58](https://github.com/opensiro/upstream/issues/58#issuecomment-7047108048).

**Rights and publication:** MIT original LICENSE; matched fork opensiro/meta owner state was ACTIVE / ALLOW at preflight; recheck before effect. **No public fork Issue**, original Issue/comment/PR, implementation, changed Index grade or new S5 authority is authorized. PAUSE/STOP must block. This draft is not externally published.

**AI disclosure:** Prepared with AI assistance. No native tests, independent human validation or measured benefit claimed.
