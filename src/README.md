# Source layout

Place production ingestion modules here. Each source must:

1. Preserve the original response/file under `raw/`.
2. Add `source`, `published_at`, and `ingested_at`.
3. Use stable source IDs and a canonical ID map.
4. Record coverage and errors.
5. Never use data published after the prediction cutoff.

The smoke test intentionally uses synthetic rows and does not claim that private or unavailable data exists.
