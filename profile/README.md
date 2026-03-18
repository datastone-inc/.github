# dataStone Inc.

PostgreSQL extension specialists. Evolution, not revolution.

dataStone has deep technical knowledge on both legacy mainframe databases and modern PostgreSQL to migrate databases from legacy to modern. We build custom extensions that bridge these worlds, enabling gradual modernization without disruptive "big bang" migrations.

We are also practitioners in AI-assisted development, building tools and publishing research on where agentic coding workflows fail and how to catch those failures before they reach production.

Our clients include enterprise system integrators and mainframe modernization specialists working with organizations transitioning from mainframe databases.

## PostgreSQL Extensions

### Foundation Tools

**pg_helloworld** - Verify your environment is correctly configured for building PostgreSQL extensions. Tests compilation, installation, and runtime loading.

### Performance Optimizations

**pg_num2int_direct_comp** - Eliminate performance-destroying casts when comparing numeric types (decimal, numeric, float) with integer columns. Essential for schema mismatches in joins and lookups where index scans become table scans.

### Data Type Enhancements  

**pg-bictext** - Blank-insensitive comparison text for scenarios requiring flexible string matching without normalization overhead.

## AI-Assisted Development

AI coding agents are good at reporting success. They are not always good at delivering it. We coined the term "phantom completion" for a specific failure mode: the agent marks a task done but the work was never performed. Our tooling catches these failures across multiple agentic coding platforms.

**verify-plan** - A Claude Code skill that checks whether a /plan was actually implemented. Parses plan items, diffs against actual changes, and reports what was missed. MIT licensed, zero dependencies.

**spec-kit-verify-tasks** - A spec-kit community extension that independently verifies task completions through a five-layer verification cascade. Works across Claude Code, GitHub Copilot, Gemini CLI, Cursor, and Windsurf.

**Chiron** (pronounced "KY-ron") - AI collaboration coaching tool, currently in closed beta.

Read more: [The [X] Problem: Phantom Completions in AI-Assisted Development](https://datastone.ca/blog/task-phantom-completions-ai-assisted-development/)

## Mainframe Integration

Extensions for connecting PostgreSQL to legacy mainframe systems - DB2 z/OS, IMS, and related technologies. Enables Foreign Data Wrapper (FDW) access patterns for gradual data migration.

*Repositories publishing soon*

## Migration Utilities

Tools for schema translation, data validation, and test data generation during database modernization projects.

*Repositories publishing soon*

## Contributing

We welcome feedback and issue reports:

- Bug reports with reproduction steps
- Feature requests with use case descriptions
- Performance observations from your environment
- Documentation improvements

We handle code development internally to maintain quality standards and architectural consistency. If you have implementation ideas, open an issue to discuss - we may incorporate the approach in future releases.

## Resources

- [Technical Blog](https://datastone.ca/blog) - Implementation guides, PostgreSQL internals, and AI-assisted development research
- [Website](https://datastone.ca) - Consulting services and case studies

## About

dataStone builds PostgreSQL extensions for complex integration and performance challenges, and tooling for AI-assisted development reliability. We contribute open-source solutions for common problems and provide consulting for specialized requirements.

For extension support or custom development inquiries: dave.sharpe@datastone.ca
