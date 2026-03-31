# bench-osnoise

Scripts and configuration to run the [rtla osnoise](https://man7.org/linux/man-pages/man1/osnoise.1.html) benchmark within the [crucible](https://github.com/perftool-incubator/crucible) performance testing framework. Measures operating system noise that can interfere with real-time workloads.

## Key Files

| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: defines client scripts and parameter transformations |
| `multiplex.json` | Parameter validation and presets for multiplex |
| `osnoise-base` | Base setup shared by other scripts |
| `osnoise-client` | Client-side benchmark execution |
| `osnoise-get-runtime` | Runtime extraction |
| `osnoise-post-process` | Post-processing: parses osnoise output into crucible metrics |
| `workshop.json` | Engine image build requirements |
