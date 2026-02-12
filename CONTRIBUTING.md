# Contributing to Minttu Architecture

Thank you for your interest in shaping Minttu’s architecture. This guide
explains how to submit proposals — whether you’re proposing a new technical
direction, suggesting changes to how the project operates, or advocating for
changes to community-facing interfaces.

## Before you begin

- **Check existing proposals.** Browse `adrs/` and `rfcs/` to see what’s already
  been decided. Your idea may build on or conflict with earlier decisions.
- **Check open merge requests.** Someone else may already be working on a
  similar proposal.
- **Open an issue first.** Use the issue templates to signal your intent and
  get early feedback before investing time in a full proposal.

## Choosing the right proposal type

### Architecture decision records (ADRs)

Use an ADR when you’re proposing an **internal technical or organisational
decision**. ADRs cover how Minttu is built, structured, and maintained.

Examples:
- Choosing a CSS layer ordering strategy
- Adopting a specific fluid scaling algorithm
- Defining the design token naming convention
- Structuring the build pipeline for CSS output variants

ADRs use **lazy consensus** — they are accepted unless someone objects within the
review period (typically 7–14 days). Technical leads facilitate the process.

### Requests for comments (RFCs)

Use an RFC when you’re proposing a **community-facing change**. RFCs cover
interfaces, behaviours, and capabilities that directly affect how people
interact with Minttu.

Examples:
- Changing the design token API or CSS custom property names
- Adding a new component to the design system
- Modifying the Vite plugin interface
- Changing how the type scale ratios work

RFCs require **active consensus** — they need explicit agreement from the
community. The discussion period is a minimum of 14 days.

## Proposal workflow

### 1. Open an issue

Use the appropriate issue template:
- **ADR**: for internal technical and organisational decisions
- **RFC**: for community-facing changes

This signals your intent to the community and invites early feedback.

### 2. Draft your proposal

Use the templates in `templates/`:
- `templates/adr.md` for architecture decision records
- `templates/rfc.md` for requests for comments

### 3. File naming

**ADRs**: `adrs/XXXX-short-descriptive-title.md`
- Example: `adrs/0001-css-layer-ordering.md`

**RFCs**: `rfcs/XXXX-short-descriptive-title.md`
- Example: `rfcs/0001-design-token-naming.md`

Numbers are sequential. Check existing files to determine the next available
number.

### 4. Branch naming

Create a branch for your proposal:
- ADRs: `proposal/adr-XXXX-short-title`
- RFCs: `proposal/rfc-XXXX-short-title`

### 5. Submit a merge request

Push your branch and open a merge request. The merge request description should
summarise the proposal and link to the tracking issue.

### 6. Discussion and decision

- **ADRs**: Technical leads review. Lazy consensus applies — accepted unless
  objected to within the review period.
- **RFCs**: Open community discussion for a minimum of 14 days. Active consensus
  required.

## Affected projects

When writing your proposal, indicate which projects are affected:

- **Tokens** (design token system, CSS custom properties, theme token sets)
- **Scale** (fluid type scale, musical interval ratios, responsive scaling)
- **Base** (CSS reset, classless styling, accessibility foundations)
- **Layout** (grid system, containers, responsive utilities, spacing)
- **Components** (buttons, cards, chips, navigation, drawers, forms)
- **Patterns** (page templates, complex compositions, responsive layouts)
- **Motion** (transitions, animations, micro-interactions, scroll effects)
- **Web components** (custom elements, Preact islands, shadow DOM)
- **Tooling** (Vite plugin, Fresh extensions, build system, documentation)
- **Infrastructure** (Polo deployment, edge proxy, DNS, storage)
- **Brand** (typography, font assets, visual identity)

## Style guidelines

- Write clearly and concisely. Assume readers are technically competent but may
  not have deep context on the specific area.
- Use British English spelling conventions (organisation, behaviour, colour).
- Avoid unexpanded acronyms on first use.
- Prefer concrete examples over abstract descriptions.
- Use human-centric language — “developers”, “operators”, “people” rather than
  “users”.

## Questions?

Open an issue. There are no bad questions, and proposing a direction — even one
that ultimately isn’t adopted — contributes to the project’s understanding of
its design space.

## Governance

All proposals follow the
[Omnifi Foundation governance model](https://handbook.omnifi.foundation/engineering/architecture/governance/).
The full process is documented in the
[handbook](https://handbook.omnifi.foundation/engineering/architecture/).
