# Day 1 — Understand Before Implementing

## Core rule

> Before asking “How do I implement this?”, understand “What problem are we solving, and what am I assuming?”

Senior thinking is not knowing every answer. It is finding the important uncertainty early, proposing a reasoned option, and confirming the right decisions with the right people.

## Connected reasoning chain

```text
Business problem
→ expected user flow
→ assumptions and edge cases
→ business rules and ownership
→ validation and error contract
→ UX recovery
→ implementation plan
→ AI-assisted execution and human review
```

## Foundation rules

1. **Start with why.** A ticket describes requested behavior, but may not explain the real problem.
2. **Write the flow before coding.** Include the happy path, important states, dependencies, and failure paths.
3. **Separate decisions.** Product decides intended business/user behavior. Engineering proposes technical options and trade-offs.
4. **Bring a recommendation.** Ask the PO: “I recommend X because Y. Does that match the expected experience?”
5. **Notice edge cases yourself.** Escalate only those that require a business decision; do not ask the PO to design the implementation.
6. **Put shared business meaning near the authority.** If several clients use the same API, prefer the backend/domain owning shared eligibility rules instead of duplicating them in every client.
7. **Keep UX responsibility in the frontend.** The backend states what is allowed and what failed; the frontend decides how to display, navigate, load, recover, and remain accessible.
8. **Validate twice for different reasons.** Frontend validation improves UX. Backend validation protects correctness and security using current authoritative data.
9. **Expect stale state.** Data can change after the page loads. The create/update endpoint must validate again.
10. **Errors must support recovery.** Tell the user what happened and what they can do next—not merely “Something went wrong.”
11. **Use structured error contracts.** A stable code such as `RESTAURANT_NOT_RESERVABLE` lets every client react consistently while presenting the message appropriately.
12. **Use AI after thinking.** AI should challenge the plan, reveal missing cases, and accelerate execution; it should not silently choose product behavior or replace review.

## Day 1 case: admin reservation

- Admin has no special override; restaurant eligibility still applies.
- No integration and no working hours means the restaurant cannot accept reservations.
- Showing every restaurant but disabling ineligible ones preserves visibility and prevents an invalid path; explanatory text or a tooltip tells the admin why.
- Product should confirm this experience after engineering presents the recommendation and trade-offs.
- Because admin, web, and mobile clients may share the API, the backend should preferably expose business meaning such as `canMakeReservation` and enforce it when creating a reservation.
- If eligibility changes mid-flow, refresh authoritative data, show a clear explanation, and return the user to a valid step such as restaurant selection—subject to product confirmation.

## Five-minute pre-Cursor note

```text
Problem: What real outcome is needed?
Known flow: What happens from start to finish?
Assumptions: What am I treating as true without confirmation?
Edge cases: What can change, fail, or become stale?
Questions: Which business behaviors need PO/backend confirmation?
My proposal: What do I recommend, and why?
Cursor: Challenge this plan, alternatives, and trade-offs before implementation.
```

## Daily checklist

- [ ] Can I explain the business problem in one sentence?
- [ ] Did I map the happy path and important failure paths?
- [ ] Did I distinguish business rules from UI behavior?
- [ ] Is each rule owned by the right layer and not needlessly duplicated?
- [ ] Does the backend revalidate authoritative rules?
- [ ] Can the user understand and recover from each important error?
- [ ] Did I take recommendations—not empty questions—to the PO?
- [ ] Did AI challenge a plan I understand before generating code?
- [ ] Did I review and test the important logic myself?

## One-line recall

**Understand the problem → map the flow → expose assumptions → assign ownership → validate authoritatively → design recovery → plan with AI → review as the engineer.**
