# Communication Analysis

## Responsibility
Characterise link quality in an available or explicitly implemented channel model.

## Inputs
- Communication telemetry
- Channel/noise configuration

## Outputs
- Link-quality and packet statistics
- Latency and uncertainty where measurable

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
