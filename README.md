# Catch Jamaat data

The masjid list and the iqama times that the Catch Jamaat app shows. The app downloads `v1/manifest.json` when it starts and fetches
`v1/mosques.json` and `v1/iqama.json` only when the manifest is newer than what it already has.

* `v1/manifest.json`: sizes, SHA-256 fingerprints and a `generated` stamp (UTC) for the two files.
* `v1/mosques.json`: places of prayer across Canada (name, address, position, website, phone).
* `v1/iqama.json`: for each place, how its iqama times are known (a fixed time, or minutes after the prayer starts) and where and when they were read.

Times are read from each masjid's own public page. They can change without notice: please confirm with the masjid.

Map positions and some place names come from OpenStreetMap (c) OpenStreetMap contributors, available under the Open Database License
(https://www.openstreetmap.org/copyright), and from the Region of Peel Open Data (Open Government Licence - Region of Peel).
