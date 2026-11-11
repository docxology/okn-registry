# TODO

## Workflowz review — 2026-11-10

Coverage note: no concrete improvement survived the bounded source review. Inspected the supplied README, Python manifest, build/query/VoID scripts, MkDocs hook, browser JavaScript, and the visible unit test. The `except OSError: pass` handlers are explicit missing-input fallbacks, and the test patches are intentional test doubles rather than silent production substitutes. Coverage is limited by the truncated `scripts/fetch_void_stats.py` excerpt and by unavailable contents for Snakefile, mkdocs.yml, uv.lock, CI configuration, and most registry/query files; no runtime or dependency behavior was executed. Re-review on a concrete failure or source change.
