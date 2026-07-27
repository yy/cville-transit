# TODO

Concrete next steps. Check items off as they're done; add issues for anything that grows past a line.

## 1. Audit the existing feed

- [ ] Download the UVA Transit GTFS feed from [Transitland](https://www.transit.land/feeds/f-university~of~virginia) and inspect it
- [ ] Run Google's [`gtfs-validator`](https://github.com/MobilityData/gtfs-validator) against it; record errors and warnings
- [ ] Check freshness: does `calendar.txt` cover the current semester? When was the feed last updated?
- [ ] Check whether GTFS-Realtime (vehicle positions, trip updates) is published anywhere
- [ ] Spot-check a few stops against reality (location accuracy, names, headsigns)

## 2. Identify the feed owner

- [x] Identify the technical publisher: [Transitland's current static GTFS URL](https://www.transit.land/feeds/f-university~of~virginia) is hosted on UVA's TransLoc tenant, and [TransLoc describes UVA as a customer since 2013](https://transloc.com/case-studies/university-of-virginia-uva/)
- [ ] Confirm who at UVA owns the TransLoc account, GTFS configuration, and Google/Apple submission decisions
- [x] Identify the relevant UVA contacts: [Allison Day](https://parking.virginia.edu/people/allison-day), General Manager, UTS (`and4ne@virginia.edu`), and [Kendall Howell](https://parking.virginia.edu/people/kendall-howell), Assistant Director - Transportation (`klh3t@virginia.edu`)
- [ ] Follow up with Allison Day; Kendall Howell was contacted but has not responded
- [ ] If the direct UTS contacts stall, reach out to [Ethan Heil](https://sustainability.virginia.edu/people/ethan-heil) — Manager of Sustainable Buildings at UVA Office for Sustainability and director of the Decarbonization Academy
- [ ] Find the equivalent contact for the City of Charlottesville / CAT (they already did the Google integration — ask how)

## 3. Investigate ingestion status

- [ ] Confirm UVA Transit is *not* in Google Maps transit search (test from multiple stops/times)
- [ ] Confirm same for Apple Maps
- [ ] Find out whether UVA has ever applied to [Google Transit Partners](https://support.google.com/transitpartners/) or [Apple Maps Connect](https://mapsconnect.apple.com/)
- [ ] If an application was made and rejected, find out why

## 4. Write up findings

- [ ] One-pager summarizing: feed quality, ingestion status, blockers, and what an asking party would need to do
- [ ] Decide whether the right move is (a) advocacy to UVA, (b) fixing the feed and re-submitting, or (c) something else

## 5. Side projects (only after above)

- [ ] Standalone web map / schedule viewer if the official path stalls
- [ ] Unified CAT + UVA trip planner (OpenTripPlanner using both feeds)
- [ ] Newsletter/blog post documenting the story so far

## Done

(nothing yet)
