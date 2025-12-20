# Integrated Actuarial Reserving Framework (GI)

## Overview

This repository contains a professional-grade Actuarial Reserving Toolset developed in Excel. It is designed to automate the estimation of Ultimate Claims for General Insurance portfolios (specifically Motor and Catastrophe lines) using a multi-model approach.

The framework is built to address modern industry challenges: IFRS 17 traceability, data governance, and scenario-based stress testing.

## Key Features & Methodology

The toolkit integrates three core actuarial methodologies to ensure reserve adequacy:

### Chain Ladder (Basic & Expected)
Utilises volume-weighted and simple-average LDFs with a built-in "Expected" method toggle for years with significant premium growth or data volatility.

### Bornhuetter-Ferguson (BF)
Blends actual loss experience with an initial expected loss ratio (IELR), providing stability for immature accident years.

### Average Cost Per Claim (ACPC)
Separates frequency and severity to identify underlying claim trends and inflation impacts.

## Technical Enhancements for Industry Needs

Tailored to the standards of top-tier consulting and insurance firms:

### Automation via Power Query
Replaced manual data entry with a scalable "Raw Data" ingestion system, reducing BAU processing time and improving auditability.

### Outlier Mitigation
Implemented conditional formatting "Heat Maps" to identify and exclude high/low development factors, ensuring more resilient ultimate estimates.

### Dynamic Scenario Switch
A user-controlled dashboard allowing real-time switching between "Optimistic," "Best Estimate," and "Pessimistic" scenarios for stress testing against catastrophe volatility.

### Validation Diagnostics
Included Actual vs. Expected (A/E) tracking and QQ-plots to validate model assumptions against observed experience.
