# Monterey Bay Important Shark and Ray Area (ISRA) Proposals

## Description
This repository contains the code and analyses used to support Important Shark and Ray Area (ISRA) proposals focused on white shark aggregations in Monterey Bay. The analyses are based on acoustic telemetry detections and include network connectivity, residency, receiver-efficiency, and size distribution summaries.

## Repository Contents
acoustic_aggregations.Rmd
- Purpose: Detects and maps white shark aggregations using ISRA-generated acoustic detection data.
- Definition of aggregation: Presence of 3+ individuals within a 5-minute window.
- Outputs:
  - Aggregation events mapped over time
  - Aggregation occurrences at proposed sites:
    - New Brighton
    - Marina

fins_aggregations.Rmd
- Purpose: Describes white shark sightings at aggregation sites using fin-ID demographic characteristics.
- Focus:
  - Individual shark sighting history
  - Demographics by fin-ID (sex, size class, etc.)
- Outputs:
  - Sighting summaries for New Brighton and Marina
  - Demographic breakdowns for observed sharks

size_distributions.Rmd
- Purpose: Analyzes size and ontogenetic characteristics of shark aggregations.
- Outputs:
  - Summary statistics for shark size distributions
  - Ontogeny-related summaries (e.g., juvenile vs adult composition)

acoustic_networks.Rmd
- Purpose: Performs preliminary network analyses on tagged white sharks in Monterey Bay.
- Key analyses:
  - Creation of nodes and edges representing shark movement and interaction
  - Computation of:
    - Activity
    - Node coverage

receiver_efficiency.Rmd
- Purpose: Explores receiver coverage across the receiver clusters in five regions of Monterey Bay.
- Outputs:
  - Receiver coverage comparisons across regions
  - Efficiency and coverage visualization by receiver cluster

Notes
- These files are written as R Markdown (.Rmd) and are intended to generate reproducible reports and figures.
- All analyses rely pre-processed detection records of unpublished data (Block Lab, Stanford University)
