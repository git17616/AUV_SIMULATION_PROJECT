# Identification

## Responsibility
Classify contacts and track authorisation status separately.

## Inputs
- Processed signal/features
- Optional authorisation messages

## Outputs
- Contact class and confidence
- Authorisation status

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
