# CoordWizard (QGIS Plugin)

All-in-one coordinate conversion tool with live preview, bidirectional transforms, batch processing for vector & raster, precision control, and export options.

## Install
1. Download `CoordWizard.zip` from this chat.
2. In QGIS: `Plugins → Manage and Install Plugins… → Install from ZIP…` and select the file.
3. Enable **CoordWizard**. A dock will appear and a toolbar icon will be added.

## Features
- Multiple CRS (WGS84, UTM, NAD83, any EPSG or custom string).
- Bidirectional conversion with **Swap**.
- Batch reprojection for **vector** and **raster** layers (uses Processing).
- Live preview and map **Click** input.
- Precision control and multiple output formats (CSV, GeoJSON, Shapefile).
- Coordinate formats: DD, DMS, UTM, MGRS.
- Settings saved via QSettings.
- Processing provider with handy algorithms.

## Tips
- Enter coordinates as `x,y` (lon,lat for geographic CRS).
- Use project CRS as source/destination by selecting it in the dropdown.
- For very large rasters, prefer GeoTIFF outputs on SSD storage.

## Testing
- Includes a lightweight CSV conversion algorithm suitable for headless tests.
- Unit tests for helpers can be added under `tests/`.

## License
MIT. See LICENSE.
