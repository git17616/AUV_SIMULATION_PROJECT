# Data Collection

## Responsibility
Collect and synchronise observations and metadata.

## Inputs
- Simulator sensor observations
- Scenario metadata
- Ground truth in a separate stream

## Outputs
- Timestamped raw records
- Data-quality flags
- Run manifest

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
