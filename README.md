# Meridian Risk — review-note compression sweep (round 7)

Archived evidence for the round-7 sweep of the accounts-payable review-note
compressor. Each candidate configuration has its own directory under `runs/`:

- `summary.json` — run metadata plus the values recorded at the final checkpoint.
- `history.jsonl` — the full logged history (one JSON object per step, in order).

The step history is the record of what the model actually produced during the
run; the summary block only mirrors the last checkpoint. Candidate ordering in
this archive is alphabetical by directory name and carries no ranking meaning.

Sweep owner: applied-ml-platform@meridian-risk.internal

Corpus snapshot cards and sample shards for the sweep live under `corpora/`.
