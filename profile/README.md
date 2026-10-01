# Jev-Engineering

Open research and tooling around **JEV**, a model that answers small structured questions (for example, which of five known actions fits a situation) instead of generating free text.

## Repositories

- [`jev-integration-evaluator`](https://github.com/Jev-Engineering/jev-integration-evaluator): scans a codebase for decision points where JEV might help and walks through testing it. Read-only and offline by default. MIT license.
- [`jraphyte`](https://github.com/Jev-Engineering/jraphyte): TRACE-GC, an evidence-bound graph compilation and GraphRAG reference implementation.
- [`layev`](https://github.com/Jev-Engineering/layev): open research implementation of parallel typed decisions and calibration, inspired by Kev and Laya. Apache-2.0 license.

## Limits

- `layev` is a research candidate, not a validated Jev replacement. Its CPU fixture tests pass; native Qwen/CUDA checks and Jev-relative quality are still open.
- `jraphyte` is a reference implementation with explicit deployment gates, not a qualified production service. Its demo uses fabricated observations and no provider.
- Live provider results are not claimed here; each README states what was and was not exercised.

[Contributing](https://github.com/Jev-Engineering/.github/blob/main/CONTRIBUTING.md) · [Support](https://github.com/Jev-Engineering/.github/blob/main/SUPPORT.md) · [Security](https://github.com/Jev-Engineering/.github/blob/main/SECURITY.md) · Steward: Complete Tech LLC
