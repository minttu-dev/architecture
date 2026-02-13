# Contributing to Minttu Architecture

Thank you for your interest in shaping Minttu’s architecture. This guide
explains how to submit proposals — whether you’re proposing a new technical
direction, suggesting changes to how the project operates, or advocating for
changes to community-facing interfaces.

## Before you begin

- **Check existing proposals.** Browse `decisions/` and `comments/` to see what’s already
  been decided. Your idea may build on or conflict with earlier decisions.
- **Check open merge requests.** Someone else may already be working on a
  similar proposal.
- **Open an issue first.** Use the issue templates to signal your intent and
  get early feedback before investing time in a full proposal.


## Understanding the terminology

This repository uses accessible folder names that map to well-established
software engineering practices:

| Folder | Purpose | Also known as |
|--------|---------|---------------|
| `decisions/` | Recorded architectural and technical choices | Architecture decision records (ADRs) |
| `comments/` | Proposals and discussion for community-facing changes | Requests for comments (RFCs) |

The purpose is identical to traditional ADRs and RFCs — we use plainer language
to lower the barrier to contribution.

## Choosing the right proposal type

### Decisions

Use a decision when you’re proposing an **internal technical or organisational
decision**. Decisions cover how Minttu is built, structured, and maintained.

Examples:
- Choosing a CSS layer ordering strategy
- Adopting a specific fluid scaling algorithm
- Defining the design token naming convention
- Structuring the build pipeline for CSS output variants

Decisions use **lazy consensus** — they are accepted unless someone objects within the
review period (typically 7–14 days). Technical leads facilitate the process.

### Comments

Use a comment when you’re proposing a **community-facing change**. Comments cover
interfaces, behaviours, and capabilities that directly affect how people
interact with Minttu.

Examples:
- Changing the design token API or CSS custom property names
- Adding a new component to the design system
- Modifying the Vite plugin interface
- Changing how the type scale ratios work

Comments require **active consensus** — they need explicit agreement from the
community. The discussion period is a minimum of 14 days.

## Proposal workflow

### 1. Open an issue

Use the appropriate issue template:
- **Decision**: for internal technical and organisational choices
- **Comment**: for community-facing changes

This signals your intent to the community and invites early feedback.

### 2. Draft your proposal

Use the templates in `templates/`:
- `templates/decision.md` for architecture decisions
- `templates/comment.md` for community-facing proposals

### 3. File naming

**ADRs**: `decisions/XXXX-short-descriptive-title.md`
- Example: `decisions/0001-css-layer-ordering.md`

**RFCs**: `comments/XXXX-short-descriptive-title.md`
- Example: `comments/0001-design-token-naming.md`

Numbers are sequential. Check existing files to determine the next available
number.

### 4. Branch naming

Create a branch for your proposal:
- Decisions: `proposal/decision-XXXX-short-title`
- Comments: `proposal/comment-XXXX-short-title`

### 5. Submit a merge request

Push your branch and open a merge request. The merge request description should
summarise the proposal and link to the tracking issue.

### 6. Discussion and decision

- **Decisions**: Technical leads review. Lazy consensus applies — accepted unless
  objected to within the review period.
- **Comments**: Open community discussion for a minimum of 14 days. Active consensus
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
