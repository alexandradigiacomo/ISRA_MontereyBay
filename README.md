# Monterey Bay Important Shark and Ray Area (ISRA) Proposals

## Description
This repository contains the code and analyses used to support Important Shark and Ray Area (ISRA) proposals focused on white shark aggregations in Monterey Bay. The analyses are based on acoustic telemetry detections and include network connectivity, residency, receiver-efficiency, and size distribution summaries.

## Repository Contents
acoustic_aggregations.Rmd
- Purpose: Detects and maps white shark aggregations using ISRA-generated acoustic detection data, which defines aggregations as the presence of 3+ individuals within a 5-minute window.
- Inputs:
  - Cleaned acoustic telemetry detections
- Outputs:
  - Aggregation events mapped over time at proposed sites (New Brighton, Marina)

fins_aggregations.Rmd
- Purpose: Describes white shark sightings at aggregation sites using fin-ID demographic characteristics.
- Inputs:
  - Individual shark fin IDs + demographics (sex, size class, etc.)
- Outputs:
  - Sighting summaries for proposed aggregations
  - Demographic breakdowns for observed sharks

size_distributions.Rmd
- Purpose: Analyzes size and ontogenetic characteristics of shark aggregations.
- Inputs:
  - Length data at aggregations (DiGiacomo et al. 2026)
- Outputs:
  - Summary statistics for shark size distributions
  - Ontogeny-related summaries (e.g., juvenile vs adult composition)

acoustic_networks.Rmd
- Purpose: Performs preliminary network analyses on tagged white sharks in Monterey Bay.
- Inputs:
  - Cleaned acoustic telemetry detections
- Outputs:
    - Activity metrics
    - Node coverage metrics

receiver_efficiency.Rmd
- Purpose: Explores receiver coverage across the receiver clusters in five regions of Monterey Bay.
- Inputs:
  - Cleaned acoustic telemetry detections and receiver metadata
- Outputs:
  - Receiver coverage comparisons across regions
  - Efficiency and coverage visualization by receiver cluster

Notes
- These files are written as R Markdown (.Rmd) and are intended to generate reproducible reports and figures.
- All analyses rely pre-processed detection records of unpublished data (Block Lab, Stanford University)
