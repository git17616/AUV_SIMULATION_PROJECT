# Static Metrics

## Responsibility
Store validated, sourced vehicle-profile attributes.

## Inputs
- Vehicle profile/configuration records

## Outputs
- Static metric vector
- Provenance and missing-field indicators

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
