# Growth Ledger

Last baseline update: 2026-09-03
Last coordination/operating decision update: 2026-09-05 — capability levels unchanged.

This is the broader software-engineering capability and evidence record for real-work coaching and the Core Lab. It may import read-only evidence from the Full-Stack AI Engineering Lab while preserving that evidence's original conditions and limitations. Levels change only when new evidence justifies them.

## Evidence scale

| Level | Meaning |
|---|---|
| 0 — Unknown | Not meaningfully assessed. This is not a weakness. |
| 1 — Exposure | Recognizes or has used the idea superficially. |
| 2 — Working | Can use it in familiar work. |
| 3 — Independent | Can apply, explain, and debug it in a new problem. |
| 4 — Strong depth | Can compare alternatives, expose failure modes, and review others' work. |
| 5 — Senior evidence | Repeated independent ownership across design, delivery, debugging, review, explanation, and trade-offs. |

Evidence quality, strongest first: **real production evidence → independent unfamiliar lab → cold recheck → guided exercise → verbal knowledge**. A cross-project summary retains the quality and limitations of its underlying evidence; the summary itself does not strengthen the claim. Documentation lookup is normal engineering behavior; trivia recall is not required.

## Baseline capability map

The next-evidence column contains candidate probes, not an assigned sequence or practice checklist. Discovery selects relevant scenarios; coverage that remains untested stays Unknown.

| Capability | Level | Evidence so far | Next evidence needed |
|---|---:|---|---|
| JavaScript fundamentals | 0 | Not assessed | Discovery-selected language/runtime scenario from real experience |
| TypeScript | 0 | Professional use reported; depth not assessed | Unfamiliar API/state type-design task |
| Browser / web platform | 0 | Not assessed | Request/render/security scenario |
| Vue / frontend architecture | 0 | Professional Vue/Pinia delivery reported; judgment not directly inspected | Existing-feature code reading and boundary defense |
| CSS / UI engineering | 0 | Not assessed | Responsive/accessibility implementation or review |
| Python application engineering | 2 | E-002: learner-written foundational capstone and local file/CSV pipelines in the Full-Stack AI Engineering Lab | Changed-context implementation with reduced scaffolding and later cold retention |
| Backend engineering | 0 | Full-Stack AI Engineering Lab roadmap owns this area; no backend-service evidence recorded yet | Import evidence after a tested backend milestone |
| AI application engineering | 1 | E-002: built prompt pipelines and explained the deterministic/LLM and echo-stub boundaries | Import evidence from a real provider integration with evaluation and failure handling |
| Data structures & algorithms | 0 | Not assessed | Practical structure choice with constraints and complexity |
| OOP | 0 | Not assessed | Decide functions vs objects, then implement or reject OOP |
| SOLID | 0 | Not assessed | Diagnose and refactor a painful boundary before naming a principle |
| Design patterns | 0 | Not assessed | Use or reject a pattern for a demonstrated problem |
| Software architecture | 1 | E-001: identified frontend/backend rule ownership with guidance | Independent boundary decision in a changed feature |
| System design | 0 | Not assessed | Small feature design before distributed-scale questions |
| Databases & SQL | 0 | Reserved for coordination with the Full-Stack AI Engineering Lab | Import its evidence, then assess cross-layer reasoning |
| Networking / HTTP / APIs | 1 | E-001: reasoned about structured error codes and shared clients with guidance | Independent API contract and failure-handling task |
| Testing | 0 | E-002: manual execution checks exist, but automated test capability has not been meaningfully assessed | Choose unit/integration/E2E protection for a concrete failure |
| Debugging | 1 | E-002: self-discovered Python control-flow/transfer bugs plus output-led file, reader, and stale-variable repairs; some repairs were guided | Independently run an evidence-led diagnosis loop on an unfamiliar bug and add regression protection |
| Performance | 0 | Not assessed | Measure-first frontend investigation |
| Security | 1 | E-001: recognized frontend validation can be bypassed | Independent trust-boundary scenario and mitigation |
| Async / concurrency | 1 | E-001: stale state and revalidation were understood with guidance | Independent stale-response/race-condition diagnostic |
| Git / code review / delivery | 0 | Repository exists; workflow capability not assessed | Review a diff and form a meaningful delivery plan |
| Reliability / observability | 0 | Not assessed | Failure-mode and production-diagnostic scenario |
| Accessibility | 0 | Tooltip/display ideas appeared, but accessibility was not assessed | Keyboard, focus, and error-state review |
| Product & requirement judgment | 2 | E-001: compared UX options and proposed PO confirmation in a real case | Repeat independently on a different ambiguous requirement |
| Technical leadership & influence | 0 | Not assessed | Real example of review, standards, mentoring, or influence |
| Technical communication | 1 | E-001: explained choices and reasoning informally | Concise written decision/status explanation under challenge |

## Evidence log

### E-001 — Admin reservation eligibility

- **Source:** real-work case discussed with coaching; no PR, code, tests, or production outcome inspected.
- **Demonstrated:** clarified business purpose; recognized admin has no override; compared hide, disable, and fail-later UX; proposed taking a recommendation and rationale to the PO; distinguished shared backend eligibility from frontend presentation; recognized authoritative backend validation and stale state; preferred structured recoverable errors.
- **Supports:** Product & requirement judgment 2; Software architecture 1; HTTP/API 1; Security 1; Async/concurrency 1; Technical communication 1.
- **Limitation:** materially guided. It supports learning and familiar-work reasoning, not independent or senior mastery.
- **Recheck:** use a different domain with ambiguous requirements and no reservation vocabulary.

### E-002 — Full-Stack AI Engineering Lab summary import

- **Source:** read-only review of the sibling Lab's `PROGRESS.md` and `CAREER_EVIDENCE.md` on 2026-09-03; the cited practice artifacts were not inspected in this import.
- **Demonstrated:** learner-written Book Tracker capstone; local file and CSV prompt pipelines; self-discovered Python/JavaScript transfer and control-flow bugs; output-led repair of stale variables and file/reader mistakes; explanation of deterministic filtering versus LLM work and of the echo-stub boundary.
- **Supports:** Python application engineering 2; Debugging 1; AI application engineering 1.
- **Limitations:** work is foundational and mainly tutor-led or familiar-context; some repairs were guided. No automated tests, real model/provider integration, backend service, database integration, deployment, or operational evidence is recorded.
- **Recheck:** import later milestone evidence when those capabilities are demonstrated. Keep Python, backend, and AI-specific implementation practice in the Full-Stack AI Engineering Lab.

### E-003 — Full-Stack Module 3 close summary refresh — 2026-09-05

- **Source:** read-only review of the sibling Lab's [PROGRESS.md](../full-stack-ai-engineering-lab/PROGRESS.md) and [CAREER_EVIDENCE.md](../full-stack-ai-engineering-lab/CAREER_EVIDENCE.md); its practice artifacts were not independently inspected in this import. E-002 remains the historical baseline.
- **Reported milestone:** Module 3 course coverage and comprehensive assessment are closed **Guided overall**, with material scaffolding or repairs in file/CSV lifecycle, aggregation, integration, and boundary reasoning. Module 4 is the next learning action; fragile capabilities retain scheduled cold rechecks in the Full-Stack Lab.
- **Supports:** a current progress summary, not a level promotion. Python 2, debugging 1, and AI application engineering 1 remain unchanged. Course completion does not establish Independent, Retained, Integrated, or Production Evidence.
- **Limitations:** reported clean execution and manual output checks do not establish automated-test, real provider/backend, database integration, deployment, or operational capability. These remain unevidenced here, not proven weaknesses.
- **Testing ownership:** the Full-Stack Lab's first real AI automation includes learner-owned automated regression tests. This Lab assesses broader testing strategy, regression protection, and cross-layer unit/integration/contract/E2E judgment, and imports actual implementation evidence without creating another test curriculum.

## Decision log

### D-001 — Proposed handling of ineligible restaurants

- **Context:** Admin must see restaurants but should not enter an invalid reservation flow.
- **Alternatives:** hide; show disabled with explanation; allow selection and reject on Next.
- **Proposed approach:** show disabled with a clear reason; backend exposes and enforces current eligibility; frontend presents and recovers.
- **Trade-off accepted:** more explicit API/UI states in exchange for visibility, consistency across clients, and earlier prevention.
- **Status:** product confirmation and implementation evidence not recorded.
- **Reconsider if:** admins need an override, eligibility semantics differ by client, or product changes visibility requirements.

## Career evidence candidates

| Candidate | Strength now | What would make it usable later |
|---|---|---|
| Admin reservation eligibility and UX recovery | Developing | Confirm ownership, inspect implementation/tests, record product decision and outcome, and show Mahmoud's independent contribution |

Package evidence into CV, LinkedIn, GitHub, portfolio, or STAR stories only after it is strong and specific.

## Career launch coordination — 2026-09-05

- **Technical owner:** the Full-Stack Lab owns Python, backend, AI implementation, its projects, and the [four-month technical roadmap](../full-stack-ai-engineering-lab/ROADMAP.md) from 2026-09-05 to approximately 2027-01-05 at 15–20 focused hours per week.
- **Target:** January 2027 is an evidence-dependent application launch with one strong deployed flagship and automation/backend evidence. It is not guaranteed readiness or full roadmap completion; the broader 6–9 month estimate for deep completion remains compatible. Do not rush a second project at the flagship's expense.
- **Growth Lab ownership:** November LinkedIn reactivation and role/company tracking using established professional experience; December CV/LinkedIn packaging using only verified, defensible project evidence; January interview and targeted-application preparation and launch as evidence supports it. Preserve raw evidence and assistance limitations before making claims.
- Coordinate within the existing capacity. Do not add a second technical roadmap, curriculum, project, weekly quota, or parallel practice stream; justified remediation replaces planned time rather than adding pressure.

## Current priority hypotheses

- **Async/concurrency:** provisional candidate, currently 1 — Exposure from guided E-001 reasoning. It has not been established as the highest-priority weakness.
- **Testing/regression judgment:** provisional candidate, currently 0 — Unknown; concrete test design has not been assessed.
- **Maintenance:** continue product/requirement judgment through real work. Discovery may confirm or reprioritize the candidates; only then select one primary capability and one secondary capability.

## Engineering Discovery Interview — decision 2026-09-05

### Entry and method

1. Protect the immediate Full-Stack focus: Module 4 and the DeepLearning.AI Python course first. After completion, the first Growth Lab assessment is text-first discovery, conversationally one question at a time. This supersedes the previously scheduled immediate async diagnostic and is not a hard voice interview.
2. Start with Mahmoud's real professional history, responsibilities, projects, features, bugs, architectural decisions, production incidents, teamwork, and ownership. Reuse already recorded context. Distinguish what he personally decided, implemented, reviewed, delivered, and operated from team outcomes.
3. Collect experience and available evidence before selecting a small number of scenarios. Use a real example to explore several relevant capabilities; follow up on causal reasoning, trade-offs, failures, and verification. Do not test every category in one interview or run a trivia quiz per category.
4. Record self-reported experience separately from directly observed reasoning, inspected artifacts, and verified delivery outcomes. Preserve existing evidence, assistance, and limitations. An unanswered or untested area remains **0 — Unknown**; an unsuccessful recall or a missing artifact alone does not establish weakness. Label weakness only when observable reasoning or implementation demonstrates it.
5. Close discovery with an evidence summary distinguishing demonstrated capability, self-reported experience, and Unknown areas, then select exactly one primary capability and one secondary capability with a reason tied to evidence and current work. Maintain other strengths through real work. If selection is not yet supported, record the missing evidence and continue a targeted conversation rather than inventing a weakness or priority.

### Practical coverage reference

Use this reference to choose scenarios after collecting experience. It is neither a syllabus nor a technology checklist, and complete coverage is not required to close discovery.

- **Programming and problem solving:** language/runtime fundamentals; arrays/lists, hash maps/dictionaries, sets, stacks, queues, and trees/graphs when relevant; searching, sorting intuition, recursion basics, traversal, decomposition, and time/space complexity.
- **Code design:** functions versus objects, encapsulation, composition versus inheritance, and appropriate abstraction. Assess SOLID through concrete design/refactoring, and patterns through use, rejection, and trade-offs rather than definitions or pattern names.
- **Frontend and web:** frontend engineering, JavaScript/TypeScript runtime behavior, event loop, asynchronous execution and concurrency, browser/web-platform fundamentals, and frontend/backend integration and contract reasoning.
- **Backend and data boundaries:** networking, HTTP, APIs, distributed-system boundaries; relational databases, SQL, transactions, constraints, indexes, and data modeling. Inspect transferable judgment here; implementation stays in the Full-Stack Lab.
- **Engineering quality and operation:** testing strategy, regression protection, debugging discipline, code-review judgment, security, performance, reliability, observability, and incident reasoning; Git, delivery workflow, CI/CD, deployment, and operational ownership.
- **Architecture and ownership:** architecture/system design, product judgment, ambiguity handling, technical communication, collaboration, technical leadership, and influence.
- **Responsible AI-assisted engineering:** analysis, design, implementation review, and verification with owned reasoning; inspect whether Mahmoud can challenge outputs, explain decisions, and verify behavior without blind dependence.

### Seniority and subsequent development

Assess seniority primarily through ownership, causal reasoning, trade-off judgment, ambiguity handling, failure-mode awareness, debugging discipline, simplification, knowing when to reject a technology or pattern, testing/operational thinking, communication/influence, and repeated delivery evidence. Terminology, confidence, years alone, and technology counts do not establish seniority.

After discovery, develop the selected primary and secondary capabilities through real workplace cases and the Full-Stack Lab's projects. Introduce system-design concepts or technologies only when a real problem, constraint, or measured failure justifies them. Do not force CQRS, Event Sourcing, Redis, RabbitMQ, API Gateway, Keycloak, microservices, or other technologies into a project for resume coverage. Add a focused CS/algorithm interview track later only if repeated target-role evidence demonstrates the need; this coverage reference itself does not authorize a track.

Use hard voice interviews only after discovery, at meaningful project, project-defense, or interview-readiness milestones. Do not create a weekly quota or parallel practice stream. Any focused remediation requires demonstrated material weakness and replaces planned time.

### Optional async probe retained

If discovery makes async/concurrency a useful scenario, use the existing unfamiliar Vue/TypeScript example with two overlapping requests resolving out of order. Ask for the final UI state, failure mechanism, safe response coordination, and a trade-off, one question at a time and before hints. Preserve the learner-owned prediction, causal explanation, correction, and trade-off as evidence. This is a candidate probe, not the automatic first action.

## Reassessment

After justified development, recheck the selected capability in a changed context. At meaningful real-work, project, project-defense, or interview-readiness milestones, summarize strongest evidence, improving areas, unknowns, interview risks, and whether the primary/secondary choice should change. Add focused practice only for demonstrated need.
