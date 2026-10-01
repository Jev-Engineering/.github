<p align="center">
  <img src="https://raw.githubusercontent.com/Jev-Engineering/.github/main/profile/assets/banner.jpg" alt="Dark banner in violet and cyan: one glowing node fans out into five parallel lanes, each ending in a different geometric shape, with the middle lane illuminated as the chosen answer" width="100%">
</p>

<h1 align="center">Jev-Engineering</h1>

<p align="center"><b>Open research and tooling around JEV: structured decisions instead of free text.</b></p>

JEV is a model that answers small structured questions (for example, which of five known actions fits a situation) instead of generating free text.

## What we do

We build open tooling around that idea: finding where a decision point in a codebase might benefit, compiling typed decision questions, and researching parallel typed decisions and calibration.

## Repositories

| Repository | What it is |
| --- | --- |
| [`jev-integration-evaluator`](https://github.com/Jev-Engineering/jev-integration-evaluator) | Scans a codebase for decision points where JEV might help and walks through testing it. Read-only and offline by default. MIT license. |
| [`TypeWright`](https://github.com/Jev-Engineering/TypeWright) | Declare a decision, compile typed Jev questions, measure them, and ship a JSON program. Alpha 0.1. MIT license. |
| [`layev`](https://github.com/Jev-Engineering/layev) | Open research implementation of parallel typed decisions and calibration, inspired by Kev and Laya. Apache-2.0 license. |
| [`jraphyte`](https://github.com/Jev-Engineering/jraphyte) | TRACE-GC: evidence-bound graph compilation and GraphRAG reference implementation. |

## Limits

- `layev` is a research candidate, not a validated Jev replacement. Its CPU fixture tests pass; native Qwen/CUDA checks and Jev-relative quality are still open.
- `jraphyte` is a reference implementation with explicit deployment gates, not a qualified production service. Its demo uses fabricated observations and no provider.
- `TypeWright` is alpha: its no-key demo and core tests pass, but no live provider study has been completed and no measured accuracy gain is claimed.
- Live provider results are not claimed here; each README states what was and was not exercised.

<p align="center">
<a href="https://github.com/Jev-Engineering/.github/blob/main/CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/Jev-Engineering/.github/blob/main/SUPPORT.md">Support</a> · <a href="https://github.com/Jev-Engineering/.github/blob/main/SECURITY.md">Security</a> · Steward: Complete Tech LLC
</p>
