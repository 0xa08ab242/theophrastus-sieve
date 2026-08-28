# Measurement Protocol

**Protocol version:** 1.0  
**Status:** Active  
**Effective date:** 2026-08-19    
**Project:** The Sieve of Theophrastus

---

## 1. Purpose

This document defines the procedures used to collect quantitative
measurements and associated observations for specimens included in
The Sieve of Theophrastus dataset.

The purpose of the protocol is to produce measurements that are:

- repeatable where practical;
- comparable between specimens;
- comparable across measurement dates;
- minimally disruptive to young or fragile specimens; and
- sufficiently documented to permit later interpretation and reuse.

This protocol applies to [all specimens / specified taxa / specified
developmental stages].

---

## 2. General principles

### 2.1 Individual specimens

Each specimen is assigned a permanent unique identifier.

Specimen identifiers are never reused or reassigned.

All measurements and events are associated with the specimen's
permanent identifier.

### 2.2 Raw observations

Raw observations are recorded as observed.

Measurements are not replaced by calculated, extrapolated, estimated,
or model-derived values.

Derived quantities such as growth rates, means, and modeled growth
curves are produced during analysis.

### 2.3 Missing observations

If a measurement cannot or should not be obtained, the measurement is
recorded as missing (`NA`) rather than estimated.

Reasons for missing measurements may be documented in the associated
notes or event record.

### 2.4 Measurement date

The actual calendar date on which a measurement is made is recorded.

Specimen age is calculated from the recorded emergence date rather
than inferred from the intended measurement interval.

---

# 3. Measurement schedule

## 3.1 Routine measurements

Routine quantitative measurements are generally collected at
approximately 30-day intervals following emergence.

The intended interval is approximately:

- 30 days
- 60 days
- 90 days
- etc.

The actual measurement date takes precedence over the intended
interval.

## 3.2 Developmental or event-based measurements

Additional measurements may be collected when significant events occur,
including but not limited to:

- germination;
- emergence of a new growth flush;
- transplanting;
- significant injury;
- substantial environmental stress;
- recovery from stress;
- onset of dormancy;
- other events judged potentially relevant to subsequent growth.

## 3.3 Very young specimens

Measurements that could risk damaging a specimen may be omitted.

In particular, stem diameter measurements are not routinely attempted
on specimens whose stems are judged too small or fragile to measure
safely.

Such measurements are recorded as missing rather than estimated.

---

# 4. General measurement conditions

Where practical, measurements should be collected under similar
conditions between measurement events.

Record any unusual conditions that could affect measurements, including:

- recent watering;
- recent transplanting;
- unusual temperature;
- mechanical disturbance;
- wilting;
- severe environmental stress;
- injury;
- pest or disease symptoms;
- other relevant conditions.

Measurements should be performed without manipulating the specimen
beyond what is reasonably necessary to obtain the measurement.

---

# 5. Age calculation

Specimen age is expressed in days since recorded emergence.

### Definition of emergency

Emergence date is recorded as the date on which the seedling shoot is first 
observed to have emerged after being sown.

### Age calculation

Age in days is calculated as:

`measurement date - emergence date`

The calculated age is stored in the dataset as `age_days`.

The intended measurement interval is not used to determine specimen age.

---

# 6. Vertical height

## 6.1 Definition

Vertical height is the vertical distance from the defined substrate
reference point to the highest living vegetative point of the specimen.

Vertical height is a vertical projection and does not follow the
curvature of the stem or branches.

## 6.2 Reference point

The reference point is:

[DEFINE EXACTLY — e.g. substrate surface at the point where the
primary stem emerges.]

## 6.3 Upper endpoint

The upper endpoint is:

[DEFINE — e.g. highest living leaf, terminal bud, or other defined
vegetative point.]

## 6.4 Measurement procedure

1. Specimen is in its natural upright position as it sits in the container or
planted in the ground.
2. The specimen is required to remain in its natural resting orientation.
3. A rigid rule with visible length indicators is placed behind the upper
endpoint.
4. The end of the ruler placed at the level of the soil near the stem and 
positioned vertically, without leaning.
5. The highest mark that the upper endpoint reaches is the measured value.  If
the upper endpoint exceeds one mark and fails to reach the next mark, the 
lesser mark is the value used.  The precision is determined by the instrument.
For example, if the ruler only shows one eighth of an inch divisions, then the
measured results will be constrained to eighths, not estimated sixteenths.

## 6.5 Units

**Canonical unit:** inches (`in`)

## 6.6 Notes

Vertical height is distinct from leader length.

A leaning or curved specimen may therefore have a leader length
substantially greater than its vertical height.

---

# 7. Leader length

## 7.1 Definition

Leader length is the length of the designated leader measured along
the physical path of the leader from its defined base to its terminal
point.

## 7.2 Leader selection

If multiple leaders are present:

THE LONGEST LEADER IS USED.

## 7.3 Measurement procedure

A flexible string, cord, or similar, is placed adjacent to the stem as where it
 touches the soil, and carefully holding it adjacent and touching the stem, the
 string mimics the shape and length of the path from soil to the tip of the 
leader, where the distal end of the string is marked.  The string is then 
removed from the specimen and placed adjacent to a straight-edge, ridig ruler 
and the straightened length of the string is measured.

## 7.4 Units

**Canonical unit:** inches (`in`)

## 7.5 Relationship to vertical height

Leader length should not be interpreted as vertical height.

In specimens exhibiting leaning, curvature, branching, or other
non-vertical growth, leader length may exceed vertical height.

---

# 8. Crown width

## 8.1 Definition

Crown width is the maximum horizontal width of the living crown.

## 8.2 Included material

Include:

leaves / living branches / other

Exclude:

dead tissue

## 8.3 Measurement procedure

Maximum crown width is the only dimension recorded.

## 8.4 Units

**Canonical unit:** inches (`in`)

---

# 9. Stem diameter

## 9.1 Definition

Stem diameter is the diameter of the stem measured at a standardized
location.

## 9.2 Measurement location

The measurement location is between the substrate and the first (false 
leaves), roughly a thumbs' width above the substrate, because the 
calipers are supported on the hands above the substrate to avoid 
damaging the seedlings.

The same reference location should be used for repeated measurements
where practical.

## 9.3 Instrument

Digital calipers

Resolution:

XX mm

## 9.4 Measurement procedure

Calipers rest upon the hand, which rests on the substrait, and positioned 
perpendicular to the stem to be measured.  The thumb wheel of the calipers
are used to close the gap until both caliper sides touch the stem, but the
calipers are not pressed into the stem.  The measurement is read before 
moving the calipers.  The instrument is tared before each measurement.

Attempt to measure the stem diameter at two perpendicular angles at the same
height above the substrait and below the false leaves.  The presented value is
the average of the measurements done at different angles.

If necessary, remove bracing jig elements to perform the measurements.

## 9.5 Young specimens

Stem diameter measurements may be omitted when the stem is considered
too small or fragile to measure without risking damage.

The absence of a measurement is not interpreted as zero diameter.

## 9.6 Units

**Canonical unit:** millimeters (`mm`)

## 9.7 Precision

Measurements are recorded to:

XX.XX mm

Precision should reflect the actual resolution and repeatability of
the measurement instrument rather than implying greater accuracy than
the instrument provides.

---

# 10. Measurement precision and rounding

Measurements should be recorded at the highest practical precision
supported by the instrument and measurement technique.

Rounding for presentation or analysis should not overwrite the raw
measurement.

---

# 11. Health observations

Health observations are recorded separately from quantitative
measurements where practical.

The health vocabulary is intentionally extensible.

Initial categories include:

- healthy
- minor stress
- moderate stress
- severe stress
- injury
- pest damage
- disease symptoms
- chlorosis
- wilting
- leaf loss
- transplant stress
- recovery
- dormancy
- mortality
- unknown

These categories describe observed conditions and do not necessarily
represent diagnoses.

Additional categories may be added as new conditions are encountered.

---

# 12. Events

Events are recorded when an occurrence may plausibly affect subsequent
growth or interpretation of measurements.

Examples include:

- transplanting;
- physical injury;
- growing-tip damage;
- environmental stress;
- unusual temperature exposure;
- pest activity;
- disease symptoms;
- substantial defoliation;
- recovery from stress;
- mortality.

Events should include:

- specimen identifier;
- date;
- event category;
- concise description;
- additional notes where appropriate.

---

# 13. Environmental observations

Environmental information is recorded when available and considered
potentially relevant to interpretation of growth.

Relevant observations may include:

- temperature;
- light exposure;
- watering;
- humidity;
- substrate conditions;
- container changes;
- outdoor/indoor location;
- unusual weather;
- other cultivation conditions.

[DEFINE WHICH OF THESE ARE CURRENTLY SYSTEMATICALLY RECORDED.]

---

# 14. Photographic documentation

Photographs may be collected to document:

- overall morphology;
- growth architecture;
- leaning;
- branching;
- injury;
- health conditions;
- developmental changes.

Where practical, photographs should include:

- specimen identifier;
- measurement date;
- scale reference;
- consistent background or orientation.

[DEFINE CURRENT PHOTOGRAPHY PROCEDURE.]

The photographic procedure is still a work-in-progress, but the provisional
steps include at least 3 photographs:

- picture of the specimen and the label within the same frame
- picture of the specimen from top-down, where the bottom of the frame is the
near side, where the specimen label is located
- picture from an oblique angle showing the stem at the substrait, the entire 
crown width, and the top, where the angle shows the top of the leaves

---

# 15. Deviations from protocol

If a measurement cannot be obtained according to the normal procedure,
the deviation should be documented rather than concealed.

Examples:

- specimen too fragile to measure;
- unusual morphology;
- damaged measuring point;
- measurement instrument unavailable;
- specimen inaccessible;
- environmental conditions prevented measurement.

Deviations should be recorded in the relevant notes or event record.

---

# 16. Protocol revisions

This protocol is versioned.

Changes to the protocol are documented rather than silently applied to
historical measurements.

| Version | Date | Change |
|---|---|---|
| 0.5 | 2026-06-19 | Preliminary protocol |
| 1.0 | 2026-08-19 | Initial protocol |
| 1.1 | 2026-08-28 | Revised stem diameter and added provisional photography |
| 1.1 | YYYY-MM-DD | [Description] |

Historical measurements retain the protocol version under which they
were collected where practical.

---

# 17. Related documentation

- `data/individuals.csv`
- `data/acquisitions.csv`
- `data/measurements.csv`
- `data/events.csv`
- `documentation/data-dictionary.md`
- `CITATION.cff`
- `README.md`