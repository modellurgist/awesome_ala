# Awesome ALA [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of explorations of **Abstraction Layered Architecture (ALA)** — apps, designs, tools, analysis, and writing.

[Abstraction Layered Architecture](https://www.abstractionlayeredarchitecture.com/) is John Spray's approach to software structure: dependencies point only *downward*, from a concrete piece to a more abstract, more stable one, so peers never depend on each other. The source is designed to be zero-coupled while the running program is fully connected through wiring in a higher layer.

This is a **community list**, independent of and unaffiliated with the author. It gathers people's own experiments with ALA across languages and problem domains — including ones that push on it, disagree with it, or measure it. **[Contributions welcome](#contributing).**

## Contents

- [The Method](#the-method)
- [Web Apps](#web-apps)
- [Designs & Patterns](#designs--patterns)
- [Tools](#tools)
- [Analysis](#analysis)
- [Thoughts & Writing](#thoughts--writing)
- [Contributing](#contributing)
- [License](#license)

## The Method

The primary source and reference code, by ALA's author.

- [Abstraction Layered Architecture](https://www.abstractionlayeredarchitecture.com/) — John Spray's online book: the concepts, motivation, and worked examples.
- [johnspray74 on GitHub](https://github.com/johnspray74) — Spray's repositories. The ALA-related ones (reference code, mostly C#):
  - [ALAExample](https://github.com/johnspray74/ALAExample) — a full example application of ALA; used in the 2021 IEEE TSE paper and the book.
  - [Thermometer](https://github.com/johnspray74/Thermometer) — the thermometer example from the book.
  - [ReactiveCalculator](https://github.com/johnspray74/ReactiveCalculator) — an ALA calculator, from an ALA workshop at AUT.
  - [GameScoring](https://github.com/johnspray74/GameScoring) — a game-scoring example demonstrating ALA.
  - [MaybeMonad](https://github.com/johnspray74/MaybeMonad), [IEnumerableMonad](https://github.com/johnspray74/IEnumerableMonad), [ContinuationMonad](https://github.com/johnspray74/ContinuationMonad) — demos comparing a monad with the equivalent ALA form, from the book.
  - [ALAAsciiDoc](https://github.com/johnspray74/ALAAsciiDoc) — the source of the ALA website/book.

## Web Apps

Runnable applications built or refactored to ALA.

- [ala_variants_elixir](https://github.com/modellurgist/ala_variants_elixir) — several Elixir/Phoenix LiveView shopping-cart designs, each a different take on ALA (committed codegen, composed inputs, a vernacular core, lint-guided evolution), plus a single-file thermometer. *(Elixir / Phoenix)*

## Designs & Patterns

Design write-ups, notations, and reusable patterns — the *how*, not a specific app.

- [ala_checklist](https://github.com/modellurgist/ala_checklist) — a language-agnostic checklist (R1–R11) and a compact encoding notation for reading ALA compliance off a design's shape.

## Tools

Linters, generators, and analyzers that check or produce ALA.

- [ala_lint_elixir](https://github.com/modellurgist/ala_lint_elixir) — a static-analysis linter that scores an Elixir codebase against the ALA Checklist and can encode source into the notation. *(Elixir)*

## Analysis

Measurements, comparisons, and critiques — evidence for or against ALA's claims.

- *Your study here — an information-theoretic comparison, a reuse experiment, a critique of where ALA does or doesn't pay off.*

## Thoughts & Writing

Blog posts, essays, and opinions.

- [getdown.dev](https://getdown.dev) — "Get Down with ALA": working notes applying ALA to Elixir and Phoenix LiveView, in the open.

## Contributing

Add your own ALA exploration — a web app, a design, a tool, an analysis, or just thoughts — by opening a pull request that adds one entry to the most fitting section:

```
- [Name](https://link) — One-line description. *(language / stack, if relevant)*
```

Explorations that question or stress-test ALA are as welcome as ones that champion it. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guidelines. By contributing, you agree your addition is released under [CC0 1.0](#license) (public domain).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, contributors have waived all copyright and related rights to this list under [CC0 1.0 Universal](LICENSE). Linked works are not covered — each keeps its own license.
