# The Sieve of Theophrastus
The Sieve of Theophrastus is an ongoing longitudinal observational dataset documenting germination, growth, morphology, health, environmental response, and survival of individually identified cultivated plants.
Named in playful reference to the Sieve of Eratosthenes: rather than sieving numbers to reveal primes, this project sieves observations of growing plants through repeated measurement, separating individual variation and environmental effects from the underlying patterns of growth.

Published information on the earliest stages of growth for many plant species can be surprisingly sparse, particularly for species that are uncommon in cultivation. This project seeks to preserve detailed, longitudinal observations of individual plants from germination onward, including both quantitative measurements and qualitative observations of health, morphology, environmental conditions, injury, and other events.

## Purpose
The project is intended to produce a reusable observational dataset rather than to establish species-wide growth rates or controlled experimental results.

## Scope
Current taxa:
- Dalbergia melanoxylon
- Dalbergia retusa

Pending Taxa (acquired and/or attempting germination):
- Guaiacum sanctum
- Sequoia sempervirens
- Sequoiadendron giganteum

Desired taxa (actively seeking to acquire)
- Brosimum alicastrum
- Brosimum guianencse
- Brosimum rubescens
- Brosimum utile

Additional genera and species may be added as the project develops. The data structure is intentionally taxonomically general.

## Current status
Status: Active / Ongoing

The dataset is currently in the initial seedling-observation phase. Specimens are being tracked individually from germination, with routine measurements approximately every 30 days and additional observations associated with developmental or environmental events.

Current cohorts (post germination):
- DM0 — Dalbergia melanoxylon
- DM1 — Dalbergia melanoxylon
- DM2 — Dalbergia melanoxylon
- DM3 — Dalbergia melanoxylon
- DM4 — Dalbergia melanoxylon
- DR0 — Dalbergia retusa

## What is being measured
Various measurements are being collected at roughly 30 day intervals:
- Vertical height in	inches - Vertical projection from substrate to highest living point
- Leader length in inches -	Length following the measured leader
- Crown width in inches	- Maximum crown width
- Stem diameter in mm	- Diameter at defined measurement position
- Age in days	- Days since recorded sprouting

See documentation/measurement-protocol.md for complete definitions and procedures.
PENDING - edit/update documentation/measurement-protocol.md

## Individual tracking
Each specimen is assigned a permanent unique identifier at the beginning of its participation in the dataset. Identifiers are never reused or reassigned. Measurements and events are linked to these individual identifiers, allowing longitudinal analysis of individual growth trajectories and variation between specimens.

## Data organization
Data organization is proposed as follows:
data/
├── individuals.csv
├── acquisitions.csv
├── dm_measurements.csv
├── dr_measurements.csv
└── events.csv

ONGOING - create and populate the above files, using data from my lab notebook and existing spreadsheets
- data/individuals.csv — identity and relatively stable attributes
- data/acquisitions.csv — source/provenance information
- data/dm_measurements.csv — quantitative observations for Dalbergia melanoxylon
- data/dr_measurements.csv — quantitative observations for Dalbergia retusa
- data/events.csv — health, injury, environmental, cultivation, and other events
- data/{date_range}_open-meteo-{LAT}.{LON}.csv
- analysis/{date_range}_theophrastus_{Genus and species shorthand}_{measurement dimension}_{measurement units}.png

PENDING - decide if and when to add more to the following:
- analysis/
- documentation/
- photos/

## Raw data vs. analysis
Raw observations are preserved separately from derived analyses. Calculated growth rates, averages, extrapolations, models, and visualizations are not substituted for the original observations.
Missing observations remain missing; values are not invented or extrapolated to fill gaps in the raw dataset.

## Measurement methodology
Measurements are collected according to a versioned measurement protocol. The protocol defines measurement techniques, measurement locations, units, routine measurement intervals, and conditions under which particular measurements are omitted to avoid harming very young specimens.
documentation/measurement-protocol.md
PENDING - create and populate the above

## Data provenance and limitations
These observations are collected from plants grown under non-native cultivation conditions and should not be interpreted as representative of natural populations or as controlled experimental measurements. Environmental conditions, seed provenance, individual genetic variation, cultivation practices, injury, and measurement limitations may affect observed growth.

## Photographic documentation
Photographic records may accompany selected measurement events to document morphology, architecture, injury, health, and developmental changes that cannot be fully represented by numerical measurements.

## Weather data
Historical weather data is being sourced from [Open-Meteo.com](https://open-meteo.com) using the default Reanalysis model settings.


## Versioning
This repository is maintained as a versioned, evolving dataset. The working repository may change as observations accumulate and measurement protocols are refined. Stable releases will represent defined snapshots of the dataset.
The specifics of the versioning is still a work-in-progress, but given the time intervals of the measurement cycles, I am considering release cycles that fit into the natural breaks of those measurement cycles.  For example, the last of the 45/75-day measurements for DM took place on 20-SEP-2026, and the first of the 60/90-day measurements starts on 23-SEP-2026.  Subsequent cycles for DM will always have this small break between, so I am strongly considering a named release for each of these cycles.  I will probably prototype the details of what to do for a release using the recently concluded 45-day cycle, but I do not expect to formally cut the release until the end of the 60-day cycle, since that one aligns with the initial goal of 30 day increments for releases.


## Current development version: 0.1
First planned stable dataset release: v1.0

## Reproducibility / future analysis
Analysis scripts and notebooks will be added as the dataset develops. Derived results should be reproducible from the preserved raw observations whenever practical.

## Citation
If you use these data, please cite this repository and the specific dataset release from which the data were obtained. Citation information is provided in CITATION.cff.
PENDING - create and populate CITATION.cff

## License
PENDING - select a license, then add the details as appropriate.

## Author / contact
Maintainer: https://github.com/0xa08ab242

Questions, corrections, and suggestions are welcome through GitHub Issues.

## Why "The Sieve of Theophrastus"?

The name is a play on the Sieve of Eratosthenes, an algorithm for progressively eliminating composite numbers to reveal prime numbers.

Here, the "sieve" is metaphorical: repeated observations filter the complex, variable process of plant growth into increasingly useful measurements, while preserving the individual observations from which those patterns emerge.

Theophrastus was chosen because his Enquiry into Plants represents one of the earliest systematic attempts to describe and understand plants as living organisms rather than merely cataloguing their uses.

### End of Line
