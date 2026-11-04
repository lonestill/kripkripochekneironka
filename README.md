# Forum Dataset Snapshot

JSON snapshot of publicly visible forum metadata, threads, and user records collected for offline analysis.

## Contents

`forum_data.json` contains `forum_id`, `forum_info`, `parsed_at`, `cutoff_time`, `threads`, and `users`.

Inspect it with standard JSON tools:

```bash
jq 'keys' forum_data.json
jq '.threads | length' forum_data.json
jq '.users | length' forum_data.json
```

## Data notice

This is a data snapshot, not an application. Forum data may be stale and may include usernames or other public profile information. Use it responsibly, respect the source site's terms, and do not treat it as authoritative or current.

The collector is not included, so the snapshot cannot currently be regenerated from this repository.

## License

No license or redistribution terms have been declared for the dataset.
