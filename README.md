# Seaside Heights Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Seaside Heights municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01408748, Seaside Heights
- PETSS / NOAA station: est0006
- NAVD88 thresholds: 2.55 ft minor, 3.55 ft moderate, 4.55 ft major
- MLLW thresholds: 3 ft minor, 4 ft moderate, 5 ft major
- MLLW = NAVD88 + 0.45 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Seaside Heights Borough boundary at 5-foot resolution.
