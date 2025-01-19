# Blood Group Data Analysis

This project involves analyzing blood group data from two perspectives:
1. **Donation and Receiving Probabilities**: The probabilities for each blood group to donate and receive blood.
2. **Global Population Distribution**: The global population distribution across different blood groups, visualized through population fractions.

## 1. Blood Group Donation and Receiving Probabilities

This analysis focuses on the probabilities of each blood group donating blood to others and receiving blood from others.

- **Donating Probabilities**: The probability of a blood group donating blood to others.
- **Receiving Probabilities**: The probability of a blood group receiving blood from others.

### Methodology:
- Blood groups considered: `['O-', 'O+', 'A-', 'A+', 'B-', 'B+', 'AB-', 'AB+']`
- Donating and receiving probabilities are given as fixed values based on medical guidelines.
- Two histograms are plotted to visualize the probabilities for donating and receiving blood.

## 2. Blood Group Population Distribution

This analysis focuses on the global distribution of blood groups and calculates the population fraction (weight) for each blood group. The population data is based on global estimates for blood group distribution.

### Methodology:
- Blood groups considered: `['O-', 'O+', 'A-', 'A+', 'B-', 'B+', 'AB-', 'AB+']`
- Population percentages are estimated based on global blood group distribution.
- Population fractions are calculated by converting the population percentages into fractions.
- A bar chart is used to visualize the population distribution of each blood group.

## Data Sources

- **Blood Group Donation and Receiving Probabilities**: The probabilities used are based on common medical practices and transfusion guidelines.
- **Blood Group Population Data**: The population distribution data used in this project is based on the following sources:
  - **Data on the global distribution of blood types**: According to research from the **American Red Cross** and other medical resources, the distribution of blood groups varies by geographic location. Here is an example breakdown of the world population distribution by blood group:
    - **O-**: 7%
    - **O+**: 38%
    - **A-**: 6%
    - **A+**: 34%
    - **B-**: 2%
    - **B+**: 9%
    - **AB-**: 1%
    - **AB+**: 3%

    Reference: [American Red Cross Blood Type Distribution](https://www.redcrossblood.org/donate-blood/blood-types.html)
