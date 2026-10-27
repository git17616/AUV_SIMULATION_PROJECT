# Feedback Evaluation

## Responsibility
Evaluate modules, monitor model performance and version results.

## Inputs
- Module outputs
- Ground truth
- Scenario/run metadata

## Outputs
- Metric reports
- Plots
- Model/data version records

## Implementation notes
- Verify fields and units against the selected HoloOcean configuration.
- Keep data source, timestamp, scenario ID and run ID with records.
- Add unit tests for transformations and missing/invalid data.
