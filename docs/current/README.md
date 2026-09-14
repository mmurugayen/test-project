# Current documentation: test-project

Last source review: **2026-09-14**, default branch `main`, commit [`1022e6e23b97`](https://github.com/mmurugayen/test-project/commit/1022e6e23b97959c88b7ff592c6a8feb881f27f5). This records a documentation review of the linked source snapshot.

The source contains a diagnostic utility; no domain product or Terraform resources are declared.

- [Architecture](ARCHITECTURE.md)
- [Workflow](WORKFLOWS.md)
- [Audit and complete inventory](DOCUMENTATION_AUDIT.md)
- [Validation](VALIDATION.md)
- [Repository README](../../README.md)

## Maintaining the diagrams

Edit [diagrams.json](diagrams/diagrams.json), then run `python3 docs/current/diagrams/render.py`. Commit sources and generated SVGs together.

Check reproducibility with `python3 docs/current/diagrams/render.py --check`. Architecture `units` contain components; workflow `nodes` describe actions and alternatives. Refresh the source commit after comparing implementation changes.
