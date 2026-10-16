# Healthcare Patient Analytics Project

## Project Overview
This project analyses 5,000 synthetic hospital encounters using Python and Pandas. It explores hospital length of stay, patient pain scores, department-level patterns, and diagnosis-level trends.

## Business Objective
To demonstrate how healthcare data analytics can help monitor hospital operations, identify patterns, and communicate findings through data visualisation.

## Dataset Summary
- Total hospital encounters: 5,000
- Unique patients: 2,603
- Departments: 5
- Diagnoses: 8
- Dataset type: Synthetic educational data, not real patient records

## Tools Used
- Python
- Pandas
- Matplotlib
- SciPy
- Google Colab

## Data Quality Checks
Checked for missing values, duplicate records, duplicate encounter IDs, inconsistent length-of-stay values, invalid dates, negative stays, invalid ages, and pain scores outside the 0–10 range.

No issues were detected by these checks in this dataset.

## Key Performance Indicators
- Average length of stay: 6.61 days
- Average pain score: 4.75/10
- Long-stay encounters: 180
- Long-stay rate: 3.60%

Long stay was defined as more than 14 days.

## Key Findings
1. Neurology had a long-stay rate of 13.38%.
2. Fracture encounters had a long-stay rate of 15.61%.
3. Stroke encounters had a long-stay rate of 13.38%.
4. The long-stay group had a higher average pain score than the non-long-stay group (5.64 versus 4.72).
5. Overall pain-score distributions differed statistically between the two groups (Mann–Whitney U test, p < 0.001).
6. Diagnosis-specific tests did not find statistically significant pain-score distribution differences for Fracture or Stroke.

## Visualisations
The repository includes charts showing:
- Long-stay rate by department
- Average pain score by stay group

## Limitations
This dataset is synthetic and intended for educational and portfolio use. Findings do not establish causation or represent actual hospital performance.

## Skills Demonstrated
- Healthcare KPI development
- Data quality validation
- Exploratory data analysis
- Statistical hypothesis
