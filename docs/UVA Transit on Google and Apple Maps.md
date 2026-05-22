# UVA Transit on Google and Apple Maps

## The problem

UVA Transit does not appear in Google Maps or Apple Maps trip planning, even though CAT (Charlottesville Area Transit) does. For anyone whose trip combines the two systems — which is many UVA students, faculty, and staff — the two map apps treat half of the local transit network as if it doesn't exist.

## What we know

- A GTFS feed for UVA Transit is published and discoverable on Transitland: <https://www.transit.land/feeds/f-university~of~virginia>
- GTFS is the standard format Google and Apple use to ingest transit data ([[GTFS]])
- The existence of a feed is necessary but not sufficient — both Google and Apple have their own onboarding pipelines that require an agency relationship, not just an open feed

## Open questions

- Who maintains the existing feed? Is it UVA Parking & Transportation directly, or a third party (e.g., the vendor running TransLoc / Passio)?
- Has UVA Transit applied to Google Transit Partners or Apple Maps Connect? If so, what happened?
- Does the feed meet Google/Apple validation requirements (stop accuracy, calendar coverage, trip headsigns, real-time GTFS-RT if expected)?
- Are there policy barriers — e.g., does UVA not want UVA Transit routed to non-affiliates via Google Maps?

## Next steps

- Audit the published feed against Google's GTFS requirements
- Identify the feed owner and reach out
- Document the institutional path (Parking & Transportation → who?)
