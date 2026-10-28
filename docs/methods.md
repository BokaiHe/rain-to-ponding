# Methods and limitations

## Process playback

Eight precomputed rainfall scenarios use a conservative local-inertia surface-flow calculation on a 5 m Manhattan grid. Saved depth and velocity frames are replayed in the browser. Increasing rainfall by 1.5 or 2 uses an independently calculated scenario, not multiplied water depths.

The city uses NOAA 2017 terrain and NYC building, street and park records. Close-view 2 m terrain improves display detail, not the 5 m hydraulic calculation's resolution. Original depressions are retained. Solid building masks, simplified roof diversion and prescribed infiltration/drainage are modeling assumptions.

## Rainfall exploration

The browser evaluates a precomputed depression hierarchy using Fill–Spill–Merge for the selected rainfall and duration. It shows a final filled/spilled state under prescribed losses, not the elapsed evolution of a storm or a future forecast. The published hierarchy and FSM papers are linked in the data-source notes.

## Independent evidence

FloodNet observations are point measurements, not complete inundation maps. The interface compares observed depth with the model sensor cell and the maximum within 10 m. A consistent or inconsistent label concerns whether each reaches 1 cm at shared observation times. Missing observations are not zero; unsuitable comparisons remain not comparable. Magnitude and timing differences are reported separately.

Five non-tidal October 30 sensor curves are usable in the current comparison. The model detects ponding at one sensor cell and within 10 m at four. At Nagle Ave, observed peak depth is 22.71 cm and the model-cell peak is 8.00 cm. This is a discrepancy, not a successful depth validation.

Drainage of 20 mm/h was selected against an official modeled stormwater map, with F1 about 0.26. That map is another model scenario, not an observed flood boundary. FloodNet was not used to tune drainage.

## Interpretation

Uniform rainfall, constant drainage capacity, no explicit sewer or tidal dynamics, older terrain and coarse building connectivity limit accuracy. Closed pits can produce unrealistically large depths. Flagged terrain artefacts remain visible but are excluded from rankings and headline statistics. The maps do not estimate damage, certify safe routes or predict future flooding.

Rain particles and exaggerated flow animation are for presentation. Model and observation values remain distinct from these visual effects.
