# NHS Workforce Vacancy Risk Register

## Overview
A workforce capacity risk register analysing nursing and administrative vacancy rates across NHS regions in England.

## Problem Statement
Persistent workforce vacancies pose a significant risk to service delivery. Regional variation suggests uneven pressure across the system, particularly for nursing roles.

## Stakeholders
- NHS England
- ICS workforce planners
- Trust operational leadership
- Commissioners
- Patients

## Key Questions
- Are nursing vacancies increasing faster in London compared to the North?
- Which regions represent the highest workforce risk?
- How concentrated are staffing shortages by staff group?

## Data Sources
- **NHS Workforce Statistics – Summary Tables** (NHS Digital)  
- **Time period:** Latest available reporting period  
- **Coverage and limitations:** Aggregated regional data. No trust-level detail.

## Approach
- Data ingestion and cleaning
- Calculation of vacancy rates
- Risk classification using RAG thresholds
- Regional comparison analysis

## Key Findings
- Nursing vacancies are consistently higher than administrative roles
- London shows sustained vacancy pressure
- Workforce risk is unevenly distributed across regions

## Visual Outputs
- Vacancy rate bar charts by region  
- RAG risk register tables  
- Regional comparison visuals

## Delivery Considerations
- Vacancy definitions may change over time
- Aggregated data limits local insight
- RAG thresholds are indicative not absolute

## Recommendations
- Prioritise nursing recruitment and retention initiatives
- Focus interventions on highest-risk regions
- Use vacancy rates as a standing operational risk metric

## Impact
Reducing vacancy rates would improve service resilience, staff wellbeing, and patient experience.

## Tools Used
Python pandas numpy matplotlib VSCode

## How to Run
1. Clone the repository  
2. Install dependencies  
3. Add workforce summary data to `data/raw`  
4. Run `python run.py`

## Next Steps
- Add trust-level workforce data
- Model vacancy reduction scenarios
- Link workforce gaps to performance outcomes
