# Bench-osnoise

## Purpose
Scripts and configuration to run the rtla osnoise benchmark within the crucible framework. Measures operating system noise that can interfere with real-time workloads.

## Language
Bash — all scripts

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client scripts, parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `osnoise-base` | Base setup shared by other scripts |
| `osnoise-client` | Client-side benchmark execution |
| `osnoise-get-runtime` | Extracts runtime from command-line options |
| `osnoise-post-process` | Parses osnoise output into crucible metrics |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
