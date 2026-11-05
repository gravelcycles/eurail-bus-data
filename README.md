# Euro Rail bus and coach data

Immutable licensed bus timetable derivatives for the optional bus layer at
[Euro Rail](https://gravelcycles.github.io/eurail-atlas/). This repository is
separate from the train delivery and from private source archives.

Each version belongs in `snapshots/<manifest-sha256>/`. The website pins both a
Git commit and that manifest hash. The version's manifest identifies its exact
service-date cohort, publisher archives, included sources, rights, observed
records and limitations. These are partial source observations: no country or
European bus network is certified complete, and the 95% target is not achieved
by counting feeds. Source records may overlap. Scheduled services are not a
claim of actual operation, public boarding eligibility or pass inclusion.

Licences apply per source. Preserve the exact publisher/update-date credits,
licence URLs and any share-alike conditions in the manifest, actual-call details
and `database-offer.json`. ODbL source derivatives retain ODbL obligations;
other derivatives retain their own named terms, including CC BY-SA where
applicable. No blanket licence or ownership claim is made over publisher data.
The database offer explains reconstruction from the published packets. Original
GTFS archives, acquisition receipts and private QA evidence are not stored here.

Old snapshots remain immutable for existing links and rollback. This is a
bounded interim distribution path; larger or repeated cohorts require dedicated
bulk-data hosting. Code, acquisition, independent conservation, rights checks,
browser verification and release identities are maintained by the Euro Rail
pipeline separately. A commit in this repository does not establish website
activation, measured coverage or complete HTTP verification.
