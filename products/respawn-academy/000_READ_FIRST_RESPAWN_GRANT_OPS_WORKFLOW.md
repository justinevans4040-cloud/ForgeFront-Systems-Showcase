# RESPAWN ACADEMY GRANT FUNDING

## 000 — READ FIRST / MANDATORY RESPWAN GRANT OPS WORKFLOW

**Effective:** September 3, 2026

**STATUS: HARD EXECUTION GATE**

This file defines the mandatory operating workflow for the Respawn Grant Funding project. It must be read before any code, implementation, file modification, registration change, deployment change, grant-submission change, or other behavior-changing work.

Any code or change produced outside this workflow is **INVALID WORK**. It must be discarded and recreated under the correct workflow. Do not salvage, retrofit, or quietly keep non-compliant implementation as production/reference work.

---

# REQUIRED READING ORDER BEFORE ANY CODE OR CHANGE

1. **This file — `000_READ_FIRST_RESPAWN_GRANT_OPS_WORKFLOW.md`.**
2. **`00_READ_FIRST_RESPAWN_GRANT_FUNDING.md` — authoritative Respawn Grant Funding continuation tie-in.**
3. **Latest Respawn Academy Grant Readiness Matrix.**
4. **`WAKE Funding Command — Codex Implementation Manual — Approach 2` — governing approved Funding Command architecture.**
5. **Current DCE Command Center V3 continuation/source evidence** whenever the project-management application is being used or changed.
6. **Current applicable Superpowers skills** required for the work being performed. Never rely on memory of a prior skill version.

If these sources disagree, STOP and resolve the conflict before implementation.

---

# GOVERNING PROJECT DECISIONS

## Respawn Grant Funding

- Accuracy > speed.
- Evidence before claim.
- No shortcuts.
- Do not rebuild established work.
- Do not assume documentation proves implementation.
- Unknown/unverified is a valid status.
- Historical material remains historical until direct evidence upgrades it.
- No duplicate federal registrations.
- No rushed NSF Project Pitch.
- No production-ready, compliance, security, outcome, accessibility, performance, partnership, registration, or market claim without evidence.

## Tools and skills

Use available tools, connected sources, installed skills, validators, artifact tooling, source inspection, and automation whenever they materially improve accuracy, grounding, verification, or execution.

Manual reconstruction is not a substitute for retrieving the authoritative source when a tool can retrieve it.

## Reuse rule

Programming assets may be copied into this project from any authorized project, repository, engine, agent, archive, or application, including `.py`, JavaScript, TypeScript, JSON, schemas, utilities, components, test harnesses, and patterns.

**COPY ONLY.** Reuse does not authorize modification of the source project, engine, agent, repository, runtime, deployment, website, or application. Original assets stay untouched unless Justin separately authorizes a source change.

---

# PROJECT-MANAGEMENT APPLICATION WORKFLOW

Respawn Grant Funding will use the existing **DCE Command Center V3 / ForgeFront Command Center** project-management application as a real-world operational test case.

The authoritative DCE/Solar Command source is **protected**. Do not edit it in place.

### Required workflow

1. Locate the exact authoritative DCE Command Center V3 source.
2. Prefer direct authoritative source retrieval over reconstruction from snippets or screenshots.
3. If the source must be retrieved from Ichabod, use SSH **read-only** to locate it, inspect metadata/hash it, and copy only the required source bytes.
4. Do not modify Ichabod while locating or copying the source.
5. Do not modify DCE/Solar Command, its production deployment, its canonical repository, or its working application.
6. Create an **isolated Respawn Grant Ops test copy/workspace**.
7. Seed the isolated copy with Respawn Grant Funding project data from the current Readiness Matrix and approved evidence.
8. Use the real Respawn grant project to test project-management workflows, gates, tasks, evidence, risks, decisions, deadlines, pilot pipeline, market work, budgets, and application readiness.
9. Any bug, missing field, poor workflow, UI problem, reporting weakness, or feature gap discovered becomes **test evidence** for the isolated copy.
10. Fixes/features are made only in the isolated test copy unless Justin separately authorizes integration into the original app.
11. No external/production deployment of the test copy without separate explicit approval.

### Required Respawn Grant Ops project structure

- Project: **Respawn Academy Grant Funding**
- Current Phase: **Phase 0 — Full Grant Readiness Audit**
- Primary control artifact: **Respawn Academy Grant Readiness Matrix**
- Gates: **Admin → Technical → Market → Pilot → NSF Pitch → Hostile Review → Submission**
- Status vocabulary: **VERIFIED / PARTIAL / MISSING / BLOCKED / PROPOSED R&D / HISTORICAL**
- Tasks: every Required Action from the Readiness Matrix
- Risks: unsupported claims, registration gaps, source gaps, security gaps, benchmark gaps, market gaps, pilot gaps, eligibility and deadline risks
- Evidence: every material claim/task must trace to a source/evidence item
- Decisions: beachhead market, applicant entity, technical objectives, submission target, pilot strategy, budget decisions
- Contacts: pilot candidates and funding contacts only after real contact occurs
- Calendar: NSF deadlines, registration dependencies, pilot milestones, review gates
- Reporting: generated from actual recorded project state, never invented completion

---

# WAKE FUNDING COMMAND WORKFLOW

The approved architecture is **`WAKE Funding Command — Codex Implementation Manual — Approach 2`**.

Do not invent a parallel grant-management architecture.

Funding Command is additive. It must not modify protected WAKE, Athere Mesh, V Prime, ForgeFront, Respawn, DCE/Solar Command, production deployments, or source materials merely for convenience.

Respawn Academy is the reference case for Funding Command. Use Respawn to test whether the system can truthfully answer:

> What capital can this organization legitimately pursue, why, what is blocking it, what evidence would make it competitive, what must be submitted, who owns every step, and how do we execute an award without losing control?

Funding Command must preserve the lifecycle:

**ASSET / ENTITY → OPPORTUNITY → ELIGIBILITY → ADMIN READINESS → PROGRAM ALIGNMENT → COMPETITIVE READINESS → PURSUIT DECISION → EVIDENCE → BUDGET → REQUIREMENT MATRIX → NARRATIVE → REVIEW → SUBMISSION PACK → AWARD EXECUTION → REPORTING → LEARNING LOOP**

Hard eligibility is deterministic. AI may help interpret, rank, summarize, draft, and recommend, but AI may not overrule a hard eligibility failure.

---

# MANDATORY SKILL / IMPLEMENTATION CHAIN

Before implementation:

1. `superpowers:using-superpowers`
2. `superpowers:brainstorming` — recognize the approved architecture; do not reopen it without a real conflict/new scope
3. `superpowers:using-git-worktrees` — establish/verify isolation
4. Inventory exact source-of-truth files/repositories and protected assets
5. Establish clean baseline and run existing tests where applicable
6. `superpowers:writing-plans` — create the exact task-by-task plan before touching code
7. Choose the required execution skill: `superpowers:subagent-driven-development` when available/appropriate, otherwise `superpowers:executing-plans`
8. `superpowers:test-driven-development` for every feature, bugfix, refactor, behavior change, migration, schema/config change, or script that changes behavior
9. RED: write the failing test first
10. VERIFY RED: run it and confirm the expected failure
11. GREEN: implement the minimum code required
12. VERIFY GREEN: rerun the test and surrounding suite
13. Refactor only after green
14. `superpowers:systematic-debugging` before attempting any unexpected-failure fix
15. `superpowers:requesting-code-review` after meaningful tasks/major phases and before integration
16. `superpowers:receiving-code-review` before applying review feedback
17. `superpowers:verification-before-completion` before any claim of done/fixed/passing/ready/complete
18. `superpowers:finishing-a-development-branch` when implementation is actually complete

No automatic merge, protected-system integration, or production deployment is authorized by this workflow.

---

# SKILL INVOCATION LEDGER

Before the first implementation diff, create/preserve a ledger recording:

- skill name
- why it applies
- phase/task
- confirmation the current skill instructions were loaded
- RED test command/result
- GREEN test command/result
- unexpected-failure debugging invocation when applicable
- review gate
- final verification command/result

If required skill usage is missing, the affected implementation is invalid.

---

# SSH / ICHABOD RULE

SSH to Ichabod is authorized as a retrieval path when required to locate authoritative source material for this project.

For source retrieval:

- use SSH read-only first;
- locate exact paths rather than guessing;
- inspect metadata/hash where useful;
- copy required programming assets into the isolated Respawn Grant Ops workspace;
- do not edit, move, delete, reorganize, restart, deploy, or otherwise modify Ichabod or the source application while retrieving material unless Justin separately authorizes that change.

If the terminal/remote connector is unavailable, stop and record the blocker instead of reconstructing the authoritative source from incomplete snippets.

---

# INVALID-WORK CONDITIONS

The affected work is invalid and must be discarded/recreated if any of the following occurs:

- code/change starts before this gate and the authoritative tie-in are read;
- required skills are not actually invoked/read;
- protected source is edited instead of copied;
- work is performed directly in a protected primary checkout when isolation is required;
- production code is written before the failing test is observed;
- an unexpected failure is patched without systematic debugging;
- implementation drifts outside the written plan or approved architecture;
- a source is reconstructed when the authoritative source can be retrieved;
- historical/design evidence is silently promoted to current implementation;
- unsupported grant claims are invented;
- work is marked done without fresh verification evidence;
- a merge, deployment, registration, submission, or protected-system integration is performed without the required explicit approval.

---

# CURRENT CONTINUATION POINT

1. The Respawn Grant Readiness Audit remains active.
2. The Grant Readiness Matrix is the primary control board.
3. The project-management app decision is APPROVED: use DCE Command Center V3 as the base pattern/source for an isolated Respawn Grant Ops test copy.
4. The approved Funding Command architecture is the existing Approach 2 implementation manual.
5. The exact authoritative DCE Command Center V3 source must be retrieved, not reconstructed.
6. If needed, retrieve it from Ichabod via read-only SSH and copy it into the isolated workspace.
7. Original DCE/Solar Command remains untouched.
8. No NSF Pitch submission yet.
9. No production deployment yet.

**This is the mandatory workflow. Anything else is invalid work.**
