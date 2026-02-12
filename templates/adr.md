# Architecture decision record

<!--
This template helps create proposals for technical and organisational decisions.
Architecture decision records are for internal decisions about how Minttu is
built, structured, and maintained. For community-facing changes, use the request
for comments template instead.

Process details: https://handbook.omnifi.foundation/engineering/architecture/adrs/
-->

## Overview

### Title
<!-- A clear, descriptive title for the decision -->

### Number
<!-- Sequential number: ADR-0001, ADR-0002, etc. -->

### Status
- [ ] Proposed (initial proposal)
- [ ] Accepted (approved for implementation)
- [ ] Rejected (not approved)
- [ ] Deprecated (no longer applies)
- [ ] Superseded (replaced by another decision)

### Affected projects
- [ ] Tokens (design token system, CSS custom properties, theme token sets)
- [ ] Scale (fluid type scale, musical interval ratios, responsive scaling)
- [ ] Base (CSS reset, classless styling, accessibility foundations)
- [ ] Layout (grid system, containers, responsive utilities, spacing)
- [ ] Components (buttons, cards, chips, navigation, drawers, forms)
- [ ] Patterns (page templates, complex compositions, responsive layouts)
- [ ] Motion (transitions, animations, micro-interactions, scroll effects)
- [ ] Web components (custom elements, Preact islands, shadow DOM)
- [ ] Tooling (Vite plugin, Fresh extensions, build system, documentation)
- [ ] Infrastructure (Polo deployment, edge proxy, DNS, storage)
- [ ] Brand (typography, font assets, visual identity)
- [ ] Other: <!-- specify -->

---

## Problem statement

### Current situation
<!-- Describe the technical or organisational situation requiring this decision -->

### Decision drivers
- <!-- Driver 1 -->
- <!-- Driver 2 -->
- <!-- Driver 3 -->

### Constraints
<!--
- Technical limitations
- Compatibility requirements
- Accessibility requirements
- Performance requirements
-->

---

## Proposed decision

### Chosen approach
<!-- State the proposed decision clearly -->

### Rationale
<!-- Why is this approach being proposed? -->

### Consequences
<!--
- Positive outcomes
- Negative trade-offs
- Risks to monitor
-->

---

## Alternatives considered

### Alternative 1: <!-- Name -->
**Description**: <!-- What this alternative involves -->
**Advantages**: <!-- Advantages -->
**Disadvantages**: <!-- Disadvantages -->
**Decision**: <!-- Why chosen or rejected -->

---

## Impact summary

### Technical impact
<!-- How does this affect the codebase and architecture? -->

### Contributor impact
<!-- How does this affect how people contribute to the project? -->

### Accessibility impact
<!-- How does this affect the accessibility of the design system? -->

---

## Implementation notes

### Approach
<!-- Key implementation steps, migration considerations, testing requirements -->

### Verification
<!-- Success criteria, testing approach, monitoring requirements -->

---

## References

### Related decisions
<!-- Link to related or dependent ADRs -->

### External references
<!-- Links to relevant standards (CSS, WCAG, HTML), research, or design systems -->

---

## Next steps

- [ ] Draft full proposal in `adrs/XXXX-title.md`
- [ ] Submit merge request for review
- [ ] Address feedback from technical leads
- [ ] Update status after decision

---

## Governance

This decision follows the
[Omnifi Foundation governance model](https://handbook.omnifi.foundation/engineering/architecture/governance/).
Architecture decision records use lazy consensus — see the
[handbook](https://handbook.omnifi.foundation/engineering/architecture/adrs/) for
details.

---

/label ~"adr" ~"architecture" ~"technical"
