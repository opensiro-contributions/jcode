# jcode — independent S3* construction sufficiency (AI/developer)

**Target transition:** S3*=— -> S3*=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[issue.md](issue.md) · [roadmap.md](roadmap.md). This contract implements the canonical receipt decision only as a future architecture hypothesis. No new current VSM grade, product patch, tests or outside publication.

## Functional boundary and independent counterfactual

Focus: one installed jcode server/swarm coding team with its root coordinator, workers, authoritative working tree and optional TUI reviewer, at original master be8c61678d2eb7e49dc9540a58ddf89e3ca798ab (2026-11-19). Jcode Desktop, external project-governance actors, unmerged branches and historical removed swarm-deep gates are excluded.

Historical Index ownership is **S1=A · S2=A · S3=A · S3*=— · S4=— · S5=—**, [accepted source](https://github.com/opensiro/vsm-harness-index/blob/b6318e9fb855c20a0a48dfd0ea03f78aaafbb320/assessments/jc/jcode.md), 2026-09-17 at 5f33d6239b56b3d381d6b2c0e9b151eef0b54cbe, Profile 0.2.2 / Skills 0.3.1. The [roadmap.md](roadmap.md) six-function dispositions are authoritative: S1 workers produce; S2 regulates interference; S3 is sole current task-control owner; independent S3* must detect deviations and feed S3, without taking S3 or parent's S5 powers; S4 is not an evidenced target.

**Counterfactual:** if the separately configured model-backed auditor is absent while worker reports, server events and simple file checks remain, no independent judgment about authenticity/relevance of accepted work would be made. If native artifact checks alone suffice, then do not build this proposed actor. S3 may refuse acceptance on its own but that is not independent S3* closure.

## Source-pinned native Track A versus on-top Track B

| Required function link | Track A: shipped / pending | Track B minimum delta | Falsifier |
| --- | --- | --- | --- |
| Independent read-only access | [Reviewer sessions](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-tui/src/tui/app/commands_review.rs) SHIPPED, but session-oriented | Explicit opt-in audit actor registration for a worker-lane result, first-party supported server mode | Already installed reviewer evaluates same result and returns independent decision |
| Candidate evidence | [Plan](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-plan/src/lib.rs) and [lane sync](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-app-core/src/server/swarm_todo_link.rs) SHIPPED; #1403 ISSUE_ONLY | Capture immutable task ID, plan version, expected scope, source revision, actual changed artifacts, executable check reports | Cheapest native check reliably rejects wrong authoritative file |
| Completion barrier | [Control](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/crates/jcode-app-core/src/server/comm_control.rs) SHIPPED; [#2240](https://github.com/1jehuang/jcode/pull/2240) OPEN head 1e4c838ab641591daa5ca4ac224e50fcefba8b4b | For audit-required tasks defer acceptance until eligible signed/attributed reviewer decision is reconciled at exact version | Existing completion gate already provides distinct independent judgment |
| Choice and return | Coordinator can requeue; [#2239](https://github.com/1jehuang/jcode/issues/2239) ISSUE_ONLY describes worker check/retry/report | Separate auditor PASS / RECHECK / UNKNOWN, durable decision evidence, S3 hold/retry/accept and subsequent worker action | Reviewer only sends a DM and S3 never changes the plan |

Current [Swarm Architecture](https://github.com/1jehuang/jcode/blob/be8c61678d2eb7e49dc9540a58ddf89e3ca798ab/docs/SWARM_ARCHITECTURE.md) explicitly says older swarm-deep critique/verify gates were removed. [#2035](https://github.com/1jehuang/jcode/pull/2035) OPEN head a76013e3fd2f4ea26923c9426388dc3e477ce173 brings worker lifecycle observers; [#2038](https://github.com/1jehuang/jcode/pull/2038) OPEN head 1158be3f60e0bbda4160c50a57fbd4fe08c7b4da addresses trust; [#2040](https://github.com/1jehuang/jcode/pull/2040) and [#2041](https://github.com/1jehuang/jcode/pull/2041) OPEN define/select roles. None is presumed merged or a completed audit constructor. Critically, PR #2240 has review concern that unavailable worker task data may be treated as empty; this is an in-flight native bug, not proof of a fresh S3* actor.

## Minimal complete first-party constructor hypothesis

**Proposed developer interface**, not a shipped API:

| Port / state | Existing support | Smallest new source-native behavior and actual actor |
| --- | --- | --- |
| Candidate identity and evidence | VersionedPlan, server task/assignment state, worker completion and repository revisions | Server snapshots TaskResultCandidate (swarm, task ID/version, worker, expected path, original revision, candidate diff, report/check results) on a pending audited completion |
| Independent actor registration | Separate read-only reviewer sessions and optional named agents (some agent-definition PRs still open) | Developer registers a non-worker reviewer and task scope in supported configuration; reviewer sees immutable candidate and only read-capable access; parent chooses whether audit is required |
| Audit decision and return | S3 coordinator task-control commands, plan events and persistence | Reviewer returns PASS, RECHECK or UNKNOWN plus source evidence; server verifies actor identity, task version, source revision, policy and independent role, persists receipt; S3 applies accept/hold/requeue and subsequent task dispatch |
| Guarded compatibility | Native non-audit task path | On disabled/unsupported mode keep old native semantics; on enabled audit require explicit eligible result, otherwise leave safe pending state; no silent completion for unavailable reviewer |

**C sufficiency if constructed:** an independent developer-composed autonomous audit actor chooses between lawful alternatives, its decision is checked/enforced through first-party source and changes S3's later live task execution, with observable feedback. Generic hook subscription, a deterministic file-existence boolean, an unconsumed reviewer DM or a label named "auditor" does not establish S3* C. S3 retains assignment rights and the user retains ultimate policy.

## Priority, tests, falsifier and alternatives

P0 is the version-bound, independent S3* actor/decision/return construction above. P1: reproduce reporter's [#1403](https://github.com/1jehuang/jcode/issues/1403) failure modes, test native proposal A/B/C first, inspect #2239/#2240 head and ownership, identify backend support across TUI/headless modes, build smallest opt-in interface, and test version/authorization. P2 NONE. Do not use new branch/PR as a substitute for owner interest; [#2208](https://github.com/1jehuang/jcode/issues/2208) records maintainer-side churn concern.

| Future native experiment | Expected first-party S3* closure | Abort if |
| --- | --- | --- |
| Correct candidate with reviewer PASS | Exact version-bound receipt leads S3 to accept and release dependent task | A report alone is marked success |
| Wrong authoritative file but all worker tasks ended | Independent reviewer RECHECK -> S3 holds and sends corrective instruction | Simple native artifact check already catches the same case with same benefit |
| Missing/revoked/self reviewer | No unauthorized decision; audited task not silently accepted | Unauthenticated response is applied |
| Stale version or modified worktree | Receipt rejected and fresh review required | Old evidence approves a new snapshot |
| Feature off and supported other modes | Existing native completion preserved | Opt-in audit silently changes every task |

Prospective native commands include cargo test -p jcode-plan and relevant jcode-app-core swarm/control suites. **NOT_RUN**: this is a proposal-stage review; current main may contain unrelated failing native tests. **NOT_MEASURED**: compare end-to-end engineering effort, acceptance correctness, latency and ongoing runtime tokens with the cheapest native validation.

**Research falsifier:** demonstrate that first-party native artifact/command verification produces the same acceptance outcome without independent function-specific judgment, or that required actor rights cannot be safely installed. If so, **NO_USEFUL_CHANGE** for the additional S3* constructor. Only an Index re-review may later regrade real shipped behavior.

**Handoff:** canonical [roadmap.md](roadmap.md); prior [2026-11-18 historical decision](https://github.com/opensiro-contributions/jcode/blob/c98f41c73818ed7bdeed32d8ab76129a342a91fa/.opensiro/issues/swarm-independent-audit-20261118/roadmap.md) stays in provenance. No external original/fork communication or implementation authorization.
