# Biology simulation services section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This section is the system locus for services which model, run, or observe
simulated biological systems — cells, organisms, and their populations —
through composed runtimes, engines, solvers, and observers. Descending
service sections add capability predicates; they do not grant an ancestor
authority to perform the terminal Actor's operation.

## Holdings

- `apps/natural-computer-simulation-engine` — the keystone app for a membrane-bounded,
  settling-based single-cell simulator: admission across the membrane as
  the only entry for opaque data, the interior as a predication site,
  metabolism as charge dynamics driven by a maintained gradient, death as
  the gradient's loss, division as site-splitting. See its own README and
  `dev/design/2026-08-21-natural-computer-simulation-engine-design.md` for the design this
  scaffold is declared against.
