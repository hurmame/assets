# Hurma assets

Public generated GeoIP and Geosite databases built by `hurmame/geodata`.
Only generated data and its checksums are published here.

The `geodata-test` branch is the testing channel. Client routing must opt in;
publishing an update does not switch normal subscriptions to these databases.

CDN URLs:

- https://cdn.jsdelivr.net/gh/hurmame/assets@geodata-test/geoip.dat
- https://cdn.jsdelivr.net/gh/hurmame/assets@geodata-test/geosite.dat

Use the immutable commit SHA in place of `geodata-test` for reproducible tests.
`manifest.json` records hashes and the source build. Generated data is released
under CC-BY-SA-4.0; upstream data attribution is provided in LICENSE.
