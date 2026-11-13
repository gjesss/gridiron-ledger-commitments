# Gridiron Ledger: public commitments

Each file here is a commitment to the Gridiron Ledger shadow ledger at a point in time:

```json
{"seq": 412, "head_hash": "<sha256>", "committed_at": "2026-11-15T03:30:00+00:00", "algorithm": "..."}
```

`head_hash` is the SHA-256 head of a hash chain over every start/sit call and lean we have
made, each logged before its game's kickoff with a secret random nonce. The picks themselves
are not published yet. At launch we publish the full ledger export; anyone can recompute the
chain and check that its head at each `seq` equals the hash committed here, on the date this
repository's history shows. That proves every call was made when we said, and that none was
edited or removed afterward.
