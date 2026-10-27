# Threat Classification

## Responsibility
Generate an explainable risk assessment from defined inputs and policy.

## Inputs
- Identification result
- Static and dynamic metrics
- Documented policy/labels

## Outputs
- Risk category
- Confidence if calibrated
- Contributing factors

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
