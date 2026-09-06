# Senior Engineering Growth Lab

The Growth Lab develops and audits Mahmoud's general software-engineering capability through evidence. It preserves the original Side Track habit: start with real features, bugs, requirements, trade-offs, and production decisions from his frontend work.

It coordinates with the sibling Full-Stack AI Engineering Lab rather than duplicating it. That Lab owns Python, backend/FastAPI, SQL/Postgres in project context, LLM systems, AI application implementation, and their learning sequence. The Growth Lab imports relevant evidence while concentrating on transferable engineering judgment.

## Mission

```text
Assess honestly
→ discover experience, evidence, and unknowns
→ choose one primary and one secondary capability
→ develop them through real work or justified project problems
→ apply it to realistic and real work
→ reassess in a changed context
→ preserve evidence for engineering and interviews
```

Four years of experience is useful context, not proof of seniority. Missing evidence means **Unknown**, not weak. Vocabulary alone is not capability.

## Two connected tracks

### Track A — Real Work Engineering

Use real features, bugs, PRs, production issues, and stakeholder decisions as primary evidence. Reconstruct only the dimensions that matter: problem, constraints, assumptions, ownership, alternatives, failure modes, testing, trade-offs, outcome, and what Mahmoud would change.

Do not turn every work story into a lecture. Extract the hidden principle and update the same capability model used by the Core Lab.

### Track B — Capability Audit & Core Lab

Begin with the text-first **Engineering Discovery Interview** in [growth-ledger.md](growth-ledger.md) after Module 4 and the DeepLearning.AI Python course are complete. Collect real experience first, then use a few selected scenarios across relevant capabilities; existing async/concurrency and testing priorities are hypotheses. After discovery, develop the selected capabilities through real workplace cases and justified Full-Stack project problems. Use short code reading, debugging, implementation, refactoring, design defense, and changed-context checks when evidence justifies them:

```text
Real problem/constraint → inspect evidence → relevant concept → implement → debug/refactor
→ defend trade-offs → changed-context recheck → evidence update
```

Every principle must eventually appear in a situation where Mahmoud must use it or reject it.

## Capability coverage

The living map in [growth-ledger.md](growth-ledger.md) covers:

- JavaScript, TypeScript, browser/web fundamentals, Vue/frontend architecture, and CSS/UI engineering
- practical data structures and algorithms, OOP, SOLID, and design patterns
- application architecture, gradual system design, databases/SQL, networking/HTTP/APIs
- testing, debugging, performance, security, async/concurrency
- Git, code review, delivery, reliability, observability, and accessibility
- product judgment, technical leadership, and technical communication

This is a map, not a linear syllabus.

## Evidence and progression

Evidence is graded by both level and source quality. Production evidence is strongest; independent unfamiliar lab work, cold rechecks, guided work, and verbal knowledge follow. Guided success is learning evidence, not independent mastery.

The Growth Lab keeps one source of truth: [growth-ledger.md](growth-ledger.md). It contains the capability map, evidence log, meaningful decisions, career-evidence candidates, the small improvement backlog, and reassessment state.

Default focus is limited to:

- one primary capability selected after discovery;
- one secondary or reinforcement area;
- maintenance through real work.

## Cross-project coordination

The two Labs contribute to one capability picture while retaining clear ownership.

| Full-Stack AI Engineering Lab owns | Senior Engineering Growth Lab owns |
|---|---|
| Python, backend, AI implementation, and their curriculum | Broader SWE depth, frontend, architecture, CS fundamentals, and system design |
| Practice and projects that specifically reinforce those domains | Senior judgment, real-work analysis, leadership, interview readiness, and broader CV/LinkedIn/application preparation |
| Its detailed learning records and artifact evidence | The broader capability profile and cross-domain interpretation of that evidence |

When current evidence in Python, backend, AI, debugging, testing, deployment, or project work matters, first consult the sibling Lab's read-only `PROGRESS.md`, `CAREER_EVIDENCE.md`, and `ROADMAP.md`. Inspect deeper files only when a specific claim needs verification. Imported evidence keeps its original conditions and limitations; a status label is never upgraded merely because it appears in another ledger.

If a gap belongs in Python, backend, or AI practice, this Lab emits a concise **Cross-Project Handoff** with the observed gap, evidence, why it matters, and suggested practice. The sibling Lab decides where that practice fits its roadmap; this Lab does not create a parallel curriculum.

## Modes used when appropriate

- **Real Work Case:** compact analysis of an actual engineering situation.
- **Engineering Discovery:** conversational, text-first evidence gathering, one question at a time; use the ledger's practical coverage and seniority criteria without creating a syllabus.
- **Core Lab:** focused capability development through real work or justified project problems, with fading scaffolding.
- **Incident:** symptoms first; observe, hypothesize, isolate, mitigate, fix, prevent recurrence, and summarize.
- **Architecture Defense:** defend boundaries and trade-offs without buzzwords.
- **Hard Interview:** after discovery, use voice-based hard interviews at meaningful project, project-defense, or interview-readiness milestones; no teaching or normal hints during the interview, with structured feedback afterward.
- **Market Calibration:** every 4–6 weeks or at a milestone, use repeated target-role signals rather than one listing or trend.

## Chat continuity

Project files—not chat history—hold durable learner state. A fresh chat starts with [CURRENT_STATE.md](CURRENT_STATE.md), then loads only the ledger sections and supporting records required for its task. Deeper history is consulted only when a decision needs it; cross-project work follows the same summary-first rule.

Continue a chat while its outcome and reasoning context remain coherent. Recommend a clearly named fresh chat when the thread becomes noisy or repetitive, crosses a major milestone, begins a distinct outcome, or would benefit from clean context. Calendar dates and message counts are not split criteria.

Before recommending a new chat, persist meaningful evidence and decisions, synchronize the ledger and priorities, record unresolved gaps and the exact next action, and update `CURRENT_STATE.md`. Then provide a one-line opener directing the fresh chat to that file and its recorded action.

## Workspace

```text
senior-engineering-growth-lab/
├── AGENTS.md
├── CURRENT_STATE.md   # Lean fresh-chat resume index
├── README.md
├── growth-ledger.md
├── daily-revision/     # Short learner-owned conclusions
├── case-studies/       # Meaningful real-work cases when needed
└── checklists/         # Reusable workflow prompts when needed
```

Start from [CURRENT_STATE.md](CURRENT_STATE.md) and its completion trigger. Consult the preserved [Day 1 foundations](daily-revision/day-01-foundations.md) only when relevant. Keep documentation lightweight: record only material that changes future decisions.
