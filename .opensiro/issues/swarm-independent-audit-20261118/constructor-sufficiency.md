# jcode — source-native S3* C-construction technical contract

**Canonical storage:** opensiro-contributions/jcode@opensiro/meta:.opensiro/issues/swarm-independent-audit-20261118/constructor-sufficiency.md.
**Level 1 / Human decision Issue:** [issue.md](issue.md).
**Canonical decision receipt:** [roadmap.md](roadmap.md), authoritative for Index vector, case pins, priority and verdict.
**Stage:** PLAN_ONLY / HYPOTHESIS, current v0.18.2 template synchronization; **DRAFT — NOT PUBLISHED**. Native validation NOT_RUN.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original 1jehuang/jcode at current original HEAD 553db90882164c47a986f13e79541bddc7a9b723, first-party entrypoints [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs). The canonical historical research HEAD remains be8c61678d2eb7e49dc9540a58ddf89e3ca798ab; accepted historical Index https://github.com/opensiro/vsm-harness-index/blob/b6318e9fb855c20a0a48dfd0ea03f78aaafbb320/assessments/jc/jcode.md reviewed at 5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe. The supported local first-party runtime and its explicit optional modes are the unit of analysis. Original project's own CI, third-party provider, external management and parent owner are not silently counted as agent functions.

**Target transition:** S3*=— -> S3*=C

**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** S1/S2/S3 are already historically agent-owned. Only independent complementary outcome review is a conditional candidate; S4 remains unproven, S5 parent-reserved. Reuse historical S1=A · S2=A · S3=A · S3*=— · S4=— · S5=— without changing the Index. Supporting runtime permissions and transport are not themselves autonomous decisions.

**Function witness:** A worker reports done while source artifacts are absent, stale or not at the claimed location; this is an original reporter scenario, not an independently reproduced defect. The legitimate independent choice and owner: the jcode swarm coordinator decides whether an assigned plan item can be treated as complete and what a worker should do next. PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. The effect and feedback must be A version-matched hold/requeue or acceptance changes the next runnable plan item and reaches the coordinator; a later plan observation reflects that outcome..

**Counterfactual owner test:** Remove the optional developer-composed S3* decision actor but keep current source machinery: First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. The specific extra choice would then be missing: A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report.. A mere generic hook or another model call does not count.

**Possible methodological negative control:** If baseline first-party code already closes the exact owner/choice/effect/return at the supported boundary, or only a human parent may choose, report native equivalence and withdraw the new C design rather than regrade.

**Contributor / maintainer priorities:** NOT_STATED as approval of this exact VSM construction; third-party product direction remains the maintainer's.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. First-party pinned source: [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs).

**Closest existing solution:** Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error.

**Relevant original Issues/PRs:** https://github.com/1jehuang/jcode/issues/1403 (OPEN, reported wrong/missing output); prior case also references #2239 and unfinished #2240, whose current head requires fresh verification.. Labels such as OPEN or CLOSED are current at this follow-up only where checked; unverified heads are not treated as merged.

| Required C link or operator outcome | Track A: shipped/current source | Track B: minimum integration | Falsifier |
| --- | --- | --- | --- |
| Bounded whole-function decision | First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. | PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. | A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. |
| Lawful downstream effect | Source entrypoints at crates/jcode-app-core/src/server/comm_plan.rs and crates/jcode-plan/src/lib.rs | A version-matched hold/requeue or acceptance changes the next runnable plan item and reaches the coordinator; a later plan observation reflects that outcome. | Missing, stale, self-authored, revoked or mismatched reviewer evidence cannot mark an audit-required plan task completed; no-audit deployments retain the current plan workflow. |

**On-top distinctness:** A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. First prefer the exact native solution; a copied supervisor abstraction is insufficient.

**Source ambiguity / rights blockers:** Future source HEAD/PR changes, reviewer identity, permission of the original owner, and tests are unverified. A matched fork research write does not authorize external original actions or code changes. No evidence-free demand assumption.

## 3. Minimal complete S3* first-party C construction

**Required property:** A first-party S3*-specific path to install a legitimate autonomous decision owner, enforce its selected lawful alternative, and return later operational evidence.

| Necessary native component or port | Existing first-party source | Smallest proposed change / integration | Legitimate owner, effect, return |
| --- | --- | --- | --- |
| Decision evidence and invocation | [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) | A developer-composed independent read-only verifier evaluates the exact candidate task result against authoritative artifacts and plan version, returns PASS / RECHECK / UNKNOWN, and makes coordinator hold, requeue or accept before later dispatch. | the jcode swarm coordinator decides whether an assigned plan item can be treated as complete and what a worker should do next |
| Bound decision and later feedback | [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs) | A version-matched hold/requeue or acceptance changes the next runnable plan item and reaches the coordinator; a later plan observation reflects that outcome. | PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. |

**Architectural C-sufficiency argument:** Native baseline: First-party versioned shared plans, coordinator-only approve_plan and task progress; checks of DAG consistency and worker reports are present. The upstream reporter in issue #1403 alleges absent/wrong-location outputs, not independently reproduced. The key residual is A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. The strongest scoped optional solution is A developer-composed independent read-only verifier evaluates the exact candidate task result against authoritative artifacts and plan version, returns PASS / RECHECK / UNKNOWN, and makes coordinator hold, requeue or accept before later dispatch. Alternative one: use native/manual Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error. Alternative two: avoid building if protected authority or actual feedback cannot be established. This proposal claims constructibility, not new implemented grade.

**Explicit non-goals:** No unrelated function upgrades, blanket task guardian, unrequested S5 authority, generic provider dependency, automatic external PR, or forced adoption.

**Implementation dependency graph:** Verify pinned current source and accepted assessment -> resolve P1 native rights/overlap/feedback proof -> implement minimal P0 only with separately authorized product work -> run native positive/negative closure tests -> reconsider adoption based on measured benefit.

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** P0 is Opt-in first-party version-bound independent audit actor on an authoritative worker-result candidate, with read-only independent judgment PASS/RECHECK/UNKNOWN, explicit S3 reconciliation and later task-control feedback. P1 is Reproduce #1403 and compare native cheapest A/B/C; review #2239/#2240 and overlapping hook/trust/agent PR diffs; verify supported runtime, authorization, stale-version controls and native acceptance.. Priorities are inherited, not newly changed.

**P2:** NONE. No forced second VSM function.

**Alternative path:** Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error.. Prefer this if it closes the same operator outcome with no independent C need.

**Stop:** Complete native equivalence, impossible independent actor right, no enforced return, policy veto or missing indispensable evidence triggers NO_GO/BLOCKED under the parent protocol. A missing measured saving is not by itself NO_GO.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** Original Rust plan/server test entrypoints exist at crates/jcode-app-core/src/server/comm_plan_tests.rs and crates/jcode-plan/src/lib.rs. Native commands NOT_RUN; no claimed CI pass.

**Positive functional closure:** Construct two identical candidate results with different independently observed artifact facts; verify only the genuine one can close audit-required plan work and subsequent worker scheduling follows the decision.

**Independent alternative (where applicable):** PASS / RECHECK / UNKNOWN before a protected plan task is closed; no reviewer may change the shared plan directly or override the legitimate coordinator. A genuine owner should be able to make two lawful different choices under different bounded contexts, not simply follow an always-grant rule.

**Negative authority and compatibility (where applicable):** Missing, stale, self-authored, revoked or mismatched reviewer evidence cannot mark an audit-required plan task completed; no-audit deployments retain the current plan workflow.

**Matched native alternative:** Use current coordinator/plan checks and a direct artifact presence/path check first; a generic extra reviewer is not justified without an observed residual error. Execute the same task once with current native behavior and once with conditional construction. No results or economics have yet been collected.

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Primary falsifier:** Shipped native verification already changes the same lawful outcome without independent audit, or no genuinely independent actor can affect later S3 decisions.

**Validation state:** NOT_RUN; proposal only, no native tests.

**Ownership of truth:** Profile owns semantics; Skills owns assessment method; Index owns historical accepted classification; original 1jehuang/jcode owns product change and maintainer choice; the [roadmap.md](roadmap.md) case receipt owns these decisions.

**Cost status:** NOT_MEASURED.

**Next permitted action:** Source-verify the narrow A/B comparison at current original HEAD and test scope under new explicit permission, or keep this as an unpublished research case.

**Human backlink:** [issue.md](issue.md); **case receipt:** [roadmap.md](roadmap.md).

**AI disclosure:** Drafted with AI; no native execution, maintainer consent, economic proof or independently verified value claimed.
