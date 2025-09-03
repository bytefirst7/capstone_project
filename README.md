**Problem Statement:**

**Objective**
Given a dataset of seismic activity in the Seattle area, develop a predictive model to estimate the likelihood of the next significant earthquake occurring within one of three timeframes:
- Within 2 years
- Within 5 years
- Within 10 years

**Goal**
Classify the expected time window for the next earthquake based on historical patterns, magnitude trends, and other relevant geophysical indicators.

**Data Source**
To address this question, I will collect seismic activity data from the https://www.pnsn.org/ Pacific Northwest Seismic Network (PNSN) Links to an external site., a trusted and comprehensive resource for earthquake monitoring in the region. The dataset will include:

- Timestamped seismic events
- Magnitude and depth of each event
- Geographic coordinates
- Fault line proximity and tectonic context
- Historical frequency and clustering patterns

**Modeling Techniques**
To explore the predictive landscape thoroughly, I will implement and compare three distinct modeling approaches:

1. Regression Model
    - Purpose: Estimate the time until the next earthquake as a continuous variable
2. Classification Model
    - Purpose: Categorize the likelihood of an earthquake occurring within predefined time windows (e.g., 2, 5, or 10 years).
3. Time Series Model
    - Purpose: Capture temporal dependencies and trends in seismic activity.

**Expected Outcomes**
The models are expected to produce a probabilistic or categorical estimate of when the next significant earthquake might occur in the Seattle area. This could include:

- A predicted time range (e.g., “likely within 5–7 years”)
- Confidence scores or probabilities for each time window
- Insights into contributing factors (e.g., recent seismic clusters or fault line stress)

**Why This Matters**
This question holds personal and civic importance. As a resident of Seattle, I believe that predictive analytics in earthquake forecasting can:

- Enhance public safety by informing early warning systems
- Support urban planning and infrastructure resilience
- Guide emergency preparedness for local agencies and communities
