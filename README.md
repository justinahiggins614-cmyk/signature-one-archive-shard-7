# signature-one-archive-shard-7

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c01071.jsonl.gz` … `specs-c01180.jsonl.gz`
  (JAH-SPEC-160501 … JAH-SPEC-177000 — 16500 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry (lazy-loaded on demand).
- FROZEN: never write new chunks here; new drip chunks always land in the main repo.
