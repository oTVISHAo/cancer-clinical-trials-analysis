# cancer-clinical-trials-analysis
# Cancer Clinical Trials Data Analysis

## Overview

This project analyzes a randomized sample of 400 cancer-related interventional clinical trials from ClinicalTrials.gov.

The project focuses on understanding clinical trial phase, enrollment, recruitment status, funding, sponsors, and participant age groups.

## Tools

- Google Sheets
- Pivot Tables
- Data Cleaning
- Data Visualization

## Dataset

The dataset contains 400 randomly selected clinical trials from a larger ClinicalTrials.gov dataset.

### Fields analyzed

- NCT Number
- Study Title
- Study Status
- Conditions
- Interventions
- Sponsor
- Collaborators
- Sex
- Age
- Phases
- Enrollment
- Funder Type
- Study Type
- Study Design

## Data Preparation

The data was profiled and cleaned before analysis.

Key preparation steps included:

- Checking for missing values
- Validating NCT identifiers
- Checking for duplicate studies
- Converting enrollment values to numeric format
- Handling missing collaborator information
- Retaining valid multi-value intervention and phase fields

## Analysis

The project examines:

1. Trial distribution by phase
2. Average enrollment by phase
3. Trial distribution by funder type
4. Study recruitment status
5. Top clinical trial sponsors
6. Participant age groups

## Key Findings

- Phase 2 represented 59.5% of the sampled trials.
- 55.75% of sampled trials were classified as recruiting.
- Phase 3 trials had an average enrollment of approximately 493 participants.
- Phase 2 trials had an average enrollment of approximately 105 participants.
- 64.25% of sampled trials were classified under the `OTHER` funder category.

## Dashboard

A Google Sheets dashboard was created to visualize the major findings from the analysis.
![Cancer Clinical Trials Dashboard](cancer-clinical-trials-analysis/clinical-trials-dashboard.png)

## Future Improvements

Future versions of this project will incorporate:

- SQL analysis
- Python/pandas data analysis
- Additional visualizations
- Deeper analysis of clinical trial characteristics
