# cville-transit

A knowledge base and working space for transit-related projects in Charlottesville, Virginia — UVA Transit, CAT (Charlottesville Area Transit), and how they fit together for the people who actually ride them.

## Why this exists

UVA and Charlottesville have two separate bus systems that many residents and students use as part of the same trip. CAT shows up in Google Maps and Apple Maps; UVA Transit does not. In practice that makes the systems feel disconnected even when the schedules and routes are public.

A [GTFS](https://gtfs.org/documentation/overview/) feed for UVA Transit actually exists on Transitland: <https://www.transit.land/feeds/f-university~of~virginia>. So the raw data is out there. The interesting questions are:

- Why don't Google Maps and Apple Maps ingest it?
- Is the feed missing fields or freshness guarantees that the big map apps require?
- Who owns the feed, and what would it take to get it submitted through the official Google Transit Partners / Apple Maps Connect pipelines?
- Are there institutional or operational barriers (data-sharing agreements, signage requirements, real-time vehicle position feeds) beyond the data itself?

## Scope

This repo is intentionally broader than one project. Likely areas:

- **UVA Transit on Google/Apple Maps** — the immediate motivating problem.
- **CAT + UVA integration** — trip planning across both systems.
- **GTFS feed quality** — auditing existing feeds, proposing fixes.
- **Side projects** — a standalone website, schedule viewer, or real-time map if useful.

## Structure

- `docs/` — Obsidian-compatible wiki. Notes on GTFS, the feed, agencies, ingestion requirements, contacts, and prior art.
- `README.md` — this file.
- `LICENSE` — MIT.

## Contributing

This is early. If you're interested in transit in Charlottesville and want to help, open an issue or a PR. Notes, links, screenshots, and questions are all welcome — not just code.

## License

MIT. See [LICENSE](LICENSE).
