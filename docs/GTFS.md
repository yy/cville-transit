# GTFS

General Transit Feed Specification — the open standard for sharing transit routes, stops, and schedules with map apps and trip planners.

- Overview: <https://gtfs.org/documentation/overview/>
- Static schedule: GTFS (a zip of CSVs — stops, routes, trips, stop_times, calendar, etc.)
- Real-time: GTFS-Realtime (vehicle positions, trip updates, service alerts) — Protocol Buffers

## Who uses it

- Google Maps (Google Transit Partners program)
- Apple Maps (Apple Maps Connect / agency partnership)
- Citymapper, Transit app, Moovit, OpenTripPlanner, and most third-party trip planners
- Aggregators: [Transitland](https://www.transit.land/), [Mobility Database](https://mobilitydatabase.org/)

## Ingestion vs. publication

Publishing a valid GTFS feed at a public URL is **not** the same as having it show up in Google or Apple Maps. Both require:

1. The agency to formally apply / partner
2. The feed to pass their internal validators (often stricter than the public spec)
3. Often a contact and SLA for keeping the feed fresh

This is the gap [[UVA Transit on Google and Apple Maps]] sits in.
