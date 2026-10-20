# Tessera Repository Instructions

This file is an index. Read the applicable bounded rules under `docs/ai-rules/` before working.

The entire `docs/` directory is local and gitignored, including product plans and AI rules. Never force-add, stage, or commit anything under it. Read these files when available. Published clones do not contain them: follow this index and available public instructions, and report missing context when it is needed rather than inventing product requirements.

## Always read

| File | Purpose |
| --- | --- |
| [Core principles](docs/ai-rules/core-principles.md) | Product, stack, design priorities, ownership, and organization. |
| [Workflow and boundaries](docs/ai-rules/workflow-and-boundaries.md) | Scope, roadmap, skills, trust, Git, and communication. |
| [Product roadmap](docs/product/roadmap.md) | Current phase, intended order, exit gates, and next work. |

## Read when triggered

| Trigger | File |
| --- | --- |
| Adding projects, dependencies, provider implementations, public extension points, or changing ownership | [Architecture boundaries](docs/ai-rules/architecture-boundaries.md) |
| Changing a behavior across server, persistence, UI, admin API, or client SDK | [Cross-stack actions](docs/ai-rules/cross-stack-actions.md) |
| Writing C# under source, tests, or samples | [C# guidelines](docs/ai-rules/csharp-guidelines.md) |
| Writing or reviewing C# XML documentation | [XML documentation](docs/ai-rules/csharp-xml-documentation.md) |
| Changing validation, expected failures, or Result flows | [Results](docs/ai-rules/dotnet-results.md) |
| Changing diagnostics, logging, audit, or telemetry | [Logging](docs/ai-rules/dotnet-logging.md) |
| Writing React/TypeScript/CSS after a frontend is selected | [React guidelines](docs/ai-rules/react-guidelines.md) |
| Changing tests or claiming work is complete | [Testing](docs/ai-rules/testing.md) |
| Porting upstream behavior, handling credentials, authentication, authorization, or tenant isolation | [Identity and provenance](docs/ai-rules/identity-and-provenance.md) |
| Creating or substantially revising documentation | [Documentation](docs/ai-rules/documentation.md) |

## Maintaining the rules

- Keep durable engineering rules in the bounded file matching their trigger. Add a new trigger only for a new concern.
- Main product design belongs under `docs/product/`. Implementation tasks belong under `docs/tasks/`.
- Keep this index and the imports in `CLAUDE.md` consistent.
- Do not carry product-specific desktop, Rust/Tauri, analysis-engine, or AI-provider assumptions from ChangeLens into this identity server.
