# King Pawn USA Entity and Citation Graph

This dataset is a first-party entity registry and citation planning graph for King Pawn USA / King Gold and Pawn locations.

It is designed for transparent AI and search discovery, not keyword stuffing. It contains seven public store records, canonical entity edges, and legitimate trade/directory citation targets that should be verified or claimed manually.

## Files

- `kgp_locations.csv`: public store facts from the canonical location registry.
- `kgp_sameas_edges.csv`: entity relationship edges between location pages and the canonical brand.
- `citation_evidence_scan.csv`: reachable profile-level citation evidence.
- `store_citation_edges.csv`: store-to-citation relationships for verified profile evidence only.
- `schema-dataset.jsonld`: schema.org `Dataset` metadata.
- `dataset-metadata.json`: publication gate metadata.
- `methodology.md`: source, limitations, and maintenance notes.

## Publication Status

Approved public-release candidate. Public proof rows include first-party location records and reachable profile-level citation evidence only.
