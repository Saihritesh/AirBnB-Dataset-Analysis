# AirBnB-Dataset-Analysis
## KPI's for the Analysis 
### Objective 
Analyse the AirBNB listings and derive actionable insights that can help improve pricing strategies, host performance, customer satisfaction, and overall marketplace efficiency.


### KPI 1: Pricing Drivers Analysis

#### Business Question
What factors influence Airbnb listing prices the most?

#### Metrics
- Average Price by Room Type
- Average Price by Neighborhood Group
- Average Price by Neighborhood
- Price vs Review Score
- Price vs Availability


#### Expected Outcome
Identify the strongest factors affecting listing prices and understand market segmentation.

---

### KPI 2: Neighborhood Market Analysis

#### Business Question
Which neighborhoods represent the strongest Airbnb markets?

#### Metrics
- Number of Listings
- Average Price
- Average Review Score
- Reviews Per Month
- Availability

#### Expected Outcome
Identify premium markets, high-demand areas, and potential market opportunities.

---

### KPI 3: Host Success Analysis

#### Business Question
What characteristics make hosts successful?

#### Metrics
- Host Verification Status
- Average Review Score
- Reviews Per Month
- Availability
- Number of Listings Managed
#### Expected Outcome
Determine whether verified and professional hosts outperform other hosts.

---

### KPI 4: Demand & Occupancy Analysis

#### Business Question
Which listings appear to have the strongest demand?

#### Metrics
- Availability 365
- Reviews Per Month
- Number of Reviews
- Price

#### Demand Indicators

High Demand:
- Low Availability
- High Reviews Per Month

Low Demand:
- High Availability
- Low Reviews Per Month

#### Expected Outcome
Identify characteristics associated with highly demanded listings.

---

### KPI 5: Customer Satisfaction Analysis

#### Business Question
What factors contribute to higher review ratings?

#### Metrics
- Review Rate Number
- Price
- Room Type
- Host Verification
- Availability
- Instant Bookable Status

#### Expected Outcome
Identify factors that drive positive guest experiences and better ratings.

---

### KPI 6: Price Recommendation Model

#### Business Question
Can listing prices be estimated using listing characteristics?

#### Target Variable
- Price

#### Features
- Neighborhood Group
- Neighborhood
- Room Type
- Host Verification
- Instant Bookable
- Availability
- Review Rate Number
- Reviews Per Month
- Construction Year
- Host Listings Count

#### Model Type
- Linear Regression
- Random Forest Regressor
- XGBoost (Optional)

#### Evaluation Metrics
- MAE
- RMSE
- R² Score
### Expected Outcome
Develop a pricing recommendation system capable of estimating listing prices from listing attributes.
