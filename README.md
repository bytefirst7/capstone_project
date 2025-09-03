**Problem Statement:**

**Objective**
Given a dataset of seismic activity in the Seattle area, develop a predictive model to estimate the likelihood of the next significant earthquake occurring within one of three timeframes:
- Within 2 years
- Within 5 years
- Within 10 years

**Goal**
Classify the expected time window for the next earthquake based on historical patterns, magnitude trends, and other relevant geophysical indicators.

**Data Source**
To address this question, I will collect seismic activity data from the [Pacific Northwest Seismic Network](https://www.pnsn.org/), a trusted and comprehensive resource for earthquake monitoring in the region. The dataset will include:

[Full Dateset](https://www.pnsn.org/events?mag_min=&mag_max=&date_start=1990-01-01&date_end=2025-08-19&custom-ui=circle&lat_min=&lat_max=&lon_min=&lon_max=&city_center=&lat_center=45.78943&lon_center=-121.47817&radius=586753.37195&depth_min=-5&depth_max=1000&etypes%5B%5D=le&etypes%5B%5D=re&etypes%5B%5D=lf&gap_max=&distance=&phase_min=&s_phase_min=&rms_max=&sort_by=event_time_utc&order=desc)

- Timestamped seismic events
- Magnitude and depth of each event
- Geographic coordinates
- Fault line proximity and tectonic context

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
