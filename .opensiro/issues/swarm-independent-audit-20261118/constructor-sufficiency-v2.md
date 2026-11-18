# jcode — S3* candidate C constructor and acceptance (AI/developer)

**PLAN_ONLY / NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**.  
Human decision: [issue-v2.md](issue-v2.md). Same **historical** vector `S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—`; same **P0 conditional independent S3***, **P1 qualification/dependencies**, **P2 NONE**. Not a shipped C.

## Functional scope: S2 vs S3 vs S3* vs S4 vs S5

S2: existing inter-agent scheduling; S3: existing coordinator's decisive current whole-swarm task control; S3*: genuinely independent access and audit of results, with actionable feedback to S3; S4: separate prospective external adaptation (not targeted); S5: ultimate legitimate policy, not generic permission filtering.

## 1. Boundary, baseline and counterfactual

Original first-party [jcode master f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745](https://github.com/1jehuang/jcode/commit/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745); standard server/swarm/CLI, with relevant TUI reviewer sessions. Exclude Jcode Desktop, private extensions, unmerged PR code and removed `swarm-deep`. Historical Index [assessment](https://github.com/opensiro/vsm-harness-index/blob/42dc230289bb5992bc3588fa5376b817b282a0fd/assessments/jc/jcode.md), assessed `5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe`, 2026-09-17, Profile 0.2.2 / Skills 0.3.1.

An operator needs independently observed evidence before acceptance of a delegated coding task. The smallest native alternative is the verification proposed in existing [#1403](https://github.com/1jehuang/jcode/issues/1403), and current coordinator checking. Proposed developer counterfactual: compose an autonomous *independent* auditor through first-party supported interfaces; its lawful choice changes later task execution. Verify this is a material improvement before implementation.

## 2. Shipped vs OPEN_PR vs unsupported gap

| Behavior | Source/state | Missing evidence |
| --- | --- | --- |
| Plan/assignment/task progress | [plan](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/crates/jcode-plan/src/lib.rs) SHIPPED | Trace current completion mutation and actual server enforcement |
| Coordinator owner/rights | [swarm](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/docs/SWARM_ARCHITECTURE.md), [control](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/crates/jcode-app-core/src/server/comm_control.rs) SHIPPED | Test return path across supported modes |
| Read-only reviewer sessions | [review code](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/crates/jcode-tui/src/tui/app/commands_review.rs) SHIPPED | Is any review required for task acceptance? |
| Evidence of incorrect completion | [#1403](https://github.com/1jehuang/jcode/issues/1403) OPEN ISSUE | Reporter sample not independently replicated |
| Swarm lifecycle hooks | [PR #2035](https://github.com/1jehuang/jcode/pull/2035) OPEN, head `a76013e3fd2f4ea26923c9426388dc3e477ce173` | Observers cannot establish decisive S3* closure by themselves |
| Trust | [PR #2038](https://github.com/1jehuang/jcode/pull/2038) OPEN, head `1158be3f60e0bbda4160c50a57fbd4fe08c7b4da` | A trust scope is not an independent auditing right |
| Definitions and agent policy | [PR #2040](https://github.com/1jehuang/jcode/pull/2040) OPEN head `931efba379a658a7d7fdaae7a5ab09cf883d61e6`; [#2041](https://github.com/1jehuang/jcode/pull/2041) OPEN head `926e6383ee84cb6cb37e30c69c10003714484a53` | Named persona != independent effectful audit actor |

These PR states are read-back observations, not first-party shipped behavior.

## 3. Conditional minimum S3* source-native construction

| Stage | Proposed first-party port and state | Decision owner / closure |
| --- | --- | --- |
| Disturbance | `TaskResultCandidate{swarm_id,task_id,task_version,authoritative_scope,revision,artifacts}` from server truth, not worker prose | Worker reports; server binds immutable identity |
| Alternatives | `AuditDecision{ACCEPT,REJECT,INCONCLUSIVE,evidence,reviewer}` | Independent developer-installed read-only auditor selects lawful option |
| Construction | Registered audit actor for specified task class and first-party supported runtime, not generic hook substitution | Operator delegates *audit judgment* only |
| Enforcement | Coordinator-only version/rights check before audit-required task acceptance; reject stale/absent/revoked/self-review results | S3 alone changes live plan/task status; parent reserves any ultimate override |
| Return/feedback | `AuditReceipt{task_version,reviewer,decision,source_revision,reason,applied_status,next_operation}` | Durable audit result feeds back to current S3, changes next runnable task |

**Future C sufficiency:** developer can truly supply a separate decisive autonomous audit actor, exercise different lawful choices, and observe enforced changed later S1/S3 operation. No claim that proposed ports are installed, fully reachable, safe or classified C. A built-in artifact-checking boolean alone would not constitute S3* independence.

## 4. Priority dependencies

P1: native matched failure reproductions for #1403; end-to-end completion path audit; compare A/B/C; classify each PR dependency at its pinned head; test independent rights and return closure. P0: only after material delta, implement the smallest first-party, version-bound independent audit/enforcement slice. P2: NONE.

## 5. Optional additional constructor

NONE: no separate justified S4, S5, C(P) or A(P) mode.

## 6. Proposed source-native acceptance (NOT RUN)

| Scenario | Actor / trigger | Required downstream evidence | Fail |
| --- | --- | --- | --- |
| Positive | Worker returns correct artifact; independent auditor ACCEPT | Exact revision accepted, receipt persisted, next dependent task can run | Merely receiving a DM |
| Different lawful choice | Same candidate; auditor REJECT | Task not accepted; remediation returned to coordinator | Core hardcodes accept |
| Wrong path | Worker commits an old copy, not authoritative file | No false acceptance; source path mismatch detectable | Existence check only |
| Missing actor/timeout | Audit-required task lacks auditor | Fail-closed for audited task; ordinary tasks compatible | Silent success |
| Stale/revoked | Task changes post-review or reviewer permission revoked | Old receipt cannot approve new task state | Reused stale proof |
| Unauthorized/self-review | Worker claims to audit itself | No unauthorized status mutation | Role label alone authorizes |
| Native comparison | Simpler #1403 A/B meets same operator need | NO_USEFUL_CHANGE for S3* runtime work | Grade-driven feature |

Potential future native suites: `cargo test -p jcode-plan`, relevant `jcode-app-core` comm/task-control tests and supported-mode integration. **Executed commands/tests: NONE.** Do not invent native test receipts.

## 7. Falsification, ownership, cost and publication

Falsify the proposal if native completion verification already achieves the outcome, if no independent actor can be installed, if S3 ignores its response, if governance forbids decisive rights, or if the source does not support the mode. GitHub original owns issue and PR states; Index alone owns accepted grade. MIT [LICENSE](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/LICENSE), [CONTRIBUTING](https://github.com/1jehuang/jcode/blob/f3fc98fbd8d05fd90a09f42a3cf8b4cc05a57745/CONTRIBUTING.md) supports AI-generated PRs with issue linkage; [#2208](https://github.com/1jehuang/jcode/issues/2208) advises caution on new lanes. Compare native vs VSM-informed all-in costs, **NOT_MEASURED**. Public fork Issue, original comment, external PR and code changes: **NOT PUBLISHED / NOT IMPLEMENTED**. Human [backlink](issue-v2.md).
