<div align="center">

<p align="center">
  <img src="./logo.png" width="120" height="120" alt="jilva logo" />
</p>

# jilva

**Beautiful frameworks for developers.**

Jilva is an open-source effort to build developer tools with exceptional
developer experience — starting with terminal interfaces, designed to feel
calm, clear, and precise.

</div>

---

## Vision

Most developer tools are powerful but unpleasant. Jilva exists to close that gap:
correctness and performance, without sacrificing beauty.

We build slowly, in the open, with high standards for API design,
documentation, and craft.

## Currently building

> **Rust first.** The first Jilva framework is a TUI framework in Rust.
> It is in the design stage — we are writing RFCs before code.

- [`jilva-co/jilva-rs`](https://github.com/jilva-co/jilva-rs) — Rust framework (vision + RFCs, no stable API yet)
- [`jilva-co/branding`](https://github.com/jilva-co/branding) — logo, colors, voice

No releases yet. If you want to follow along, watch `jilva-rs`.

## Roadmap

| Stage | Status |
|-------|--------|
| Org foundation (profile, contributing, security) | In progress |
| Branding v0 (logo, palette, voice) | Next |
| `jilva-rs` RFCs (scope, non-goals, API sketch) | Next |
| `jilva-rs` prototype (private branch) | Later |
| Public alpha `0.1.0` | Later — no date promised |

We will not publish a crate before the API has been reviewed in an RFC.

## Projects

| Project | Language | State |
|---------|----------|-------|
| [`jilva-rs`](https://github.com/jilva-co/jilva-rs) | Rust | Design — RFCs welcome, code not accepted yet |
| `jilva-go` | Go | Future — not started |
| `jilva-ts` | TypeScript | Future — not started |
| `jilva-py` | Python | Future — under consideration |

One repository per language. Shared assets live in `branding`, shared community files live in `.github`.

## Future language ecosystem

Jilva is a family name, not a single crate. The convention is:

```text
jilva-rs   Rust (first)
jilva-go   Go (future)
jilva-ts   TypeScript (future)
jilva-py   Python (future)
```

Each language gets its own repo, releases, and docs — but the same
positioning: modern, beautiful, high-quality. We expand one language at a
time, only when the previous one is genuinely usable.

## How to contribute

We are early, so the most valuable contributions are **ideas and scrutiny**,
not code.

1. Read [`jilva-co/jilva-rs`](https://github.com/jilva-co/jilva-rs) vision and open RFCs.
2. Open a Discussion before a PR — especially for API ideas.
3. Read [CONTRIBUTING.md](https://github.com/jilva-co/.github/blob/main/CONTRIBUTING.md).
4. Be kind — see our [Code of Conduct](https://github.com/jilva-co/.github/blob/main/CODE_OF_CONDUCT.md).

```bash
# when code lands, this is all you will need
git clone https://github.com/jilva-co/jilva-rs.git
cd jilva-rs
```

---

<sub>Jilva · Beautiful frameworks for developers · [`jilva-rs`](https://github.com/jilva-co/jilva-rs) · [`branding`](https://github.com/jilva-co/branding) · Maintained by the Jilva contributors</sub>
