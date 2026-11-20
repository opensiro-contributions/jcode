# jcode — Capability Roadmap Receipt (fresh independent v0.18 re-run, 2026-11-19)

## Identity and pins
- Original repository: 1jehuang/jcode
- Original HEAD: be8c61678d2eb7e49dc9540a58ddf89e3ca798ab
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/b6318e9fb855c20a0a48dfd0ea03f78aaafbb320/assessments/jc/jcode.md
- Accepted assessment blob SHA: 26ab988dd6ef8fb1ddbab8e8fff8c3202781eed4
- Accepted review ref: 5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe
- Accepted reviewed at: 2026-09-17
- System in focus: One installed first-party jcode coding swarm (server, coordinator, workers, optionally TUI reviewer) at pinned original master; excludes Desktop, external governance and unmerged changes.
- Index commit: b6318e9fb855c20a0a48dfd0ea03f78aaafbb320
- Index catalog blob: 8609180ea6b25cc0d3e51e3c8111f2a4ae4f73f7; harness_id jcode; exact repository and review_ref matched, catalog position 82.
- Historic Profile / Methodology: 0.2.2 / 0.3.1; 63 calendar days since accepted review, re-review recommended (not an automatic change).
- Prior historical case: https://github.com/opensiro-contributions/jcode/blob/c98f41c73818ed7bdeed32d8ab76129a342a91fa/.opensiro/issues/swarm-independent-audit-20261118/roadmap.md ; previous PLAN_ONLY / NEEDS_EVIDENCE without terminal GO/NO_GO/BLOCKED.

## Rights and authority
- MIT original license: https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/LICENSE ; contributor policy: https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/CONTRIBUTING.md (AI-assisted contributions permitted; original issue link required for PR; significant work needs prior discussion).
- Matched actual fork: opensiro-contributions/jcode, verified fork=true and parent=1jehuang/jcode, dedicated opensiro/meta branch, push/admin rights.
- Fork state readback before review: owner_control=ALLOW, attention=ACTIVE; 2026-11-19 owner activation event; later STOP/PAUSE still overrides. ALLOW does not approve public fork Issue/PR or original maintainer communication.
- No external publication or product implementation authorized by this proposal.

## Existing work / overlap

### v0.18.2 bounded original-source and human-template checkpoint — 2026-11-20

A source-first same-case check was sealed at [Upstream #58](https://github.com/opensiro/upstream/issues/58#issuecomment-7047329680) before the prior fork record was read. Current public original default HEAD 553db90882164c47a986f13e79541bddc7a9b723 (distinct from receipt historical Original HEAD be8c61678d2eb7e49dc9540a58ddf89e3ca798ab) was read at [crates/jcode-app-core/src/server/comm_plan.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-app-core/src/server/comm_plan.rs) and [crates/jcode-plan/src/lib.rs](https://github.com/1jehuang/jcode/blob/553db90882164c47a986f13e79541bddc7a9b723/crates/jcode-plan/src/lib.rs); status of issue/PR overlap: https://github.com/1jehuang/jcode/issues/1403 (OPEN, reported wrong/missing output); prior case also references #2239 and unfinished #2240, whose current head requires fresh verification..

The scoped new-source first pass asks: A distinct independent evidence owner and version-bound audit-required disposition are not proven by a coordinator plan approval or worker self-report. **No newly demonstrated changed C ownership or Index regrade** is asserted. Previous canonical proposal remains **GO / NEEDS_EVIDENCE**, \`S3*=— -> S3*=C\`, with native tests \`NOT_RUN\`, cost \`NOT_MEASURED\`. This is a Human/AI template-compliance repair and bounded current-source note, **not a duplicate independent original research case, code implementation, or public outreach**. The old receipt/head and first-attempt lineage remain readable in Git history and in the existing fields above.

- SHIPPED: https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/docs/SWARM_ARCHITECTURE.md ; https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-plan/src/lib.rs ; https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-app-core/src/server/comm_control.rs ; https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-app-core/src/server/swarm_todo_link.rs ; https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-tui/src/tui/app/commands_review.rs .
- ISSUE_ONLY: https://github.com/1jehuang/jcode/issues/1403 (author reports 4 missing and 1 wrong-location outputs among 12; not independently reproduced), https://github.com/1jehuang/jcode/issues/2239 (acceptance command/retry/handoff), https://github.com/1jehuang/jcode/issues/2208 (branch/PR churn).
- OPEN_PR (unmerged at review): https://github.com/1jehuang/jcode/pull/2240 head 1e4c838ab641591daa5ca4ac224e50fcefba8b4b (unfinished lane guard with pending unreadable-task review comment); https://github.com/1jehuang/jcode/pull/2035 head a76013e3fd2f4ea26923c9426388dc3e477ce173 (hooks); https://github.com/1jehuang/jcode/pull/2038 head 1158be3f60e0bbda4160c50a57fbd4fe08c7b4da (trust); https://github.com/1jehuang/jcode/pull/2040 head 931efba379a658a7d7fdaae7a5ab09cf883d61e6 (agent definition); https://github.com/1jehuang/jcode/pull/2041 head 926e6383ee84cb6cb37e30c69c10003714484a53 (agent policy).
- Removed previous swarm-deep critique/verify gates: direct documented source above. No older OpenSiro verdict used to select new P0.
- Cheapest alternative: built-in coordinator/task verification or original Issue #1403 artifact presence/path checks, not an automatic new VSM controller.

## Function ownership
- Accepted VSM vector: S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—
- S1 disposition: ALREADY_A — named coding agents execute work; additional C has no demonstrated independent need.
- S2 disposition: ALREADY_A — server plan dependencies, messaging and file-change notification coordinate writers; no justified second C.
- S3 disposition: ALREADY_A — root coordinator steers assignment/retry and current plan; preserve decisive S3 rights.
- S3* disposition: C_CANDIDATE — separate review sessions exist, but a developer-installed independent reviewer with audit-required plan disposition and S3 feedback is not demonstrated.
- S4 disposition: UNKNOWN/NO_TARGET — ambient/memory examples do not prove a separately required in-boundary prospective strategic C; revisit on environmental-change counterexample.
- S5 disposition: PARENT_RESERVED/NO_TARGET — mission, identity and ultimate policy remain with user/project owner; cannot invent local autonomous authority.

## Capability priority
- Receipt contract: proposal-gate
- Repository-wide source map: Six-function census above spans workers, plan/coordination, coordinator current control, read-only review, ambient/memory, and parent user/project governance.
- Priority rationale: Only historic S3* lacks demonstrated independent function-specific decision/feedback with an observed residual wrong-result operator scenario; S1/S2/S3 already A, S4 not evidenced, S5 parent-reserved.
- Target transition: S3*=— -> S3*=C
- P1 dependencies: Reproduce #1403 and compare native cheapest A/B/C; review #2239/#2240 and overlapping hook/trust/agent PR diffs; verify supported runtime, authorization, stale-version controls and native acceptance.
- P2 optional: NONE
- Proposed C construction: Opt-in first-party version-bound independent audit actor on an authoritative worker-result candidate, with read-only independent judgment PASS/RECHECK/UNKNOWN, explicit S3 reconciliation and later task-control feedback.
- C sufficiency falsifier: Shipped native verification already changes the same lawful outcome without independent audit, or no genuinely independent actor can affect later S3 decisions.
- Scenario basis: OBSERVED
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Compare #1403-style native artifact checks with independent read-only reviewer on correct/missing/wrong-authoritative-path output; guard unauthorized/stale/absent actor and cross-mode baselines.
- Validation state: NOT_RUN
- Proposal falsifier: Existing simpler first-party path achieves the same operator outcome, no distinct reviewer decision is possible or audit cannot return to S3.
- Result: PLAN_ONLY
- Cost status: NOT_MEASURED

## Parallel contribution-on-top review
- Evaluation object: An additional first-party developer-composable independent S3* audit-and-return constructor for swarm task completion, not a generic completion fix.
- Existing-work overlap: Native plan, session review, worker report, original Issue #1403 and live #2239/#2240 + pending hooks/trust/agent PRs supply parts but not a confirmed independent plan-audit closure.
- Our on-top contribution: Reuse current plan/current-control and read-only reviewer primitives; add only registration of independent audit actor, exact candidate evidence, version/rights-bound decision and S3 feedback applying hold/accept/retry.
- Incremental benefit: Detect wrong authoritative outcome even when worker checks and marked tasks pass, giving S3 different lawful task disposition; hypothetical benefit beyond reported #1403 failure, not measured.
- Decision scope: Proposal-stage GO only; no product edits, external Issue/PR/comment, tests or canonical Index regrade.

| Function-specific C link | Track A native / overlap | Track B on-top change | Falsifier |
| --- | --- | --- | --- |
| Actual independent audit | Current TUI review sessions but no mandatory swarm lane gate | Developer installs a distinct read-only reviewer for selected tasks | Existing native independent actor already does equivalent audit |
| Evidence and optional policy | Native task/plan states, worker messages; #1403 verification ISSUE_ONLY | Bind task ID/version, authorized scope, authoritative diff and check results into audit candidate | Simple artifact verification suffices |
| Decisive feedback | S3 coordinator requeues; #2240 adds pending unfinished-lane test | Accept/hold/retry only after independent reviewer PASS/RECHECK/UNKNOWN and exact version/rights check | Audit report cannot change later S3 or S1 action |

## Implementation options
- P0: scope a first-party optional S3* audit integration above the native plan and TUI reviewer, only after P1 source and actor tests; do not duplicate PR #2240 completion checks.
- P1: native source/rights preflight and acceptance validation, including reporter Issue #1403, case #2239 and current PR heads/diffs.
- P2: NONE. Prefer first-party native check if it solves the same outcome.
- Developer counterfactual: without independently installed model-backed reviewer, transport and self-report remain but no separate scrutiny/alternative independent audit choice is made; S3 still owns current decisions.
- Positive prospective witness: correct artifact accepted; wrong-authoritative-path output held after independent RECHECK; later coordinator recovery observed.
- Negative prospective witness: stale/absent/revoked/self-review receipts not applied, no silent audit-required completion; feature-off baseline unchanged.
- Native tests: NOT_RUN; future jcode-plan and jcode-app-core targeted swarm tests only when code/proposed scenario exists.
- Contributor interest: NOT_STATED (original Issue reporter expresses artifact verification interest, not OpenSiro S3* adoption).

## Specification and domain alternatives
- Original-native #1403 fix first; separate Profile/Skills semantics feedback if first-party S3* meaning is disputed; separately authorized MIT domain fork experiment as optional comparator. None executed.
- Source drift + 63-day Index age trigger an Index-owned source-pinned re-review recommendation; an unmerged or unperformed re-review is not accepted evidence.
- Historical comparison, AFTER independent decision: previous 2026-11-18 PLAN_ONLY / NEEDS_EVIDENCE conditional S3* proposal; new v0.18 independent scoped GO / NEEDS_EVIDENCE with additional original #2239/#2240 overlap and falsifiers. No old terminal verdict existed to overwrite.

## Cost experiment
- Compare native source path/commit checks versus opt-in independent S3* audit for matched cases. Track completion accuracy, review latency, added runtime tokens, design/build/test/review/integration/maintenance effort.
- Cost status: NOT_MEASURED

## Delivery and publication
- Result: PLAN_ONLY
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Validation state: NOT_RUN
- External issue: DRAFT — NOT PUBLISHED
- Current owner permission: ACTIVE / ALLOW for fork metadata; NOT third-party/public publication consent.
- Source output: [Human](issue.md), [AI/developer](constructor-sufficiency.md), [canonical receipt](roadmap.md).
- No native code, public fork Issue/PR, original PR/comment/Issue, independent tests, claimed measured savings or accepted Index upgrade.
