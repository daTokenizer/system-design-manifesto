# The System Design Manifesto

A sane path toward systems that stay small, change safely, and can be understood by one person.

Read it: **[arch.adamlev.com](https://arch.adamlev.com)**

Eight principles for the practice of architecture — from a single function signature to a cross-team rebuild:

1. **Form Follows Function** — the design is derived from the requirements, never the other way round.
2. **One Normal Engineer** — a good design is reviewable by a single normal engineer; present it one level up.
3. **New is the Enemy** — new tools, services, and datastores are expensive; reuse and standards before invention.
4. **Do One Thing, Well** — one component, one job; extend before you build, but if you need the word *and* to say what it does, it is two components.
5. **Less Logic, Fewer Bugs** — code is hostile; deletion beats addition; talk through versioned schema/API seams.
6. **Control at the Edge** — put user-facing control close to the user, not baked into the infrastructure.
7. **Fail Correctly** — every component will fail; a cascading failure must not. Validate every input at the boundary.
8. **Actionable by Design** — every view ties an effect back to a cause the user can act on.
9. **Present Alternatives** — show the real options with their flaws; never smuggle a single solution past review.

A sibling to [The Data Modeling Manifesto](https://data.adamlev.com), and the doctrine behind the [baldspot](https://github.com/daTokenizer/baldspot) design-review mode.

The page is static HTML + CSS, no build step. By [Adam Lev-Libfeld](https://www.adamlev.com). Licensed GPL-3.0.
