# Data Understanding: Fibromyalgia and Autistic-like Behaviors Study

## Dataset Overview

This dataset investigates the relationship between fibromyalgia and autistic-like behaviors, with a focus on hypersensitization in sensory processing sensitivity. The study employs a case-control design to compare individuals with fibromyalgia against healthy controls across multiple validated assessment instruments.

## Sample Characteristics

**Total Participants:** 399 (excluding header row)

### Group Distribution
- **Control Group (Group 0):** 139 participants (34.8%)
- **Fibromyalgia Group (Group 1):** 260 participants (65.2%)

### Age Demographics
- **Control Group Age Range:** 18-87 years (Mean: 43.97 years)
- **Fibromyalgia Group Age Range:** 20-79 years (Mean: 48.07 years)

### Sex Distribution
- **Male (Sex 0):** 33 participants (8.3%)
- **Female (Sex 1):** 366 participants (91.7%)

## Assessment Instruments

### 1. Central Sensitization Inventory (CSI)
- **Items:** CSI1-CSI25 (25 individual items)
- **Total Score:** CSI_total (calculated sum)
- **Purpose:** Measures central sensitization symptoms commonly associated with fibromyalgia
- **Dataset Mean:** 59.74

### 2. Sensory Processing Sensitivity Questionnaire (SPSQ)
- **Part A Items:** SPSQa_1 to SPSQa_8 (8 items)
- **Part B Items:** SPSQb_1 to SPSQb_8 (8 items)
- **Total Scores:** 
  - SPS_total (overall sensitivity score, Mean: 106.13)
  - SPSa_total (Part A subscore, Mean: 50.62)
  - SPSb_total (Part B subscore, Mean: 55.51)
- **Purpose:** Assesses sensory processing sensitivity and hypersensitivity traits

### 3. Additional Variables
- **Socioeconomic Status (SES):** Continuous variable indicating participant's socioeconomic background
- **Participant ID:** Unique identifier for each participant

## Study Design Implications

The dataset structure supports investigation of:
1. **Central sensitization differences** between fibromyalgia patients and controls
2. **Sensory processing sensitivity patterns** across both groups
3. **Potential autistic-like behavioral traits** in fibromyalgia patients through sensory hypersensitivity measures
4. **Age and sex effects** on symptom presentation
5. **Socioeconomic factors** influencing symptom reporting or access to care

## Data Quality Notes

- Female participants are heavily overrepresented (91.7%), which is consistent with fibromyalgia epidemiology
- The fibromyalgia group is larger than the control group, providing adequate power for detecting group differences
- Age ranges overlap substantially between groups, allowing for meaningful comparisons
- The dataset appears complete with calculated total scores for all major instruments