# ARGO Probabilistic Density Maps

## Overview

This project aims to analyze 20 years of T/S metadata from Argo floats deployed in the Indian Ocean to identify regions where data is available despite the absence of ship-based deployments. By examining current drift patterns and deriving probability density maps, we aim to determine areas where Argo float deployments using ships are unnecessary.

## Objectives

1. **Metadata Analysis**: Identify regions with available data even though instruments were not deployed using ships.
2. **Current Drift Analysis**: Determine regions where observations can still be obtained based on the current drift without the need for ship deployment.
3. **Probability Density Maps**: Create probability density maps to evaluate:
    - Locations where Argo floats were deployed and observations are available.
    - Locations where no deployment happened, but data is still available.
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

## Getting Started

### Prerequisites

- MATLAB or another data analysis software
- Access to Argo project data and metadata

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ARGO-Probabilistic-Density-Maps.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ARGO-Probabilistic-Density-Maps
    ```

3. Follow the scripts and documentation to run the analysis.

## Usage

1. Collect and preprocess the Argo float data.
2. Run the provided MATLAB scripts to perform metadata analysis and generate probability density maps.
3. Review the generated maps and data for insights into optimal deployment strategies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Argo Project for providing the data and metadata.
- Contributors and developers involved in the project.

