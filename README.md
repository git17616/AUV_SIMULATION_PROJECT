# AUV Simulation Project

Modular simulation and evaluation scaffold for the HoloOcean-based UUV/AUV project.

## Modules
1. Data collection
2. Identification and authorisation
3. Static vehicle metrics
4. Dynamic metrics and tracking
5. Threat classification
6. Communication analysis
7. Depth-sensor analysis
8. Feedback, evaluation and model updating

## Suggested execution order
1. Configure a scenario and verify simulator/sensor outputs.
2. Run data collection and save ground truth separately from observations.
3. Add identification and static/dynamic metrics.
4. Add rule-based risk assessment before training ML models.
5. Add communication/depth-sensor analysis only for signals supported by the selected simulator setup.
6. Run evaluation and save versioned outputs.

## Data integrity
- Keep ground truth separate from noisy sensor observations.
- Store units, timestamps, scenario IDs, run IDs and data source with each record.
- Split ML datasets by scenario/run, not randomly by adjacent frames.
- Do not commit large raw datasets or trained model files unless the repository policy requires it.
- Treat the module code as a scaffold until each sensor/API is verified against the installed HoloOcean version.
