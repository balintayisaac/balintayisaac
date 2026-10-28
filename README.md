# Isaac Balintay

I build AI systems that run on modest hardware. Most local-LLM tooling assumes a 32 GB workstation with a discrete GPU; my focus is the other case: an 8 GB laptop, four CPU cores, no graphics card, and a disk budget measured in gigabytes. The tools should still work.

## Current work

**[FlashMini](https://github.com/balintayisaac/flashmini)** — a terminal coding assistant for Linux that runs a small quantized model (1.5B–4B parameters) entirely on-device. The design covers llama.cpp inference, tree-sitter code analysis, hybrid keyword/vector retrieval over the codebase, a SQLite-backed memory system, and one non-negotiable rule: the agent may not report a fix as working until tests and linters pass. It is in active development, built and dogfooded on the machine it targets.

## How I work

- Local-first. Software that runs offline and keeps your data on your machine.
- Small, testable components over frameworks.
- Honest measurement. If a claim can't be verified by running a command, it doesn't ship.

## Stack

Linux (Lubuntu) · Python (CLI/backend) · C/C++ (llama.cpp) · TypeScript (tooling/plugins) · SQL/SQLite · tree-sitter · git

## Contact

isaacbalintay@tutamail.com
