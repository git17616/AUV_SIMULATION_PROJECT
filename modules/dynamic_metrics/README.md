# Dynamic Metrics

## Responsibility
Estimate state over time and calculate motion metrics where inputs support them.

## Inputs
- Time-series observations
- Measurement uncertainty

## Outputs
- State estimate and covariance
- CPA/TCPA and tracking metrics when calculable

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
