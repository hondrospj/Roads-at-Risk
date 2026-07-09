# Roads at Risk

Static GitHub Pages app for drawing cross sections through a clipped 5 ft Seaside Heights DEM.

DEM source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Seaside Heights Borough boundary and resampled to 1.524 m / 5 ft pixels.

Flood-dashboard context: Seaside Heights gauge thresholds, dated observed daily peaks, top tide events, high tide count, and trend summary are stored in `flood_stats.json`.

Main files:

- `index.html` - web app
- `seaside_heights_dem_5ft_cog.tif` - elevation COG, meters
- `seaside_heights_hillshade.png` - map hillshade preview
- `seaside_heights_boundary.geojson` - clip boundary
- `dem_metadata.json` - data provenance and raster bounds
- `flood_stats.json` - flood-dashboard thresholds, dated archive peaks, and trend statistics used by dot-click flood charts
