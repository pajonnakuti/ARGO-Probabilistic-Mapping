# ARGO Probabilistic Density Maps

## Introduction

Ocean observation platforms called Argo floats have been deployed in the Indian Ocean for the past 20 years. Deployment of these floats is usually conducted using ships, which may not always be available for all regions. This project aims to:

1. Identify regions where data is available even though instruments were not deployed using ships, using 20 years of T/S metadata.
2. Identify regions where deployment using ships is unnecessary based on current drift patterns.
3. Derive probability density maps considering the following:
    - Locations where Argo floats were deployed and observations are available.
    - Locations where no deployment happened, but data is still available.

## Objectives

- **Metadata Analysis**: Analyze the T/S metadata to identify regions with available data despite the lack of instrument deployment using ships.
- **Current Drift Analysis**: Determine regions where observations can still be obtained based on the current drift without the need for ship deployment.
- **Probability Density Maps**: Create probability density maps to evaluate:
    - The likelihood of obtaining observations in certain areas without deploying instruments using ships.
    - The confidence and probability that specific areas do not need deployment but can still provide data.

## Methodology

1. **Data Collection**:
    - Gather 20 years of T/S metadata from the Argo float observations in the Indian Ocean.

2. **Data Analysis**:
    - Identify regions with and without ship-based deployments.
    - Analyze the drift patterns of the Argo floats to determine regions where data can be obtained without deployment.

3. **Probability and Confidence Calculation**:
    - Consider the two events (deployment with and without ship) as mutually exclusive.
    - Calculate the probability and confidence levels for obtaining data in regions without ship-based deployment.

4. **Density Map Generation**:
    - Create probability density maps using the analyzed data to visually represent the regions with and without deployment needs.

## Results

### Regions with Data Availability Without Ship Deployment
Using the metadata analysis, regions were identified where data is available even though instruments were not deployed using ships.

### Regions with No Need for Ship Deployment
Based on current drift analysis, regions were identified where observations can still be obtained without the need for ship deployment.

### Probability Density Maps
Probability density maps were derived to show:
- Locations where deployment occurred and data is available.
- Locations where no deployment occurred, but data is still available.
- The confidence and probability that certain areas do not need deployment but can still obtain data.

![Probability Density Map](path_to_image.png)

## Conclusion

This analysis provides insights into regions where Argo float deployments using ships are unnecessary, enabling more efficient use of resources and better planning for future deployments. The probability density maps offer a visual representation of the likelihood of obtaining observations in various regions, enhancing the decision-making process for ocean observation strategies.

## References

- Argo Project Data and Metadata
- Indian Ocean Current Drift Patterns
