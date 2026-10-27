# Depth Sensor Analysis

## Responsibility
Characterise sensor error and calibration against a reference.

## Inputs
- Measured depth
- Reference depth
- Test conditions

## Outputs
- Depth error
- Calibration and response estimates where supported

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
